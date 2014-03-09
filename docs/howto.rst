How to add your experiences to this repo
========================================

Goal
----

You should follow these instructions if you want to add a new file
to this project.

There are two ways to do it: the easy way (via the GitHub web
editor), and the hard way (via your terminal on your personal
computer). This file only documents the easy way, but you can
either infer the hard way yourself, or ask for help.


Steps (via GitHub web editor)
-----------------------------

* Surf to https://github.com/beckastar/hackbright-django/

* Click on **docs** to open the docs/ folder

* Click on the **+** icon (next to the word **docs**) to create a new file. This may require you to sign in to your GitHub account.

* You will see a blank editable field, and a prompt to **Name your file...**.

 * I suggest **yourgithubname.rst** (replace "yourgithubname" with your actual GitHub username)

* In the text area, type something like the folowing::

    My name
    =======

    Things that worked well
    -----------------------


    * Donuts


    Things that I had questions about
    ---------------------------------


    * Why is the documentation thing named after a
      mythical creature? Is the idea that docs are a myth?

* If you like, explain your proposed change with a short summary below the text area.

* Click **Propose new file**, and GitHub will create your pull request!

* When Becka merges it, it will eventually show up on http://hackbright-django-docs.rtfd.org.


Things to know about how this works
-----------------------------------

* Remember, the purpose of your document is to provide useful feedback to the Django documentation team. Therefore, share anything that seems relevant. Things to consider writing about: parts of the tutorial you liked, parts that were unclear, how long each section took you, what your background is, and so on.

* index.rst has a "glob" parameter, so any files are automatically included.

* The choice of ``====`` and ``----`` doesn't actually matter, but you have to be consistent. See http://sphinx-doc.org/rest.html#sections for more information.

* readthedocs.org and GitHub can be configured to talk to each other over Web Hooks.
