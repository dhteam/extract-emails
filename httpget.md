# help <a href="http://docs.python-requests.org/en/latest/index.html">http://docs.python-requests.org/en/latest/index.html</a>

or

#http://docs.python-requests.org/en/latest/user/quickstart/#more-complicated-post-requests

#get request 

>>> r = requests.get('https://api.github.com/user', auth=('user', 'pass'))

>>> r.status_code
200

>>> r.headers['content-type']
'application/json; charset=utf8'

>>> r.encoding
'utf-8'

>>> r.text
u'{"type":"User"...'

>>> r.json()
{u'private_gists': 419, u'total_private_repos': 77, ...}

