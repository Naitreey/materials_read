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
  * What’s New In Python 3.4
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
- StringIO (io.StringIO)

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
- xmltodict
- html5lib
- pyquery
- BeautifulSoup
- Scrapy
- html
- html.entities
- html.parser

cmdline parser
--------------
- getopt
- optparse
- argparse
- docopt
- click

shell, terminal
---------------
- colorama
- termcolor
- cmd
- shlex
- readline
- rlcompleter
- getpass
- pty

file and directory
------------------
- glob
- fnmatch
- linecache
- pathlib
- filecmp
- stat
- tempfile
- fileinput
- shutil

debugging and profiling
-----------------------
- pdb
- bdb
- dis
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
- sys
- sysconfig
- __future__
- traceback
- py_compile
- inspect
- weakref
- site
- runpy
- keyword
- types

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

C and system level
------------------
- signal
- psutil
- pwd
- spwd
- grp
- errno
- resource
- mmap
- atexit
- python-prctl
- os
- os.path (posixpath)
- platform (done: doc)
- posix
- struct
- ctypes
- fcntl

date, time
----------
- time
- datetime
- calendar

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
- zlib
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

C and low level data
--------------------
data structure
--------------
- collections
- heapq
- Queue
- enum
- array

object serialization
--------------------
- pickle
- pickletools
- shelve

database
--------
- dbm
- dbm.gnu
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

- http and related protocols

  .. client

  * http.client (httplib)
  * urllib (urllib, urlib2)
  * urllib.request
  * urllib.parse (urlparse)
  * urllib.robotparser
  * urllib.error
  * urllib3
  * requests
  * pycurl

  .. server

  * http.server (BaseHTTPServer)
  * bottle
  * Flask
  * uWSGI
  * Django
  * Tornado
  * Twisted

  .. cookies

  * http.cookies (Cookie)
  * http.cookiejar

- ssh

  * paramiko

- XML-RPC
  .. (ok, why not REST?)

  * xmlrpc
  * xmlrpc.client (xmlrpclib)
  * xmlrpc.server (SimpleXMLRPCServer)

.. server

- wsgiref
- socketserver
- select
- selectors
- shadowsocks

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
- cmath
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
- logging
- ConfigParser
- jsbeautifier
- uuid
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
- pdb
- docutils
  * docutils front-end tools
    http://docutils.sourceforge.net/docs/user/tools.html
- pyenv
- pip
- venv
- pylint
- flake8
