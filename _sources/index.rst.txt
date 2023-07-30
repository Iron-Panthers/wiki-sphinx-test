.. this is a comment, it is not rendered
   The toctree blocks below build the navigation for the left hand side of the wiki when it is rendered.
   They can be hidden or show in the page, and the order they appear will be reflected.
   When adding new *.rst files, reference them here or in one of the sub-index files that is already listed.

.. toctree::
   :hidden:
   :maxdepth: 2
   :caption: 🤖 Robot Archive
   :glob:

   robots/*


Welcome
====

2023 Charged Up Docs
----

`2023 FRC Useful Links <https://www.team5026.com/index.php?title=2023_FRC_Useful_Links>`
`Kickoff Tasks <https://www.team5026.com/index.php?title=Kickoff_Tasks>`

Quick Links
----

🚀 :doc:`usage`

🤖 :doc:`Robot Archive <robots/>`

How-To Guides
^^^^

How to Design a Robust FRC Robot

How to Get Onshape

How to Get And Use Onshape Feature Scripts

How to Wire a Robust FRC Robot


Sub-Team Sections
----

.. toctree::
   :hidden:
   :maxdepth: 1
   :caption: 💼 Business
   :glob:

   business/*

.. toctree::
   :hidden:
   :maxdepth: 1
   :caption: ⚡️ Electrical
   :glob:

   electrical/*

.. toctree::
   :hidden:
   :maxdepth: 1
   :caption: 🦾 Mechanical
   :glob:

   mechanical/*

.. toctree::
   :hidden:
   :maxdepth: 1
   :caption: 💻 Programming
   :glob:

   programming/*


.. Catch-all for other pages.

.. toctree::
   :hidden:
   :maxdepth: 2
   :glob:

   purpose.rst
   dependencies.rst
   usage.rst
   credit.rst
   exercises.rst
   *
