# Awesome Python [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![License](https://licensebuttons.net/l/by-nc/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc/4.0/) 

_[Creative Commons License Compatibility](https://github.com/Catacrockers/awesome-catacrockers/blob/master/CC_License_Compatibility_Chart_compact.png)_

A curated list of awesome Python frameworks, libraries, software and resources.

## 📝 Index

+ [Code Analysis](#code-analysis)
+ [Concurrency and Parallelism](#concurrency-and-parallelism)
+ [Configuration](#configuration)
+ [Command-line Tools](#command-line-tools)
+ [Compatibility](#compatibility)
+ [GUI](#gui)
+ [HTTP](#http)
+ [Logging](#logging)
+ [Programming Paradigms](#programming-paradigms)
  - [Event Driven Programming](#event-driven-programming)
  - [Reactive programming](#reactive-programming)
+ [RESTful API](#restful-api)
+ [Testing](#testing)
+ [Web Frameworks](#web-frameworks)
+ [WSGI Servers](#wsgi-servers)

## Concurrency and parallelism

*Libraries for concurrent and parallel execution.*

- [gevent](http://www.gevent.org/) - A coroutine-based Python networking library that uses [greenlet](https://github.com/python-greenlet/greenlet).

## Code Analysis

*Tools of static analysis, linters and code quality checkers.*

- [Pylint](https://www.pylint.org/) - A fully customizable source code analyzer. Pylint is a Python static code analysis tool which looks for programming errors, helps enforcing a coding standard, sniffs for code smells and offers simple refactoring suggestions.

## Configuration

- [Aumbry](https://aumbry.readthedocs.io/en/latest/) - general purpose library for handling configuration within your Python applications. The project was born from constantly needing a simple interface for configuration models that came from multiple data sources.

## Command-line Tools

*Libraries for building command-line application.*

+ Productivity Tools
  - [parallel_foreach_submodule (PFS)](https://github.com/RDCH106/parallel_foreach_submodule) - Tool for "git submodule foreach" execution in parallel.
  - [pipdeptree](https://github.com/naiquevin/pipdeptree) - A command line utility to display dependency tree of the installed Python packages.

## Compatibility

*Libraries for migrating from Python 2 to 3.*

* [Python-Future](http://python-future.org/index.html) - The missing compatibility layer between Python 2 and Python 3.
* [Python-Modernize](https://github.com/mitsuhiko/python-modernize) - Modernizes Python code for eventual Python 3 migration.
* [Six](https://pypi.python.org/pypi/six) - Python 2 and 3 compatibility utilities.

**⚠️ [Python 2.7 Countdown](https://pythonclock.org/)**

## GUI

*Libraries for working with graphical user interface applications.*

- [Gooey](https://github.com/chriskiehl/Gooey) - Turn command line programs into a full GUI application with one line.
- [remi](https://github.com/dddomodossola/remi) - Python REMote Interface library. Platform independent. In about 100 Kbytes, perfect for your diet.
- [Tkinter](https://wiki.python.org/moin/TkInter) - Tkinter is Python's de-facto standard GUI package.
- [Kivy](https://github.com/kivy/kivy) - Kivy is an open source, cross-platform Python framework for the development of applications that make use of innovative, multi-touch user interfaces. 

## HTTP

Libraries for working with HTTP.

- [requests](http://docs.python-requests.org/en/latest/) - HTTP Requests for Humans™.

## Logging

- [logging](https://docs.python.org/3/library/logging.html) - (Python standard library) Logging facility for Python.
- [structlog](https://github.com/hynek/structlog) - makes logging in Python less painful and more powerful by adding structure to your log entries.

## Programming Paradigms

## Event Driven Programming

*Event driven Programming with Python.*

+ [paho-mqtt](https://pypi.org/project/paho-mqtt/) - Client for mqtt protocol
+ [pytransitions](https://github.com/pytransitions/transitions) - A lightweight, object-oriented state machine implementation in Python.

### Reactive Programming

*Reactive Programming with Python.*

- [rxpy](https://github.com/ReactiveX/RxPY) - 
A library for composing asynchronous and event-based programs using observable collections and LINQ-style query operators in Python.

## RESTful API

*Libraries for developing RESTful APIs.*

+ Flask
  - [flask-restful](https://github.com/flask-restful/flask-restful) - Quickly building REST APIs for Flask.
  - [linkero](https://github.com/ingran/linkero) - Restful API for external requests with access control

+ Framework agnostic
  - [falcon](http://falconframework.org/) - A high-performance framework for building cloud APIs and web app backends.
  - [hug](https://github.com/timothycrosley/hug) - A Python3 framework for cleanly exposing APIs over HTTP and the Command Line with automatic documentation and validation.

## Testing

*Libraries for testing codebases and generating test data.*

+ Testing Frameworks
  - [Pytest](https://docs.pytest.org/en/latest/) - A mature full-featured Python testing tool. The pytest framework makes it easy to write small tests, yet scales to support complex functional testing for applications and libraries.
+ GUI / Web Testing
  - [PyAutoGUI](https://github.com/asweigart/pyautogui) - PyAutoGUI is a cross-platform GUI automation Python module for human beings.

## Web Frameworks

*Full stack web frameworks.*

- [Flask](http://flask.pocoo.org/) - A microframework for Python.

## WSGI Servers

- [gunicorn](https://gunicorn.org/) - Gunicorn 'Green Unicorn' is a Python WSGI HTTP Server for UNIX. It's a pre-fork worker model. The Gunicorn server is broadly compatible with various web frameworks, simply implemented, light on server resources, and fairly speedy.
- [waitress](https://github.com/Pylons/waitress) - Waitress is meant to be a production-quality pure-Python WSGI server with very acceptable performance. It has no dependencies except ones which live in the Python standard library.

