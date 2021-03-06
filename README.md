zonkylla
========

[![Build Status](https://travis-ci.org/zonkylla/zonkylla.svg?branch=master)](https://travis-ci.org/zonkylla/zonkylla) [![Code Climate](https://codeclimate.com/github/zonkylla/zonkylla/badges/gpa.svg)](https://codeclimate.com/github/zonkylla/zonkylla)

Tool for zonky.cz

Preparation
-----------

-   [Fedora 26](doc/prepare_f26.md)

After installation configure your local git repository:

    # setup commit template
    git config commit.template .git-commit-template

Usage
-----

-   Run

    ``` bash
    virtualenv-3.6 venv
    source venv/bin/activate
    python setup.py install

    zonkylla

    deactivate
    ```

-   Testing run with mock

    ``` bash
    echo 'test' | python -m zonkylla -t test
    ```

Resources
---------

-   <http://docs.zonky.apiary.io>
-   <http://pre-commit.com>
-   <http://docs.python-requests.org/en/master/>
-   <https://requests-mock.readthedocs.io/en/latest/>
-   <http://requests-oauthlib.readthedocs.io/en/latest/index.html>
-   <https://sqlite.org/lang.html>
