# Mozilla Web QA Examples

This repository contains examples of test automation from Mozilla's Web QA team.

[![Travis](https://img.shields.io/travis/mozilla/mozwebqa-examples.svg)](https://travis-ci.org/mozilla/mozwebqa-examples/)
[![Issues](https://img.shields.io/github/issues-raw/mozilla/mozwebqa-examples.svg)](https://github.com/mozilla/mozwebqa-examples/issues)
[![Requirements](https://img.shields.io/requires/github/mozilla/mozwebqa-examples.svg)](https://requires.io/github/mozilla/mozwebqa-examples/requirements/?branch=master)


You will need to be familiar
with Python, Selenium, and have a working knowledge of GitHub.

If you are comfortable with Python, it's worth having a look at the Selenium
framework to understand the basic concepts of browser-based testing and the 
page objects pattern.

If you need to brush up on programming but are eager to start contributing
immediately, please consider helping out by doing manual testing.  You can
help find bugs in Mozilla [Firefox][firefox] or find bugs in the Mozilla web
sites tested by the [Web QA][webqa] team.  We have many projects that would be
thrilled to have your help!

To brush up on Python skills before engaging with us, [Dive Into Python][dive]
is an excellent resource.  MIT also has [lecture notes on Python][mit] available
through their open courseware.  The programming concepts you will need to know
include functions, working with classes, and the basics of object-oriented 
programming.


How to setup and run Mozilla Web QA Examples tests locally
---------------------------------------------
This repository contains Selenium tests used to test:

* Link to project being tested

__note__

This is not necessary but is really helpful if you are working on multiple
Python projects that use different versions of modules.

Run

    easy_install pip

followed by

    sudo pip install -r requirements.txt

__note__

If you are running on Ubuntu/Debian you will need to do following first

    sudo apt-get install python-setuptools

to install the required Python libraries.

To run tests locally it is as simple as calling <code>py.test</code> with
several flags. To run testcases that do not modify or delete data:

[mit]: http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-189-a-gentle-introduction-to-programming-using-python-january-iap-2011/
[dive]: http://www.diveintopython.net/toc/index.html
[webqa]: http://quality.mozilla.org/teams/web-qa/
[firefox]: http://quality.mozilla.org/teams/desktop-firefox/
[webdriver]: http://seleniumhq.org/docs/03_webdriver.html
[mozwebqa]:http://02.chat.mibbit.com/?server=irc.mozilla.org&channel=#mozwebqa    
