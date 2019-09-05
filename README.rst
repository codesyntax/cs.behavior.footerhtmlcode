.. This README is meant for consumption by humans and pypi. Pypi can render rst files so please do not use Sphinx features.
   If you want to learn more about writing documentation, please check out: http://docs.plone.org/about/documentation_styleguide.html
   This text does not appear on pypi or github. It is a comment.

==========================
cs.behavior.footerhtmlcode
==========================

.. image:: https://travis-ci.com/codesyntax/cs.behavior.footerhtmlcode.svg?branch=master
    :target: https://travis-ci.com/codesyntax/cs.behavior.footerhtmlcode

.. image:: https://coveralls.io/repos/github/codesyntax/cs.behavior.footerhtmlcode/badge.svg?branch=master
    :target: https://coveralls.io/github/codesyntax/cs.behavior.footerhtmlcode?branch=master


This addon adds a behavior to provide an extra field where you can write any HTML code.

This HTML code will be shown in the footer viewlet. The Footer viewlet will look for the nearest Language Root Folder (/en, /de, /es, ...) and will render the value of the field present there.

This behavior is useful for multilingual sites where you may want to put some language-dependant javascript code editable by the end user.

We are using this to provide the cookie message in several languages. We are using `Cookie Consent`_ to achieve this.

Installation
------------

Install cs.behavior.footerhtmlcode by adding it to your buildout::

    [buildout]

    ...

    eggs =
        cs.behavior.footerhtmlcode


and then running ``bin/buildout``

Use
---

Install the product in the Plone Control Panel -> Addons. The install process will enable the behavior automatically for Language Root Folders.


Contribute
----------

- Issue Tracker: https://github.com/collective/cs.behavior.footerhtmlcode/issues
- Source Code: https://github.com/collective/cs.behavior.footerhtmlcode
- Documentation: https://docs.plone.org/foo/bar


Support
-------

If you are having issues, please let us know.
We have a mailing list located at: project@example.com


License
-------

The project is licensed under the GPLv2.

.. _`Cookie Consent`: https://cookieconsent.osano.com/
