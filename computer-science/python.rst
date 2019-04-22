language
========
- tutorials 
  
  * tutorial section of Python official documentation (已读)

  * Python's Class Development Toolkit
    https://www.youtube.com/watch?v=HTLu2DFOdTg&list=WL&index=20&t=1s

  * Beyond PEP 8, best practices for beautiful intelligible code
    https://www.youtube.com/watch?v=wf-BqAjZb8M

- Beginning Python From Novice to Professional (已读)

- Python Language Reference 2.7.10 --- Python official documentation (已读)

- Python Standard Library

  * Built-in Exceptions
    https://docs.python.org/3/library/exceptions.html

- C3 method resolution order
  https://www.python.org/download/releases/2.3/mro/

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
    https://www.python.org/dev/peps/pep-0008/

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

  * PEP 3107 -- Function Annotations

  * PEP 249  -- Python Database API Specification v2.0
    https://www.python.org/dev/peps/pep-0249/

- Unifying types and classes in Python 2.2
  https://www.python.org/download/releases/2.2.3/descrintro/

- Format String Syntax --- Python Library Reference

- Builtin exception hierarchy
  https://docs.python.org/3.4/library/exceptions.html#exception-hierarchy

- Unicode HowTo
  https://docs.python.org/2/howto/unicode.html#python-2-x-s-unicode-support

- Descriptor HowTo
  https://docs.python.org/3.6/howto/descriptor.html

- Buffer protocol

  * Less copies in Python with the buffer protocol and memoryviews
    http://eli.thegreenplace.net/2011/11/28/less-copies-in-python-with-the-buffer-protocol-and-memoryviews

- FAQs

  * Why is Python a dynamic language and also a strongly typed language?
    https://wiki.python.org/moin/Why%20is%20Python%20a%20dynamic%20language%20and%20also%20a%20strongly%20typed%20language


libraries and frameworks
========================
concurrency
-----------
- thread (_thread in py3)
- threading
- multiprocessing
- asyncio
- uvloop
- concurrent.futures
- gevent

command execution
-----------------
- subprocess (with source)
  * Creating pipelines with subprocess
    http://www.enricozini.org/blog/2009/debian/python-pipes/
  * Python SIGPIPE handling
    http://www.chiark.greenend.org.uk/~cjwatson/blog/python-sigpipe.html
- subprocess32
- pyinvoke
- fabric

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
  * homepage
    https://github.com/chardet/chardet

  * doc
    https://chardet.readthedocs.io/en/latest/index.html

    - FAQs
      https://chardet.readthedocs.io/en/latest/faq.html

    - Supported encodings
      https://chardet.readthedocs.io/en/latest/supported-encodings.html


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

cmdline animation
-----------------
- curses
- halo
- asciimatics

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
  https://docs.python.org/3/library/tempfile.html

- fileinput

- shutil

debugging and profiling
-----------------------
- pdb

- ipdb
  https://github.com/gotcha/ipdb

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
- tblib
- py_compile
- compileall
- copy
- inspect
- weakref
- site
- runpy
- keyword
- types (with source)
  https://docs.python.org/3/library/types.html
- gc
- contextlib
- pprint
- reprlib

import
^^^^^^

- importlib
- imp
- zipimport
- pkgutil

packaging
^^^^^^^^^

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
  https://docs.python.org/3/library/operator.html

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
  https://docs.python.org/3/library/atexit.html
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
  https://docs.python.org/3/library/time.html
- datetime
  https://docs.python.org/3/library/datetime.html
- calendar
  https://docs.python.org/3/library/calendar.html#module-calendar
- dateutil
  https://dateutil.readthedocs.io/en/stable/

coverage & test
---------------
- trace
- coverage
- unittest (with source)
  https://docs.python.org/3/library/unittest.html

- unittest.mock (with source)

  * getting started
    https://docs.python.org/3/library/unittest.mock-examples.html

  * doc
    https://docs.python.org/3/library/unittest.mock.html

- factory_boy (with source)
  https://factoryboy.readthedocs.io/en/latest/index.html

  - introduction
    https://factoryboy.readthedocs.io/en/latest/introduction.html

  - Reference
    https://factoryboy.readthedocs.io/en/latest/reference.html

  - Using factory_boy with ORMs
    http://factoryboy.readthedocs.io/en/latest/orms.html

  - Common recipes
    https://factoryboy.readthedocs.io/en/latest/recipes.html

  - Examples
    http://factoryboy.readthedocs.io/en/latest/examples.html

- doctest
- pytest

- Faker (with source)
  https://faker.readthedocs.io/en/latest/

  * providers

    - file
      http://faker.readthedocs.io/en/master/providers/faker.providers.file.html

    - phone_number
      https://faker.readthedocs.io/en/latest/providers/faker.providers.phone_number.html

    - company
      https://faker.readthedocs.io/en/master/providers/faker.providers.company.html

    - lorem
      https://faker.readthedocs.io/en/master/providers/faker.providers.lorem.html

    - python
      https://faker.readthedocs.io/en/master/providers/faker.providers.python.html

    - misc
      https://faker.readthedocs.io/en/master/providers/faker.providers.misc.html

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
- cryptography
- pynacl

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
^^^^^

.. mongodb

- pymongo (mongodb)
- bson (mongodb)
- bson.codec_options

.. elasticsearch

- elasticsearch
- elasticsearch_dsl

SQL
^^^

- sqlalchemy

.. sqlite

- sqlite3

.. postgresql

- psycopg2
- asyncpg

.. mysql

- MySQLdb
- mysqlclient

  * MySQLdb User’s Guide
    https://mysqlclient.readthedocs.io/user_guide.html

  * MySQLdb package
    https://mysqlclient.readthedocs.io/MySQLdb.html

  * constant package
    https://mysqlclient.readthedocs.io/MySQLdb.constants.html

- PyMySQL
- mysql.connector
- mycli

network programming
-------------------

lower-level stuffs
^^^^^^^^^^^^^^^^^^

- socket
- netifaces
- dpkt
- ipaddress
- pyroute2
- scapy

.. server

- socketserver
- select
- selectors
- shadowsocks

http and related protocols
^^^^^^^^^^^^^^^^^^^^^^^^^^

* WSGI

  * wiki
    https://en.wikipedia.org/wiki/Web_Server_Gateway_Interface

  * PEP 3333 -- Python Web Server Gateway Interface v1.0.1
    https://www.python.org/dev/peps/pep-3333/

* http

.. client

* http.client (httplib)
* urllib (urllib, urlib2)
* urllib.request
* urllib.parse (urlparse)
  https://docs.python.org/3/library/urllib.parse.html#urllib.parse.urlencode
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

* cherrypy

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

      - Performing raw SQL queries
        https://docs.djangoproject.com/en/2.0/topics/db/sql/

      - Database transactions
        https://docs.djangoproject.com/en/stable/topics/db/transactions/

      - Multiple databases
        https://docs.djangoproject.com/en/2.0/topics/db/multi-db/

      - Tablespaces
        https://docs.djangoproject.com/en/2.0/topics/db/tablespaces/

    * Migrations
      https://docs.djangoproject.com/en/2.1/topics/migrations/

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

    * Managing files
      https://docs.djangoproject.com/en/2.0/topics/files/

    * Signals
      https://docs.djangoproject.com/en/stable/topics/signals/

    * Security in Django
      https://docs.djangoproject.com/en/2.0/topics/security/

    * Logging
      https://docs.djangoproject.com/en/2.0/topics/logging/

    * Testing in Django
      https://docs.djangoproject.com/en/2.0/topics/testing/

      - Writing and running tests
        https://docs.djangoproject.com/en/2.1/topics/testing/overview/

      - Testing tools
        https://docs.djangoproject.com/en/2.1/topics/testing/tools/

      - Advanced testing topics
        https://docs.djangoproject.com/en/2.1/topics/testing/advanced/

    * System check framework
      https://docs.djangoproject.com/en/2.1/topics/checks/

    * Sending email
      https://docs.djangoproject.com/en/2.2/topics/email/

  - "How-to" guides

    * Managing static files (e.g. images, JavaScript, CSS)
      https://docs.djangoproject.com/en/stable/howto/static-files/

      - Deploying static files
        https://docs.djangoproject.com/en/2.0/howto/static-files/deployment/

    * Outputting CSV with Django
      https://docs.djangoproject.com/en/stable/howto/outputting-csv/

    * Writing custom model fields
      https://docs.djangoproject.com/en/stable/howto/custom-model-fields/

    * Authentication using ``REMOTE_USER``
      https://docs.djangoproject.com/en/2.0/howto/auth-remote-user/

    * Writing custom django-admin commands
      https://docs.djangoproject.com/en/2.0/howto/custom-management-commands/

    * Writing database migrations
      https://docs.djangoproject.com/en/2.0/howto/writing-migrations/

    * Writing a custom storage system
      https://docs.djangoproject.com/en/2.0/howto/custom-file-storage/

  - API reference
    https://docs.djangoproject.com/en/stable/ref/

    * Application
      https://docs.djangoproject.com/en/2.1/ref/applications/

    * Databases
      https://docs.djangoproject.com/en/2.0/ref/databases/

    * SchemaEditor
      https://docs.djangoproject.com/en/2.1/ref/schema-editor/

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

    * File handling
      https://docs.djangoproject.com/en/2.0/ref/files/

      - The File object
        https://docs.djangoproject.com/en/2.0/ref/files/file/

      - File storage API
        https://docs.djangoproject.com/en/2.0/ref/files/storage/

      - Uploaded Files and Upload Handlers
        https://docs.djangoproject.com/en/2.0/ref/files/uploads/

    * Built-in class-based views API

      - Multiple object mixins
        https://docs.djangoproject.com/en/2.0/ref/class-based-views/mixins-multiple-object/

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

      - The staticfiles app
        https://docs.djangoproject.com/en/2.0/ref/contrib/staticfiles/

    * Request and response objects
      https://docs.djangoproject.com/en/stable/ref/request-response/

    * Cross Site Request Forgery protection
      https://docs.djangoproject.com/en/2.0/ref/csrf/

    * Clickjacking Protection
      https://docs.djangoproject.com/en/2.0/ref/clickjacking/

    * System check framework
      https://docs.djangoproject.com/en/2.1/ref/checks/

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

* django-mysql

  - Requirements and Installation
    https://django-mysql.readthedocs.io/en/latest/installation.html

  - Model Fields
    https://django-mysql.readthedocs.io/en/latest/model_fields/index.html

    * EnumField
      https://django-mysql.readthedocs.io/en/latest/model_fields/enum_field.html

    * JSONField
      https://django-mysql.readthedocs.io/en/latest/model_fields/json_field.html

    * BIT(1) boolean fields
      https://django-mysql.readthedocs.io/en/latest/model_fields/null_bit1_boolean_fields.html

* django-environ (with source)

  - readme
    https://github.com/joke2k/django-environ/tree/master

  - doc
    http://django-environ.readthedocs.io/en/latest/

* django-stubs
  https://github.com/mkurnikov/django-stubs

* django-mongodb-engine

* django-localflavor

* Tornado

* Twisted

SSH
^^^
- paramiko

- fabric

RPC
^^^

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

- fractions

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

- PyEphem

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

- python-future

  * Overview: Easy, clean, reliable Python 2/3 compatibility
    http://python-future.org/overview.html

  * Quick-start guide
    http://python-future.org/quickstart.html

  * Cheat Sheet: Writing Python 2-3 compatible code
    http://python-future.org/compatible_idioms.html

  * imports
    http://python-future.org/imports.html

  * What else you need to know
    http://python-future.org/what_else.html

  * Automatic conversion to Py2/3
    http://python-future.org/automatic_conversion.html#known-limitations

- lib2to3

code quality
------------
- flake8
  https://github.com/PyCQA/flake8

  * quickstart
    http://flake8.pycqa.org/en/latest/

  * FAQs
    http://flake8.pycqa.org/en/latest/faq.html

  * Glossary of terms used in flake8 documentation
    http://flake8.pycqa.org/en/latest/glossary.html

  * Using Flake8
    http://flake8.pycqa.org/en/latest/user/index.html

    - Invoking Flake8
      http://flake8.pycqa.org/en/latest/user/invocation.html

    - Configuring Flake8
      http://flake8.pycqa.org/en/latest/user/configuration.html

    - Full Listing of Options and Their Descriptions
      http://flake8.pycqa.org/en/latest/user/options.html

    - Error/Violation codes
      http://flake8.pycqa.org/en/latest/user/error-codes.html

    - Selecting and Ignoring Violations
      http://flake8.pycqa.org/en/latest/user/violations.html

    - Using Version Control Hooks
      http://flake8.pycqa.org/en/latest/user/using-hooks.html

- yapf
  https://github.com/google/yapf

- vulture
  https://github.com/jendrikseipp/vulture

- pylint

message queue
-------------
- beanstalkc

- pynsq

- pyzmq

task queue
----------
- celery (with source)

  * Celery: an overview of the architecture and how it works
    https://www.vinta.com.br/blog/2017/celery-overview-archtecture-and-how-it-works/

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

  * user guide

    - Tasks
      http://docs.celeryproject.org/en/latest/userguide/tasks.html

    - Periodic Tasks
      http://docs.celeryproject.org/en/latest/userguide/periodic-tasks.html

    - Routing Tasks
      http://docs.celeryproject.org/en/latest/userguide/routing.html

    - Canvas: Designing Work-flows
      http://docs.celeryproject.org/en/latest/userguide/canvas.html

  * Django
    http://docs.celeryproject.org/en/latest/django/index.html

    - First steps with Django
      http://docs.celeryproject.org/en/latest/django/first-steps-with-django.html

  * API Reference

    - celery.contrib.abortable
      http://docs.celeryproject.org/en/latest/reference/celery.contrib.abortable.html

- django-celery-beat (with source)
  https://github.com/celery/django-celery-beat

- django-celery-results (useless)

logging and warning
-------------------
- logging (with source)

  * logging
    https://docs.python.org/3/library/logging.html

  * logging.config
    https://docs.python.org/3/library/logging.config.html

  * logging.handlers

  * Logging HOWTO
    https://docs.python.org/3/howto/logging.html

  * Logging Cookbook
    https://docs.python.org/3/howto/logging-cookbook.html

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

file format
-----------
format library
^^^^^^^^^^^^^^^
- python-magic
  https://github.com/ahupp/python-magic
- mimetypes

pdf
^^^

- pypdf2

microsoft excel
^^^^^^^^^^^^^^^

- xlwt

HDF
^^^
-h5py

- PyTables


iOS
---
- stash

static typing
-------------
- typing
  https://docs.python.org/3/library/typing.html

  * PEP 483 -- The Theory of Type Hints
    https://www.python.org/dev/peps/pep-0483/

  * PEP 484 -- Type hints
    https://www.python.org/dev/peps/pep-0484/

  * PEP 526 -- Syntax for Variable Annotations
    https://www.python.org/dev/peps/pep-0526/

  * PEP 563 -- Postponed Evaluation of Annotations
    https://www.python.org/dev/peps/pep-0563/

- typeshed
  https://github.com/python/typeshed/

- mypy

  * home
  http://www.mypy-lang.org/

  * readme
    https://github.com/python/mypy

  * examples
    http://www.mypy-lang.org/examples.html

  * about
    http://www.mypy-lang.org/about.html

  * roadmap
    https://github.com/python/mypy/blob/master/ROADMAP.md

  * documentation
    https://mypy.readthedocs.io/en/stable/

    - Introduction
      https://mypy.readthedocs.io/en/stable/introduction.html

    - Getting started
      https://mypy.readthedocs.io/en/stable/getting_started.html

    - Using mypy with an existing codebase
      https://mypy.readthedocs.io/en/stable/existing_code.html

    - Running mypy and managing imports
      https://mypy.readthedocs.io/en/stable/running_mypy.html

    - The mypy command line
      https://mypy.readthedocs.io/en/stable/command_line.html

    - The mypy configuration file
      https://mypy.readthedocs.io/en/stable/config_file.html

    - Mypy daemon
      https://mypy.readthedocs.io/en/stable/mypy_daemon.html

    - Using intalled packages
      https://mypy.readthedocs.io/en/stable/installed_packages.html

    - Extending and integrating mypy
      https://mypy.readthedocs.io/en/stable/extending_mypy.html

    - Common issues and solutions
      https://mypy.readthedocs.io/en/stable/common_issues.html#

    - Supported python features
      https://mypy.readthedocs.io/en/stable/supported_python_features.html

    - Unsupported python features
      https://github.com/python/mypy/wiki/Unsupported-Python-Features

    - FAQs
      https://mypy.readthedocs.io/en/stable/faq.html

    - Built-in types
      https://mypy.readthedocs.io/en/stable/builtin_types.html

    - Type inference and type annotations
      https://mypy.readthedocs.io/en/stable/type_inference_and_annotations.html

    - Kinds of types
      https://mypy.readthedocs.io/en/stable/kinds_of_types.html

    - Class basics
      https://mypy.readthedocs.io/en/stable/class_basics.html

    - Protocols and structural subtyping
      https://mypy.readthedocs.io/en/stable/protocols.html

    - Dynamically typed code
      https://mypy.readthedocs.io/en/stable/dynamic_typing.html

    - Casts and type assertions
      https://mypy.readthedocs.io/en/stable/casts.html

    - Duck type compatibility
      https://mypy.readthedocs.io/en/stable/duck_type_compatibility.html

    - Stub files
      https://mypy.readthedocs.io/en/stable/stubs.html

    - Generics
      https://mypy.readthedocs.io/en/stable/generics.html

    - More types
      https://mypy.readthedocs.io/en/stable/more_types.html

    - Final names, methods and classes
      https://mypy.readthedocs.io/en/stable/final_attrs.html

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


profiling
---------
- The Python Profilers
  https://docs.python.org/2/library/profile.html

python version
--------------
- pyenv

  * repository
    https://github.com/pyenv/pyenv

  * FAQ
    https://github.com/pyenv/pyenv/wiki

  * Common build problems
    https://github.com/pyenv/pyenv/wiki/Common-build-problems

  * Deploying with pyenv
    https://github.com/pyenv/pyenv/wiki/Deploying-with-pyenv

  * Plugins
    https://github.com/pyenv/pyenv/wiki/Plugins

  * Understanding binstubs
    https://github.com/pyenv/pyenv/wiki/Understanding-binstubs

  * Unix shell initialization
    https://github.com/pyenv/pyenv/wiki/Unix-shell-initialization

  * Command Reference
    https://github.com/pyenv/pyenv/blob/master/COMMANDS.md

  * plugin: python-build
    https://github.com/pyenv/pyenv/tree/master/plugins/python-build

  * plugin: pyenv-virtualenv
    https://github.com/pyenv/pyenv-virtualenv

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
