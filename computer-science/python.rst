language
========
- tutorial --- Python official documentation (已读)

- Python Language Reference 2.7.10 --- Python official documentation (已读)

- Beginning Python From Novice to Professional (已读)

- The Python Standard Library

  * Built-in Constants

- What's New In Python

  * What’s New In Python 3.0
  * What’s New In Python 3.1
  * What’s New In Python 3.2
  * What’s New In Python 3.3
  * What’s New In Python 3.4
  * What’s New In Python 3.5

- PEPs

  * PEP 0008 -- Style Guide for Python Code
  * PEP 0020 -- The Zen of Python
  * PEP 0273 -- Import Modules from Zip Archives
  * PEP 0257 -- Docstring Conventions
  * PEP 0302 -- New Import Hooks
  * PEP 0318 -- Decorators For Functions and Methods
  * PEP 0328 -- Imports: Multi-Line and Absolute/Relative
  * PEP 0441 -- Improving Python ZIP Application Support
  * PEP 3113 -- Removal of Tuple Parameter Unpacking
  * PEP 3119 -- Introducing Abstract Base Classes
  * PEP 3135 -- New Super

- Unifying types and classes in Python 2.2
  https://www.python.org/download/releases/2.2.3/descrintro/

- Format String Syntax --- Python Library Reference

- Builtin exception hierarchy
  https://docs.python.org/3.4/library/exceptions.html#exception-hierarchy

- Unicode HowTo
  https://docs.python.org/2/howto/unicode.html#python-2-x-s-unicode-support

- Descriptor HowTo
  https://docs.python.org/2/howto/descriptor.html

- Buffer protocol

  * Less copies in Python with the buffer protocol and memoryviews
    http://eli.thegreenplace.net/2011/11/28/less-copies-in-python-with-the-buffer-protocol-and-memoryviews

libraries and frameworks
========================
concurrency
-----------
- subprocess (with source)
  * Creating pipelines with subprocess
    http://www.enricozini.org/blog/2009/debian/python-pipes/
  * Python SIGPIPE handling
    http://www.chiark.greenend.org.uk/~cjwatson/blog/python-sigpipe.html
- subprocess32
- thread (_thread in py3)
- threading
- multiprocessing
- asyncio
- uvloop
- concurrent.futures
- gevent

event scheduler
---------------
- sched

text
----
- string
- re
- textwrap
- difflib

encoding
--------
- codecs
- unicodedata
- chardet

io
--
- io
- StringIO (io.StringIO)

data formats and markup
-----------------------

* json
  - json
  - json.tool
  - ujson

* yaml
  - PyYAML

* csv
  - csv

* xml
  - xml
  - xml.dom.minidom
  - xml.etree.ElementTree
  - xmltodict

* html
  - html
  - html.entities
  - html.parser
  - html5lib
  - pyquery
  - BeautifulSoup
  - Scrapy

configuration
-------------
- configparser

cmdline parser
--------------
- getopt
- optparse
- argparse (with source)
- docopt
- click

shell, terminal
---------------
- colorama
- termcolor
- cmd
- code
- shlex
- readline
- rlcompleter
- getpass
- pty

grammar parser
--------------
- parsley

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

python runtime
--------------
- sys
- sysconfig
- builtins
- __future__
- traceback
- py_compile
- compileall
- copy
- inspect
- weakref
- site
- runpy
- keyword
- types
- gc
- contextlib
- pprint

.. import

- importlib
- imp
- zipimport
- pkgutil

.. packaging

- ensurepip
- pip
- wheel
- venv
- setuptools
- pkg_resources
- distutils

functional programming
----------------------
- operator
- functools
- itertools

documentation
-------------
- docutils
- Sphinx
- Read the Docs
- pydoc

system level utils
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
- posix (do not import directly)
- platform (done: doc)
- fcntl
- ctypes
- struct
- array
- pyinotify
- setproctitle

date, time
----------
- time
- datetime
- calendar
- dateutil

coverage & test
---------------
- trace
- coverage
- unittest
- doctest
- pytest

refactor
--------
- pylint

bin
---
- base64
- binascii

hash
----
- hashlib
- hmac

crypto
------
- crypt
- ssl
- rsa

compression
-----------
- zlib
- gzip
- bz2
- lzma
- zipfile
- zipapp
- tarfile

ABC
---
- abc (with source)
- collections.abc (with source)
- numbers

data structure
--------------
- collections (with source)
- heapq
- queue
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

NoSQL
~~~~~

.. mongodb

- pymongo (mongodb)
- bson (mongodb)
- bson.codec_options

.. elasticsearch

- elasticsearch
- elasticsearch_dsl

SQL
~~~

- sqlalchemy

.. sqlite

- sqlite3

.. postgresql

- psycopg2
- asyncpg

.. mysql

- MySQLdb
- mysqlclient
- PyMySQL
- mysql.connector
- mycli

network programming
-------------------

lower-level stuffs
~~~~~~~~~~~~~~~~~~

- socket
- netifaces
- dpkt
- ipaddress
- pyroute2

.. server

- socketserver
- select
- selectors
- shadowsocks

http and related protocols
~~~~~~~~~~~~~~~~~~~~~~~~~~

* http

.. client

* http.client (httplib)
* urllib (urllib, urlib2)
* urllib.request
* urllib.parse (urlparse)
* urllib.robotparser
* urllib.error
* urllib3
* requests
* requests-toolbelt
* pycurl
* querystring-parser (多维数组形式 querystring 解析)

.. server

* http.server (BaseHTTPServer)
* uWSGI
* wsgiref


.. cgi

* cgi

.. cookies

* http.cookies (Cookie)
* http.cookiejar

.. web framework

* bottle (with source)

  - tutorial
    https://bottlepy.org/docs/dev/tutorial.html

* Flask

* django (with source)

  - start
    https://www.djangoproject.com/start/

    * overview
      https://www.djangoproject.com/start/overview/

  - Getting started
    https://docs.djangoproject.com/en/stable/intro/

    * Writing your first Django app, part 1,2,3,4,5,6,7
      https://docs.djangoproject.com/en/stable/intro/tutorial01/
      https://docs.djangoproject.com/en/stable/intro/tutorial02/
      https://docs.djangoproject.com/en/stable/intro/tutorial03/
      https://docs.djangoproject.com/en/stable/intro/tutorial04/
      https://docs.djangoproject.com/en/stable/intro/tutorial05/
      https://docs.djangoproject.com/en/stable/intro/tutorial06/
      https://docs.djangoproject.com/en/stable/intro/tutorial07/

    * Advanced tutorial: How to write reusable apps
      https://docs.djangoproject.com/en/stable/intro/reusable-apps/

    * Django at a glance
      https://docs.djangoproject.com/en/stable/intro/overview/

    * What to read next
      https://docs.djangoproject.com/en/stable/intro/whatsnext/

  - topics

    * Models and databases
      https://docs.djangoproject.com/en/stable/topics/db/

      - Models
        https://docs.djangoproject.com/en/stable/topics/db/models/

      - Making queries
        https://docs.djangoproject.com/en/stable/topics/db/queries/

      - Aggregation
        https://docs.djangoproject.com/en/stable/topics/db/aggregation/

      - Search
        https://docs.djangoproject.com/en/2.0/topics/db/search/

      - Managers
        https://docs.djangoproject.com/en/2.0/topics/db/managers/

      - Database transactions
        https://docs.djangoproject.com/en/stable/topics/db/transactions/

    * Class-based views
      https://docs.djangoproject.com/en/stable/topics/class-based-views/

      - Introduction to class-based views
        https://docs.djangoproject.com/en/stable/topics/class-based-views/intro/

      - Built-in class-based generic views
        https://docs.djangoproject.com/en/stable/topics/class-based-views/generic-display/

      - Form handling with class-based views
        https://docs.djangoproject.com/en/stable/topics/class-based-views/generic-editing/

      - Using mixins with class-based views
        https://docs.djangoproject.com/en/stable/topics/class-based-views/mixins/

    * Migrations
      https://docs.djangoproject.com/en/stable/topics/migrations/

      - How to move model between apps
        https://stackoverflow.com/a/26472482/1602266
        https://stackoverflow.com/a/29622570/1602266
        https://stackoverflow.com/a/30613732/1602266

    * Working with forms
      https://docs.djangoproject.com/en/stable/topics/forms/

      - Creating forms from models
        https://docs.djangoproject.com/en/stable/topics/forms/modelforms/

    * Templates
      https://docs.djangoproject.com/en/stable/topics/templates/

    * Handling HTTP requests
      https://docs.djangoproject.com/en/stable/topics/http/

      - URL dispatcher
        https://docs.djangoproject.com/en/stable/topics/http/urls/

      - Writing views
        https://docs.djangoproject.com/en/stable/topics/http/views/

      - View decorators
        https://docs.djangoproject.com/en/stable/topics/http/decorators/

      - File Uploads
        https://docs.djangoproject.com/en/stable/topics/http/file-uploads/

      - Django shortcut functions
        https://docs.djangoproject.com/en/stable/topics/http/shortcuts/

      - Middleware
        https://docs.djangoproject.com/en/stable/topics/http/middleware/

      - How to use sessions
        https://docs.djangoproject.com/en/stable/topics/http/sessions/

    * User authentication in Django
      https://docs.djangoproject.com/en/stable/topics/auth/

      - Using the Django authentication system
        https://docs.djangoproject.com/en/stable/topics/auth/default/

      - Customizing authentication in Django
        https://docs.djangoproject.com/en/stable/topics/auth/customizing/

      - Password Management in Django
        https://docs.djangoproject.com/en/2.0/topics/auth/passwords/

    * Signals
      https://docs.djangoproject.com/en/stable/topics/signals/

    * The contenttypes framework
      https://docs.djangoproject.com/en/stable/ref/contrib/contenttypes/

    * Security in Django
      https://docs.djangoproject.com/en/2.0/topics/security/

  - "How-to" guides

    * Managing static files (e.g. images, JavaScript, CSS)
      https://docs.djangoproject.com/en/stable/howto/static-files/

    * Outputting CSV with Django
      https://docs.djangoproject.com/en/stable/howto/outputting-csv/

    * Writing custom model fields
      https://docs.djangoproject.com/en/stable/howto/custom-model-fields/

    * Authentication using ``REMOTE_USER``
      https://docs.djangoproject.com/en/2.0/howto/auth-remote-user/

  - API reference
    https://docs.djangoproject.com/en/stable/ref/

    * Models
      https://docs.djangoproject.com/en/stable/ref/models/

      - Model Meta options
        https://docs.djangoproject.com/en/stable/ref/models/options/

      - Conditional Expressions
        https://docs.djangoproject.com/en/stable/ref/models/conditional-expressions/

      - Model index reference
        https://docs.djangoproject.com/en/2.0/ref/models/indexes/

    * Validators
      https://docs.djangoproject.com/en/2.0/ref/validators/

    * Templates
      https://docs.djangoproject.com/en/stable/ref/templates/

      - The Django Template Language
        https://docs.djangoproject.com/en/stable/ref/templates/language/

      - Built-in template tags and filters
        https://docs.djangoproject.com/en/stable/ref/templates/builtins/

      - The Django template language: for Python programmers
        https://docs.djangoproject.com/en/stable/ref/templates/api/

    * contrib packages
      https://docs.djangoproject.com/en/stable/ref/contrib/

      - The Django admin site
        https://docs.djangoproject.com/en/stable/ref/contrib/admin/

        * Admin actions
          https://docs.djangoproject.com/en/stable/ref/contrib/admin/actions/

      - The messages framework
        https://docs.djangoproject.com/en/stable/ref/contrib/messages/

      - authentication
        https://docs.djangoproject.com/en/2.0/ref/contrib/auth/

    * Request and response objects
      https://docs.djangoproject.com/en/stable/ref/request-response/

    * Cross Site Request Forgery protection
      https://docs.djangoproject.com/en/2.0/ref/csrf/

  - Django's release schedule
    https://www.djangoproject.com/download/
    https://www.djangoproject.com/weblog/2015/jun/25/roadmap/

  - Django packages
    https://djangopackages.org/

* django-nested-admin
  http://django-nested-admin.readthedocs.io/en/latest/

* django-widget-tweaks

* django-redis

* django-session-security

* django-debug-toolbar

* djangorestframework

* django-guardian

* django-jsonfield

* django-auth-ldap (with source)
  https://bitbucket.org/psagers/django-auth-ldap

  - Documentation
    https://django-auth-ldap.readthedocs.io/en/latest/index.html

    * installation
      https://django-auth-ldap.readthedocs.io/en/latest/install.html

    * authentication
      https://django-auth-ldap.readthedocs.io/en/latest/authentication.html

    * user objects
      https://django-auth-ldap.readthedocs.io/en/latest/users.html

* Grappelli

* Tornado

* Twisted

ssh
~~~

* paramiko

RPC
~~~

- XML-RPC

  .. (ok, why not REST?)

  * xmlrpc
  * xmlrpc.client (xmlrpclib)
  * xmlrpc.server (SimpleXMLRPCServer)

template
--------
- jinja2

  * Template Designer Documentation
    http://jinja.pocoo.org/docs/2.9/templates/

email
-----
- email
- smtplib
- smtpd
- poplib
- imaplib
- mimetypes

SMB
---
- pysmb

SNMP
----
- pysnmp

asn1
----
- pyasn1

ldap
----
- python-ldap

scientific computing
--------------------
- math

- cmath

- decimal

- statistics

- SciPy

- NumPy

- Sympy

- Matplotlib

- pandas

- pint

- IPython

  * ipyparallel

- Dask

- Joblib

- Jupyter

  kernels.

  * ipykernel

  widgets.

  * ipyleaflet

  * bqplot

  * pythreejs

  * ipyvolume

  * nglview

  * BeakerX

- traits

- traitlets

machine-learning
----------------
- scikit-learn

c extension
-----------
- SWIG
- ctypes
- Cython
- cffi

graphics and image processing
-----------------------------
- turtle
- imghdr
- stepic
- pillow
- scikit-image

GUI, animation, game
--------------------
- wxPython
- PyQt

- matplotlib
- processing.py
- blender (python scripting)

- kivy
- pygame

sound
-----
- sndhdr

py2py3
------
- six
- future
- lib2to3

codingstyle
-----------
- flake8
- yapf

message queue
-------------
- beanstalkc

- pynsq

- pyzmq

task queue
----------
- celery

  * repo readme
    https://github.com/celery/celery

  * Getting Started
    http://docs.celeryproject.org/en/latest/getting-started/index.html

    - Introduction to Celery
      http://docs.celeryproject.org/en/latest/getting-started/introduction.html

    - Brokers
      http://docs.celeryproject.org/en/latest/getting-started/brokers/index.html

      * Using RabbitMQ
        http://docs.celeryproject.org/en/latest/getting-started/brokers/rabbitmq.html

    - First Steps with Celery
      http://docs.celeryproject.org/en/latest/getting-started/first-steps-with-celery.html

    - Next Steps
      http://docs.celeryproject.org/en/latest/getting-started/next-steps.html

logging and warning
-------------------
- logging (with source)
  * logging
  * logging.config
  * logging.handlers
  * Logging HOWTO
    https://docs.python.org/3/howto/logging.html#advanced-logging-tutorial
  * Logging Cookbook
    https://docs.python.org/3/howto/logging-cookbook.html#adding-contextual-information-to-your-logging-output
- warnings

malware analysis
----------------
- yara

random number
-------------
- random
- secrets

vcs
---
.. git

- gitpython (with source)
  * tutorial
    http://gitpython.readthedocs.io/en/stable/tutorial.html

- gittle

file format manipulation
------------------------
pdf
~~~

- pypdf2

microsoft excel
~~~~~~~~~~~~~~~

- xlwt

HDF
~~~
-h5py

- PyTables


iOS
---
- stash

misc
----
- jsbeautifier
- uuid
- webbrowser

dev tools
=========

shell/REPL
----------
- IPython

debugging
---------
- python debugging tools
  https://wiki.python.org/moin/PythonDebuggingTools

- pdb

code checking
-------------
- pylint
- flake8
- yapf

profiling
---------
- The Python Profilers
  https://docs.python.org/2/library/profile.html

python version
--------------
- pyenv

virtual environment
-------------------
- venv

packaging and distribution
--------------------------
- Python Packaging User Guide

  * Additional Topics

    - install_requires vs Requirements files
      https://packaging.python.org/requirements/

- docutils
  * docutils front-end tools
    http://docutils.sourceforge.net/docs/user/tools.html

- setuptools

- easy_install

- pip
  * pip documentation: quickstart
    https://pip.pypa.io/en/stable/quickstart/
  * pip documentation: installation
    https://pip.pypa.io/en/stable/installing/
  * pip documentation: user guide
    https://pip.pypa.io/en/stable/user_guide/

- egg
  * The Quick Guide to Python Eggs
    http://peak.telecommunity.com/DevCenter/PythonEggs
- wheel
  * wheel documentation
    https://wheel.readthedocs.io/en/latest/

history
=======
- Centrum Wiskunde & Informatica (CWI)
  https://en.wikipedia.org/wiki/Centrum_Wiskunde_%26_Informatica
