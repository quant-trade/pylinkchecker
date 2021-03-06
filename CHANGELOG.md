0.2 (October 28th 2013)
=======================

- Added logging information (e.g., --verbose=2)
=======
- Added logging information (e.g., --verbose=2)
- Added support for html5lib parser (pure python html 5-ready parser)
- Improved README documentation with lots of examples
- Added runonce option (only check one page and exit)
- Clarified documentation (the default python parser is not good for production
use).
- Only follow http URL schemes (e.g., do not try to access ftp or mailto
links).

0.1 (July 8th 2013)
===================

This is the first release of pylinkchecker, a pure python crawler that reports
errors encountered while traversing a website.

pylinkchecker works with Python 2.6, 2.7, and 3.3 and its performance can be
boosted by installing lxml, cchardet and gevent.

Some features:

- Can use a, img, style, and script tags to crawl a web site.
- Can download resources outside the main domain.
- Can ignore certain path prefixes or allow other domains.
- Can send a username and password for basic HTTP authentication.
- Print a report in the console, and optionally in a file, or in an email.
- Possible to specify the type of worker (thread, process, green thread) and
their number.

Installing pylinkchecker is as simple as running "pip install pylinkchecker"
