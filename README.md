# A Python Log

A Full Stack, Mobile-friendly web app with Python running the show! A full stack app with RWD, forms using HTTP, auth, validation, admin vs user access, and more. A fast, beautiful, readable, accessible, and friendly site for anybody that wants to contribute to a blog aiming to provide users with a go-to resource for learning code.

<img src="https://raw.githubusercontent.com/mathcodes/PythonLog/main/mockupspythonLog.png?token=GHSAT0AAAAAABQS7SFHW27JTGMA7KKAHDW6YPGMM6A" width="60%" />

## [LIVE](https://jonspythonlog.herokuapp.com/)

# Installation
In development I ended up using both `VS Code` and `PyCharm` for certain features not shared by both. With that said, I find that running the app is easiest using PyCharm by following these simple steps:

 1) Start new project in `PyCharm`.
 2) Clone the repo in PyCharm using the following command:
```bash
git clone git@github.com:mathcodes/PythonLog.git
```
 3) Install the dependencies (In `main.py`, whichever remaining dependencies are not automatically installed will have a red alert flag that when you hover over, offers you an option to install the necessary dependencies/components.
 4) Run `main.py`

- ### Requirements
  - [gunicorn](#gunicorn)
  - [django](#django)
  - [certifi](#certifi)
  - [chardet](#chardet)
  - [click](#click)
  - [ckeditor](#ckeditor)
  - [dominate](#dominate)
  - [Flask](#flask)
  - [Flask-Bootstrap](#bootstrap)
  - [Flask-CKEditor](#ckeditor)
  - [Flask-Gravatar](#gravatar)
  - [Flask-Login](#login)
  - [Flask-SQLAlchemy](#sqlalchemy)
  - [Flask-WTF](#wtf)
  - [idna](#idna)
  - [itsdangerous](#itsdangerous)
  - [Jinja2](#jinja2)
  - [MarkupSafe](#markupsafe)
  - [requests](#requests)
  - [SQLAlchemy](#sqlalchemy)
  - [urllib3](#urllib3)
  - [visitor](#visitor)
  - [Werkzeug](#werkzeug)
  - [WTForms](#wtforms)

## [Green Unicorn (Gunicorn)]('https://www.fullstackpython.com/green-unicorn-gunicorn.html')

The Gunicorn "Green Unicorn" is a Python Web Server Gateway Interface HTTP server. It is a pre-fork worker model, ported from Ruby's Unicorn project. The Gunicorn server is broadly compatible with a number of web frameworks, simply implemented, light on server resources and fairly fast.

## [Django](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Introduction)

Django is a Python-based web framework, free and open-source, that follows the model–template–views architectural pattern. It is maintained by the Django Software Foundation, an independent organization established in the US as a 501 non-profit.

## [certifi](https://pypi.org/project/certifi/)
Certifi provides Mozilla’s carefully curated collection of Root Certificates for validating the trustworthiness of SSL certificates while verifying the identity of TLS hosts. It has been extracted from the Requests project.

## [chardet](https://chardet.readthedocs.io/en/latest/usage.html#basic-usage)
Character encoding auto-detection in Python. As smart as your browser. Open source.

## [click](https://click.palletsprojects.com/en/8.1.x/) 
Click is a Python package for creating beautiful command line interfaces in a composable way with as little code as necessary. It’s the “Command Line Interface Creation Kit”. It’s highly configurable but comes with sensible defaults out of the box.

## [ckeditor](https://ckeditor.com/)
CKEditor 5 provides every type of WYSIWYG editing solution imaginable. From editors similar to Google Docs and Medium, to Slack or Twitter like applications, all is possible within a single editing framework.

## [dominate](https://anaconda.org/conda-forge/dominate)
Dominate is a Python library for creating and manipulating HTML documents using an elegant DOM API.

## [Flask](https://flask.palletsprojects.com/en/2.1.x/)
Flask is a micro web framework written in Python. It is classified as a microframework because it does not require particular tools or libraries. It has no database abstraction layer, form validation, or any other components where pre-existing third-party libraries provide common functions. 

## [Flask-Bootstrap](https://pypi.org/project/Flask-Bootstrap4/)
Flask-Bootstrap packages Bootstrap into an extension that mostly consists of a blueprint named ‘bootstrap’. It can also create links to serve Bootstrap from a CDN and works with no boilerplate code in your application.


## [Flask-CKEditor](https://pypi.org/project/Flask-CKEditor/)
CKEditor integration for Flask, including image upload, code syntax highlighting, and more.

Features include: 
 - Integrate with Flask-WTF/WTForms.
 - Configure CKEditor through Flask's configuration system.
 - Image upload support.
 - Code snippet highlighting.
 - Built-in CKEditor resources.

## [Flask-Gravatar](https://pypi.org/project/Flask-Gravatar/)
This is small and simple integration gravatar into flask.

## [Flask-Login](https://pypi.org/project/Flask-Login/)
Flask-Login provides user session management for Flask. It handles the common tasks of logging in, logging out, and remembering your users' sessions over extended periods of time.

Flask-Login is not bound to any particular database system or permissions model. The only requirement is that your user objects implement a few methods, and that you provide a callback to the extension capable of loading users from their ID.


## [Flask-SQLAlchemy](https://pypi.org/project/Flask-SQLAlchemy/)
Flask-SQLAlchemy is an extension for Flask that adds support for SQLAlchemy to your application. It aims to simplify using SQLAlchemy with Flask by providing useful defaults and extra helpers that make it easier to accomplish common tasks.


## [Flask-WTF](https://pypi.org/project/Flask-WTF/)
Simple integration of Flask and WTForms, including CSRF, file upload, and reCAPTCHA.

## [idna](https://pypi.org/project/idna/)
Support for the Internationalised Domain Names in Applications (IDNA) protocol as specified in RFC 5891. This is the latest version of the protocol and is sometimes referred to as “IDNA 2008”.

This library also provides support for Unicode Technical Standard 46, Unicode IDNA Compatibility Processing.

This acts as a suitable replacement for the “encodings.idna” module that comes with the Python standard library, but which only supports the older superseded IDNA specification (RFC 3490).

## [itsdangerous](https://pypi.org/project/itsdangerous/)
Various helpers to pass data to untrusted environments and to get it back safe and sound. Data is cryptographically signed to ensure that a token has not been tampered with.

It’s possible to customize how data is serialized. Data is compressed as needed. A timestamp can be added and verified automatically while loading a token.


## [Jinja2](https://pypi.org/project/Jinja2/)
Jinja is a fast, expressive, extensible templating engine. Special placeholders in the template allow writing code similar to Python syntax. Then the template is passed data to render the final document.

Features include: 
 - Template inheritance and inclusion.
 - Define and import macros within templates.
 - HTML templates can use autoescaping to prevent XSS from untrusted user input.
 - A sandboxed environment can safely render untrusted templates.
 - AsyncIO support for generating templates and calling async functions.
 - I18N support with Babel.
 - Templates are compiled to optimized Python code just-in-time and cached, or can be compiled ahead-of-time.
 - Exceptions point to the correct line in templates to make debugging easier.
 - Extensible filters, tests, functions, and even syntax.

Jinja’s philosophy is that while application logic belongs in Python if possible, it shouldn’t make the template designer’s job difficult by restricting functionality too much.

## [MarkupSafe](https://pypi.org/project/MarkupSafe/)
MarkupSafe implements a text object that escapes characters so it is safe to use in HTML and XML. Characters that have special meanings are replaced so that they display as the actual characters. This mitigates injection attacks, meaning untrusted user input can safely be displayed on a page.

## [requests](https://pypi.org/project/requests/)
Requests is a simple, yet elegant, HTTP library.

Requests allows you to send HTTP/1.1 requests extremely easily. There’s no need to manually add query strings to your URLs, or to form-encode your PUT & POST data — but nowadays, just use the json method!

Requests is one of the most downloaded Python packages today, pulling in around 30M downloads / week— according to GitHub, Requests is currently depended upon by 1,000,000+ repositories. You may certainly put your trust in this code.


## [SQLAlchemy](https://pypi.org/project/SQLAlchemy/)
SQLAlchemy is the Python SQL toolkit and Object Relational Mapper that gives application developers the full power and flexibility of SQL. SQLAlchemy provides a full suite of well known enterprise-level persistence patterns, designed for efficient and high-performing database access, adapted into a simple and Pythonic domain language.

Major SQLAlchemy features include:

- An industrial strength ORM, built from the core on the identity map, unit of work, and data mapper patterns. These patterns allow transparent persistence of objects using a declarative configuration system. Domain models can be constructed and manipulated naturally, and changes are synchronized with the current transaction automatically.
- A relationally-oriented query system, exposing the full range of SQL’s capabilities explicitly, including joins, subqueries, correlation, and most everything else, in terms of the object model. Writing queries with the ORM uses the same techniques of relational composition you use when writing SQL. While you can drop into literal SQL at any time, it’s virtually never needed.
- A comprehensive and flexible system of eager loading for related collections and objects. Collections are cached within a session, and can be loaded on individual access, all at once using joins, or by query per collection across the full result set.
- A Core SQL construction system and DBAPI interaction layer. The SQLAlchemy Core is separate from the ORM and is a full database abstraction layer in its own right, and includes an extensible Python-based SQL expression language, schema metadata, connection pooling, type coercion, and custom types.
- All primary and foreign key constraints are assumed to be composite and natural. Surrogate integer primary keys are of course still the norm, but SQLAlchemy never assumes or hardcodes to this model.
- Database introspection and generation. Database schemas can be “reflected” in one step into Python structures representing database metadata; those same structures can then generate CREATE statements right back out - all within the Core, independent of the ORM.
SQLAlchemy’s philosophy:

- SQL databases behave less and less like object collections the more size and performance start to matter; object collections behave less and less like tables and rows the more abstraction starts to matter. SQLAlchemy aims to accommodate both of these principles.
- An ORM doesn’t need to hide the “R”. A relational database provides rich, set-based functionality that should be fully exposed. SQLAlchemy’s ORM provides an open-ended set of patterns that allow a developer to construct a custom mediation layer between a domain model and a relational schema, turning the so-called “object relational impedance” issue into a distant memory.
- The developer, in all cases, makes all decisions regarding the design, structure, and naming conventions of both the object model as well as the relational schema. SQLAlchemy only provides the means to automate the execution of these decisions.
- With SQLAlchemy, there’s no such thing as “the ORM generated a bad query” - you retain full control over the structure of queries, including how joins are organized, how subqueries and correlation is used, what columns are requested. Everything SQLAlchemy does is ultimately the result of a developer- initiated decision.
- Don’t use an ORM if the problem doesn’t need one. SQLAlchemy consists of a Core and separate ORM component. The Core offers a full SQL expression language that allows Pythonic construction of SQL constructs that render directly to SQL strings for a target database, returning result sets that are essentially enhanced DBAPI cursors.
- Transactions should be the norm. With SQLAlchemy’s ORM, nothing goes to permanent storage until commit() is called. SQLAlchemy encourages applications to create a consistent means of delineating the start and end of a series of operations.
- Never render a literal value in a SQL statement. Bound parameters are used to the greatest degree possible, allowing query optimizers to cache query plans effectively and making SQL injection attacks a non-issue.

## [urllib3](https://pypi.org/project/urllib3/)
urllib3 is a powerful, user-friendly HTTP client for Python. Much of the Python ecosystem already uses urllib3 and you should too. urllib3 brings many critical features that are missing from the Python standard libraries:

- Thread safety.
- Connection pooling.
- Client-side SSL/TLS verification.
- File uploads with multipart encoding.
- Helpers for retrying requests and dealing with HTTP redirects.
- Support for gzip, deflate, and brotli encoding.
- Proxy support for HTTP and SOCKS.
- 100% test coverage.

## [visitor](https://pypi.org/project/visitor/)
A tiny library to facilitate visitor implementation in Python (which are slightly peculiar due to dynamic typing). In fact, it is so small, you may just be better off copy & pasting the source straight into your project…


## [Werkzeug](https://werkzeug.palletsprojects.com/en/2.1.x/)
<p><em>werkzeug</em> German noun: “tool”.
Etymology: <em>werk</em> (“work”), <em>zeug</em> (“stuff”)</p>
<p>Werkzeug is a comprehensive <em><a class="reference external" href="https://wsgi.readthedocs.io/en/latest/">WSGI</a></em> web application library. It began as
a simple collection of various utilities for WSGI applications and has
become one of the most advanced WSGI utility libraries.</p>
<p>Werkzeug doesn’t enforce any dependencies. It is up to the developer to
choose a template engine, database adapter, and even how to handle
requests.</p>
 

<em><a class="reference external" href="https://wsgi.readthedocs.io/en/latest/">WSGI</a></em> is the Web Server Gateway Interface. It is a specification that describes how a web server communicates with web applications, and how web applications can be chained together to process one request.

## [WTForms](https://wtforms.readthedocs.io/en/3.0.x/)
WTForms is a flexible forms validation and rendering library for Python web development. It can work with whatever web framework and template engine you choose. It supports data validation, CSRF protection, internationalization (I18N), and more. There are various community libraries that provide closer integration with popular frameworks.

# Contact
<img src="https://avatars0.githubusercontent.com/u/17928947?v=4" alt="Github profile image" width="80px" height="80px" />

__Jon Christie__ 

GitHub: [mathcodes](https://github.com/mathcodes) 

[<code><img width="36px" src="https://img.icons8.com/color/48/000000/linkedin.png"/></code>](https://www.linkedin.com/jonchristie)       [<code><img width="36" src="https://img.icons8.com/color/48/000000/twitter--v2.png"/></code>](https://twitter.com/jonpchristie)       [<code><img width="36" src="https://img.icons8.com/color/48/000000/youtube-play.png"/></code>](https://www.youtube.com/channel/UC5GFnN-lv8Yuqc9O3b79k6g)       [<code><img width="36" src="https://img.icons8.com/color/48/000000/facebook.png"/></code>](https://www.facebook.com/jonpchristie)       [<code><img width="36" src="https://img.icons8.com/color/48/000000/instagram-new--v2.png"/></code>](https://www.instagram.com/fullstack11235)       [<code><img width="36" src="https://img.icons8.com/color/48/000000/soundcloud.png"/></code>](https://soundcloud.com/jonchristie#/)       [<code><img width="36" src="https://img.icons8.com/color/48/000000/spotify--v1.png"/></code>](https://open.spotify.com/artist/07S7aLfxH70VAX64g1WuFw?si=tlOj1OMBRLm-y4sY8Lox3Q)
