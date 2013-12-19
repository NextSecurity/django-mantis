============
Contributing
============

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given. 

You can contribute in many ways:

Types of Contributions
----------------------

Report Bugs
~~~~~~~~~~~

Report bugs at:

* https://github.com/siemens/django-dingos/issues for issues concerning the ``django-dingos`` component
* https://github.com/siemens/django-mantis-core/issues for issues concerning the ``django-mantis-core`` component
* https://github.com/siemens/django-mantis-openioc-importer/issues for issues concerning the ``django-mantis-openioc-importer`` component
* https://github.com/siemens/django-mantis-stix-importer/issues for issues concerning the ``django-mantis-stix-importer`` component
* https://github.com/siemens/django-mantis-iodef-importer/issues for issues concerning the ``django-mantis-iodef-importer`` component
* https://github.com/siemens/django-mantis/issues for issues concerning MANTIS as a whole or issues for which you are not
  able to locate a specific component

If you are reporting a bug, please include:

* Your operating system name and version.
* Any details about your local setup that might be helpful in troubleshooting.
* Detailed steps to reproduce the bug.

Fix Bugs
~~~~~~~~

Look through the GitHub issues for bugs. Anything tagged with "bug"
is open to whoever wants to implement it.

Implement Features
~~~~~~~~~~~~~~~~~~

Look through the GitHub issues for features. Anything tagged with "feature"
is open to whoever wants to implement it.

Write Documentation
~~~~~~~~~~~~~~~~~~~

Djangos could always use more documentation, whether as part of the 
official Djangos docs, in docstrings, or even on the web in blog posts,
articles, and such.

Submit Feedback
~~~~~~~~~~~~~~~

The best way to send feedback is to file an issue at https://github.com/bgro/django-dingos/issues.

If you are proposing a feature:

* Explain in detail how it would work.
* Keep the scope as narrow as possible, to make it easier to implement.
* Remember that this is a volunteer-driven project, and that contributions
  are welcome :)

Get Started!
------------

Ready to contribute? Here's how to set up a repository for local development.

1. Fork the relevant repository repo on GitHub.
2. Clone your fork locally::

    $ git clone git@github.com:your_name_here/<repository>.git

3. Install your local copy into a virtualenv. Assuming you have virtualenvwrapper installed, this is how you set up your fork for local development::

    $ mkvirtualenv <your_mantis_environment>
    $ cd <repository_folder>
    $ python setup.py develop

4. Create a branch for local development::

    $ git checkout -b name-of-your-bugfix-or-feature

Now you can make your changes locally.

5. Commit your changes and push your branch to GitHub::

    $ git add .
    $ git commit -m "Your detailed description of your changes."
    $ git push origin name-of-your-bugfix-or-feature

6. Submit a pull request through the GitHub website.

Pull Request Guidelines
-----------------------

Before you submit a pull request, check that it meets these guidelines:

1. The pull request should include tests.
2. If the pull request adds functionality, the docs should be updated. Put
   your new functionality into a function with a docstring, and add the
   feature to the list in README.rst.
3. The pull request should work for Python 2.7.