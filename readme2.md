# [gunicorn]('https://www.fullstackpython.com/green-unicorn-gunicorn.html')

Green Unicorn (Gunicorn)
Green Unicorn, commonly shortened to "Gunicorn", is a Web Server Gateway Interface (WSGI) server implementation that is commonly used to run Python web applications.

Official Green Unicorn (Gunicorn) logo.

Why is Gunicorn important?
Gunicorn is one of many WSGI server implementations, but it's particularly important because it is a stable, commonly-used part of web app deployments that's powered some of the largest Python-powered web applications in the world, such as Instagram.

Gunicorn implements the PEP3333 WSGI server standard specification so that it can run Python web applications that implement the application interface. For example, if you write a web application with a web framework such as Django, Flask or Bottle, then your application implements the WSGI specification....

# [django](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Introduction)

Django is written in Python, which runs on many platforms. That means that you are not tied to any particular server platform, and can run your applications on many flavours of Linux, Windows, and Mac OS X. Furthermore, Django is well-supported by many web hosting providers, who often provide specific infrastructure and documentation for hosting Django sites.==3.2.4

### What is Django?
Django is a high-level Python web framework that enables rapid development of secure and maintainable websites. Built by experienced developers, Django takes care of much of the hassle of web development, so you can focus on writing your app without needing to reinvent the wheel. It is free and open source, has a thriving and active community, great documentation, and many options for free and paid-for support.

Django helps you write software that is:

### Complete
Django follows the "Batteries included" philosophy and provides almost everything developers might want to do "out of the box". Because everything you need is part of the one "product", it all works seamlessly together, follows consistent design principles, and has extensive and up-to-date documentation.

### Versatile
Django can be (and has been) used to build almost any type of website — from content management systems and wikis, through to social networks and news sites. It can work with any client-side framework, and can deliver content in almost any format (including HTML, RSS feeds, JSON, XML, etc). The site you are currently reading is built with Django!

Internally, while it provides choices for almost any functionality you might want (e.g. several popular databases, templating engines, etc.), it can also be extended to use other components if needed.

### Secure
Django helps developers avoid many common security mistakes by providing a framework that has been engineered to "do the right things" to protect the website automatically. For example, Django provides a secure way to manage user accounts and passwords, avoiding common mistakes like putting session information in cookies where it is vulnerable (instead cookies just contain a key, and the actual data is stored in the database) or directly storing passwords rather than a password hash.

A password `hash` is a fixed-length value created by sending the password through a `cryptographic` hash function. Django can check if an entered password is correct by running it through the hash function and comparing the output to the stored hash value. However due to the "one-way" nature of the function, even if a stored hash value is compromised it is hard for an attacker to work out the original password.

Django enables protection against many vulnerabilities by default, including SQL injection, cross-site scripting, cross-site request forgery and clickjacking (see Website security for more details of such attacks).

### Scalable
Django uses a component-based “shared-nothing” architecture (each part of the architecture is independent of the others, and can hence be replaced or changed if needed). Having a clear separation between the different parts means that it can scale for increased traffic by adding hardware at any level: caching servers, database servers, or application servers. Some of the busiest sites have successfully scaled Django to meet their demands (e.g. Instagram and Disqus, to name just two).

### Maintainable
Django code is written using design principles and patterns that encourage the creation of maintainable and reusable code. In particular, it makes use of the Don't Repeat Yourself (DRY) principle so there is no unnecessary duplication, reducing the amount of code. Django also promotes the grouping of related functionality into reusable "applications" and, at a lower level, groups related code into modules (along the lines of the Model View Controller (MVC) pattern).

### Portable
Django is written in Python, which runs on many platforms. That means that you are not tied to any particular server platform, and can run your applications on many flavours of Linux, Windows, and Mac OS X. Furthermore, Django is well-supported by many web hosting providers, who often provide specific infrastructure and documentation for hosting Django sites.

[certifi](https://spectrum.ieee.org/media-library/purple-background-with-a-yellow-hand-shape-made-up-of-names-of-programming-languages-holds-the-word-python-which-is-large.jpg)

Dominate is a Python library for creating and manipulating HTML documents using an elegant DOM API.
dominate is a tool in the PyPI Packages category of a tech stack.
dominate is an open source tool with 1.3K GitHub stars and 77 GitHub forks. Here’s a link to dominate's open source repository on GitHub

#[click]()

Click is a Python package for creating beautiful command line interfaces in a composable way with as little code as necessary.
https://click.palletsprojects.com/en/8.0.x/_images/click-logo.png
https://click.palletsprojects.com/en/8.0.x/why/
Click is a Python package for creating beautiful command line interfaces in a composable way with as little code as necessary. It’s the “Command Line Interface Creation Kit”. It’s highly configurable but comes with sensible defaults out of the box.

It aims to make the process of writing command line tools quick and fun while also preventing any frustration caused by the inability to implement an intended CLI API.

Click in three points:
 - arbitrary nesting of commands

- automatic help page generation

- supports lazy loading of subcommands at runtime

What does it look like? Here is an example of a simple Click program:
```
import click
```

```
@click.command()
@click.option('--count', default=1, help='Number of greetings.')
@click.option('--name', prompt='Your name',
              help='The person to greet.')
def hello(count, name):
    """Simple program that greets NAME for a total of COUNT times."""
    for x in range(count):
        click.echo(f"Hello {name}!")
```

```
if __name__ == '__main__':
    hello()
```
    
And what it looks like when run:
```
$ python hello.py --count=3
Your name: John
Hello John!
Hello John!
Hello John!
```

It automatically generates nicely formatted help pages:
```
$ python hello.py --help
Usage: hello.py [OPTIONS]
```
  Simple program that greets NAME for a total of COUNT times.
```
Options:
  --count INTEGER  Number of greetings.
  --name TEXT      The person to greet.
  --help           Show this message and exit.
  ```
You can get the library directly from PyPI:



### Installation

`pip install click`

### Documentation
Click is a Python package for creating beautiful command line interfaces in a composable way with as little code as necessary. It’s the “Command Line Interface Creation Kit”. It’s highly configurable but comes with sensible defaults out of the box.
https://appdividend.com/wp-content/uploads/2020/06/Python-certifi-Example-How-to-Use-SSL-Certificate-in-Python.png
Frequently asked questions
What is character encoding?
When you think of “text”, you probably think of “characters and symbols I see on my computer screen”. But computers don’t deal in characters and symbols; they deal in bits and bytes. Every piece of text you’ve ever seen on a computer screen is actually stored in a particular character encoding. There are many different character encodings, some optimized for particular languages like Russian or Chinese or English, and others that can be used for multiple languages. Very roughly speaking, the character encoding provides a mapping between the stuff you see on your screen and the stuff your computer actually stores in memory and on disk.

In reality, it’s more complicated than that. Many characters are common to multiple encodings, but each encoding may use a different sequence of bytes to actually store those characters in memory or on disk. So you can think of the character encoding as a kind of decryption key for the text. Whenever someone gives you a sequence of bytes and claims it’s “text”, you need to know what character encoding they used so you can decode the bytes into characters and display them (or process them, or whatever).


# [chardet]('https://chardet.readthedocs.io/en/latest/faq.html')

What is character encoding auto-detection?
It means taking a sequence of bytes in an unknown character encoding, and attempting to determine the encoding so you can read the text. It’s like cracking a code when you don’t have the decryption key.

Isn’t that impossible?
In general, yes. However, some encodings are optimized for specific languages, and languages are not random. Some character sequences pop up all the time, while other sequences make no sense. A person fluent in English who opens a newspaper and finds “txzqJv 2!dasd0a QqdKjvz” will instantly recognize that that isn’t English (even though it is composed entirely of English letters). By studying lots of “typical” text, a computer algorithm can simulate this kind of fluency and make an educated guess about a text’s language.

In other words, encoding detection is really language detection, combined with knowledge of which languages tend to use which character encodings.

Who wrote this detection algorithm?
This library is a port of the auto-detection code in Mozilla. I have attempted to maintain as much of the original structure as possible (mostly for selfish reasons, to make it easier to maintain the port as the original code evolves). I have also retained the original authors’ comments, which are quite extensive and informative.

You may also be interested in the research paper which led to the Mozilla implementation, A composite approach to language/encoding detection.

Yippie! Screw the standards, I’ll just auto-detect everything!
Don’t do that. Virtually every format and protocol contains a method for specifying character encoding.

HTTP can define a charset parameter in the Content-type header.
HTML documents can define a <meta http-equiv="content-type"> element in the <head> of a web page.
XML documents can define an encoding attribute in the XML prolog.
If text comes with explicit character encoding information, you should use it. If the text has no explicit information, but the relevant standard defines a default encoding, you should use that. (This is harder than it sounds, because standards can overlap. If you fetch an XML document over HTTP, you need to support both standards and figure out which one wins if they give you conflicting information.)

Despite the complexity, it’s worthwhile to follow standards and respect explicit character encoding information. It will almost certainly be faster and more accurate than trying to auto-detect the encoding. It will also make the world a better place, since your program will interoperate with other programs that follow the same standards.

Why bother with auto-detection if it’s slow, inaccurate, and non-standard?
Sometimes you receive text with verifiably inaccurate encoding information. Or text without any encoding information, and the specified default encoding doesn’t work. There are also some poorly designed standards that have no way to specify encoding at all.

If following the relevant standards gets you nowhere, and you decide that processing the text is more important than maintaining interoperability, then you can try to auto-detect the character encoding as a last resort. An example is my Universal Feed Parser, which calls this auto-detection library only after exhausting all other options.

Installation

Install from PyPI:
``` 
pip install chardet
```

### Documentation
For users, docs are now available at `https://chardet.readthedocs.io/`.

### Command-line Tool
chardet comes with a command-line script which reports on the encodings of one or more files:
```
% chardetect somefile someotherfile
somefile: windows-1252 with confidence 0.5
someotherfile: ascii with confidence 1.0
```
### About
This is a continuation of Mark Pilgrim’s excellent chardet. Previously, two versions needed to be maintained: one that supported python 2.x and one that supported python 3.x. We’ve recently merged with Ian Cordasco’s charade fork, so now we have one coherent version that works for Python 2.7+ and 3.4+.
 
### Chardet: The Universal Character Encoding Detector
chardet
Python Certifi provides Mozilla’s thoroughly curated collection of Root Certificates for validating the trustworthiness of SSL certificates while verifying an identity of TLS hosts.
https://appdividend.com/2020/06/19/python-certifi-example-how-to-use-ssl-certificate-in-python/
Python Certifi provides Mozilla’s thoroughly curated collection of Root Certificates for validating the trustworthiness of SSL certificates while verifying an identity of TLS hosts. It has been plucked from the Requests project.

The Python Requests library uses its own CA file by default or will use the certifi package’s certificate bundle if installed.)

Python Certifi provides Mozilla’s thoroughly curated collection of Root Certificates for validating the trustworthiness of SSL certificates while verifying an identity of TLS hosts. It has been plucked from the Requests project.

The Python Requests library uses its own CA file by default or will use the certifi package’s certificate bundle if installed.

Install Python certifi
To install the python certifi package, you have to type the following command.



python3 -m pip install certifi

# OR

pip install certifi
If you have installed requests library already, then there are 100% chances that the certifi library is also installed, but you have to check it. So, if you hit the following command, then either it will tell us that the requirement is already satisfied or it will install on your machine.


PLAYUNMUTE
FULLSCREEN
VDO.AI
Skip Ad
While it’s possible to pass your own CA bundle to Requests to override the default CAs, several third-party packages use Requests under the hood, and there is no way you can tell them to use the custom location for verify.

Use certifi in your Python project
To reference the installed certificate authority (CA) bundle, you can use the built-in function:


import certifi

print(certifi.where())
Output
/Users/krunal/Library/Python/3.8/lib/python/site-packages/certifi/cacert.pem
You can also find the cacert.pem path from the command line using the following command.

 python -m certifi
/Users/krunal/Library/Python/3.8/lib/python/site-packages/certifi/cacert.pem
Browsers and certificate authorities have finalized that 1024-bit keys are unacceptably weak for certificates, particularly root certificates.

For the same reason, Mozilla has removed any weak (i.e., 1024-bit key) certificate from its bundle, replacing it with the equivalent robust (i.e., 2048-bit or higher key) certificate from the same CA.

Note: Certifi does not support any addition/removal or other modification of the CA trust store content. 
If you put the additional certificates in the PEM bundle file, you can use these two environment variables to overwrite the default cert stores used by Python OpenSSL and Requests.

SSL_CERT_FILE=/System/Library/OpenSSL/cert.pem
REQUESTS_CA_BUNDLE=/System/Library/OpenSSL/cert.pem
However, we can quickly check for this when our scripts start-up, and update the CA bundle automatically with a given CA if necessary.

First, capture your custom CA and save it as the PEM file.
