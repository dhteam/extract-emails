#Sending http request from python

>>> import requests
>>> r = requests.post("http://bugs.python.org", data={'@number': 12524, '@type': 'issue', '@action': 'show'})
>>> print(r.status_code, r.reason)
200 OK
>>> print(r.text[:300] + '...')

<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="en" lang="en">
<head>
<title>
Issue 12524: change httplib docs POST example - Python tracker

</title>
<link rel="shortcut i...
>>> 

#for this install requests 
using <b>sudo pip install requests</b>
