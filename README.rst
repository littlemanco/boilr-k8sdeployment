====================
k8sdeployment
====================

Project Outline
----------------

Project Goals
'''''''''''''

Make it trivial to create a Kubernetes deployment, following the littleman.co standards

Similar Work
''''''''''''

None


Justification
'''''''''''''

It's hard generating consistant configuration over time. Let's make it easy


Summary
'''''''

============= ==============
License       Language
------------- --------------
MIT           en-AU [lang]_
============= ==============

Installation
-------------

.. Code:: bash

  $ boilr template download boilr-k8sdeployment

Usage
-----

Swap `foo` and `bar` for your own values.

.. Code:: bash

  $ mkdir foo
  $ cd foo
  $ git init
  $ git remote set-url origin git@github.com:foo/bar.git
  $ boilr template use k8sdeployment
  $ git add .
  $ git commit -m "Initial Commit"
  $ git push

Thanks
------

- The team behind boilr (https://github.com/tmrts/boilr)

Contributing
------------

Contributions are always welcome! Nothing is to small, and the best place to start is to open an issue.

References
-----------

.. [lang] Lingoes.net,. (2015). Language Code Table. Retrieved 4 June 2015, from http://www.lingoes.net/en/translator/langcode.htm
