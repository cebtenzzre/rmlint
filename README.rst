.. image:: https://raw.githubusercontent.com/sahib/rmlint/develop/docs/_static/logo.png
   :align: center

`rmlint` finds space waste and other broken things on your filesystem and offers
to remove it. 

**Features:**

Finds…

- …Duplicate Files and duplicate directories.
- …Nonstripped binaries (i.e. binaries with debug symbols)
- …Broken symbolic links.
- …Empty files and directories.
- …Files with broken user or/and group ID.

**Differences to other duplicate finders:**

- Extremely fast (no exaggeration, we promise!)
- Paranoia mode for those who do not trust hashsums.
- Many output formats.
- No interactivity.
- Search for files only newer than a certain ``mtime``.
- Many ways to handle duplicates.
- Caching and replaying.
- ``btrfs`` support.
- ...

It runs and compiles under most Unices, including Linux, FreeBSD and Darwin.
The main target is Linux though, some optimisations might not be available
elsewhere.

.. image:: https://raw.githubusercontent.com/sahib/rmlint/develop/docs/_static/screenshot.png
   :align: center

AUTHORS
-------

Here's a list of developers to blame:

===================================  ============================= =========
*Christopher Pahl*                   https://github.com/sahib      2010-2017
*Daniel Thomas*                      https://github.com/SeeSpotRun 2014-2017
*Jared Van Bortel*                   https://github.com/cebtenzzre 2021-2025
===================================  ============================= =========

There are some other people that helped us of course.
Please see the AUTHORS distributed along `rmlint`.

LICENSE
-------

`rmlint` is licensed under the conditions of the
`GPLv3 <https://www.gnu.org/licenses/quick-guide-gplv3.html.en>`_.
See the
`COPYING <https://raw.githubusercontent.com/sahib/rmlint/master/COPYING>`_ 
file distributed along the source for details.
