# google-auth-sample

非推奨の oauth2client ではなく、google-auth を使って、YouTube Data API を叩くサンプル。

参考: https://developers.google.com/sheets/api/quickstart/python

## Environment

```
$ sw_vers
ProductName:	Mac OS X
ProductVersion:	10.14.6
BuildVersion:	18G103

$ python --version
Python 3.9.0

$ pip --version
pip 20.2.3 from /Users/<USER_NAME>/<PATH>/lib/python3.9/site-packages/pip (python 3.9)

```

## Setup

```
$ pip install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib
```

## Usage 

```
$ python main.py
```
