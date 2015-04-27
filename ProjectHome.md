This is a backport of the Python 3.2 subprocess module for use on Python versions 2.4 through 2.7 running on POSIX Platforms.  Bonus: It includes timeout support from Python 3.3.

It includes many important bug fixes including a C extension module used
internally to handle the code path between fork() and exec().  This improves
the reliability when an application is using threads.

**Downloads have moved to PyPI**: https://pypi.python.org/pypi/subprocess32/

Documentation can be found at https://docs.python.org/3.2/library/subprocess.html.

Tested using: Python 2.4, 2.5, 2.6 and 2.7.

Think you've found an issue?  Please try to reproduce it using Python 3.4 and file it using http://bugs.python.org/.  Work will be done upstream and backported to this project.