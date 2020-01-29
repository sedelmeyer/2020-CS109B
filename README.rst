Harvard SEAS CS109B: Advanced Topics In Data Science
====================================================

This is a forked version of the course repository for the 2020 Spring offering of the Harvard SEAS course CS109B: Advanced Topics In Data Science.

.. contents::
   :local:
   :backlinks: top

Course website
--------------

https://harvard-iacs.github.io/2020-CS109B/

Cloning this repo and managing upstream merges
----------------------------------------------

1. Clone this forked repo locally::

       git clone https://github.com/sedelmeyer/2020-CS109B.git cs109b-repo-2020spring

2. Enter the locally cloned repository and add the original course repo as an upstream remote::

       git remote add upstream https://github.com/Harvard-IACS/2020-CS109B.git

3. Confirm that both the ``origin`` and ``upstream`` remotes exist::

       git remote -v

Pushing changes to the forked repo
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1. Use ``git add ...`` and ``git commit -m ...`` as you would normally to commit changes locally.

2. Use ``git push origin ...`` as you typically would to push to your ``origin`` remote forked version of the repo.

Getting updates from the ``upstream`` branch
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1. To merge in newly published content from the original ``upstream`` course repo::

       git fetch upstream
       git merge upstream/master

2. This will merge upstream changes into your local master. Merge conflicts will need to be managed locally. To prevent painful ``.ipynb`` merge collisions, make local copies of Jupyter notebooks for running code locally.

