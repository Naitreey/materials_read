language
========
- tutorial --- Python official documentation (已读)
- Python Language Reference 2.7.10 --- Python official documentation (已读)
- Beginning Python From Novice to Professional (已读)
- What's New In Python
  * What’s New In Python 3.0
  * What’s New In Python 3.1
  * What’s New In Python 3.2
  * What’s New In Python 3.3
- PEPs
  * PEP 0008 --- Style Guide for Python Code
  * PEP 0273 --- Import Modules from Zip Archives
  * PEP 0257 --- Docstring Conventions
  * PEP 0302 --- New Import Hooks
  * PEP 0318 --- Decorators For Functions and Methods
  * PEP 0328 --- Imports: Multi-Line and Absolute/Relative
  * PEP 0441 --- Improving Python ZIP Application Support
  * PEP 3113 --- Removal of Tuple Parameter Unpacking
  * PEP 3119 --- Introducing Abstract Base Classes
- Unifying types and classes in Python 2.2
  https://www.python.org/download/releases/2.2.3/descrintro/
- Format String Syntax --- Python Library Reference
- Builtin exception hierarchy
  https://docs.python.org/3.4/library/exceptions.html#exception-hierarchy
- Unicode HowTo
  https://docs.python.org/2/howto/unicode.html#python-2-x-s-unicode-support
- Descriptor HowTo
  https://docs.python.org/2/howto/descriptor.html

libraries and frameworks
========================
concurrency
-----------
- subprocess
- subprocess32
- thread (_thread in py3)
- threading
- multiprocessing
- asyncio
- concurrent.futures

event scheduler
---------------
- sched

text
----
- string
- re
- textwrap
- difflib

io
--
- io
- StringIO

json
----
- json (doc)
- ujson

yaml
----
\itme PyYAML

xml, html
---------
- xml
- xml.dom.minidom
- xml.etree.ElementTree
- xml.etree.cElementTree
- html5lib
- pyquery
- xmltodict
- BeautifulSoup (bs4)
- Scrapy

cmdline
-------
- colorama
- termcolor
- docopt (done: doc)
- getopt
- argparse
- cmd
- shlex
- readline
- rlcompleter

file and directory access
-------------------------
- glob
- fnmatch
- linecache
- pathlib

debugging and profiling
-----------------------
- pdb
- bdb
- tracemalloc
- timeit
- cProfile
- profile
- pstats
- pycallgraph

virtualization
--------------
- guestfs
- libvirt

python itself
-------------
- sys (done: doc)
- sysconfig
- __future__ (done: doc, source)
- traceback (done: 部分 doc and source code)
- py_compile
- inspect
- dis
- weakref
- site
- runpy

.. import

- importlib
- imp
- zipimport
- pkgutil

.. packaging

- pip
- ensurepip
- venv
- setuptools
- distutils

documentation
-------------
- docutils
- Sphinx
- Read the Docs
- pydoc

os-level
--------
- signal
- psutil
- fileinput
- tempfile
- stat
- pwd
- getpass
- errno
- resource
- atexit
- python-prctl
- os (done: doc)
- shutil (done: doc)
- posixpath, a.k.a. os.path (done: doc)
- platform (done: doc)
- posix

time
----
- time
- datetime

test
----
- trace
- coverage
- unittest
- doctest

refactor
--------
- pylint

hash
----
- hashlib

bin
---
- base64
- binascii

crypto
------
- ssl
- rsa

compression
-----------
- zlib (done: doc)
- gzip
- bz2
- lzma
- zipfile
- zipapp (py3 only)
- tarfile

encoding
--------
- codecs
- unicodedata
- chardet

ABC
---
- abc
- collections.abc
- numbers

C and system-level interfaces
-----------------------------
- array
- struct
- fcntl
- mmap

data structure
--------------
- collections
- heapq
- Queue
- enum

object serialization
--------------------
- shelve
- pickle
- pickletools

database
--------
- pymongo (mongodb)
- bson (mongodb)
- psycopg2
- sqlite3
- sqlalchemy
- elasticsearch
- elasticsearch_dsl

GUI programming
---------------
- wx (wxPython)
- PyQt

network programming
-------------------

.. lower-level structure

- socket
- netifaces
- dpkt
- ipaddress
- pyroute2

.. client

- paramiko
- requests
- urlparse (urllib.parse in py3)
- urllib (urllib in py3)
- urllib2 (urllib in py3)
- urllib3
- pycurl
- httplib (http.client in py3)
- xmlrpclib

.. server

- wsgiref
- SocketServer
- BaseHTTPServer (http.server in py3)
- SimpleXMLRPCServer
- select
- selectors
- cgi
- cgitb
- bottle (doc & source)
- uWSGI
- Twisted
- Django
- Flask
- Tornado
- shadowsocks

.. cookies

- Cookie (http.cookies in py3) (doc & source)

mime
----
- mimetype

template
--------
- jinja2

email
-----
- email
- smtplib
- smtpd
- poplib
- imaplib

SMB
---
- pysmb

SNMP
----
- pysnmp

asn1
----
- pyasn1

scientific computing
--------------------
- math
- decimal
- statistics
- SciPy
- NumPy
- IPython
- Sympy
- Matplotlib
- pandas

c extension
-----------
- ctypes
- SWIG

graphics and image processing
-----------------------------
- turtle

py2py3
------
- six
- future

codingstyle
-----------
- flake8

queue
-----
- beanstalkc (done: official tutorial)
- pynsq

misc
----
- __main__ (done: doc)
- yara
- pypdf2
- gc
- functools
- itertools
- contextlib
- operator
- keyword
- logging
- ConfigParser
- jsbeautifier
- textwrap
- uuid
- types (done: doc, source)
- copy
- warnings
- pprint
- webbrowser
- random
- csv

dev tools
=========
- The Python Profilers
  https://docs.python.org/2/library/profile.html
- docutils
  * docutils front-end tools
    http://docutils.sourceforge.net/docs/user/tools.html
