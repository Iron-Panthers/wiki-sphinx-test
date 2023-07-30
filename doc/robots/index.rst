An Index Page with some images
==============================

..  toctree::
    :glob:
    *
    */*

Here's a picture of 5026's 2019 comp bot:

..  image:: Screen Shot 2022-11-19 at 1.23.41 PM.png
    :height: 300

This was included with the image directive:
::
  ..  image:: Screen Shot 2022-11-19 at 1.23.41 PM.png
      :height: 300

And a picture of 5026's 2020 comp bot:

..  image:: Screen Shot 2022-11-19 at 1.20.08 PM.png
    :scale: 50
    :alt: a robot

This was included with the image directive:
::
    ..  image:: Screen Shot 2022-11-19 at 1.20.08 PM.png
        :scale: 50
        :alt: a robot

A header
--------

A sub-header
^^^^

A sub-sub-header
""""

Copying tables from readmes...

+-------+----------+------+
| Table Headings   | Here |
+-------+----------+------+
| Sub   | Headings | Too  |
+=======+==========+======+
| cell  | column spanning |
+ spans +----------+------+
| rows  | normal   | cell |
+-------+----------+------+
| multi | * cells can be  |
| line  | * formatted     |
| cells | * paragraphs    |
| too   |                 |
+-------+-----------------+

===== ========= =====
Table Headings  Here
--------------- -----
Sub   Headings  Too
===== ========= =====
column spanning no
--------------- -----
cell  cell      row
column spanning spans
=============== =====

The most minimal table:

========== ===========
Tabel title
----------------------
Header 1   Header 2 
========== ===========
Data 1      lkad
Data 2
Data 3
Data 4
Data 5      asdf
========== ===========
