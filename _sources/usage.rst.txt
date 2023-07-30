Getting Started & Usage
=====

Editing this wiki is possible for any users part of the Iron-Panthers organization.

The pages are written in reStructureText and compiled by Sphinx into GitHub Pages static text. The compilation is done by a GitHub action upon any change to the ``main`` branch - by Pull Request merge, direct web edit, or by a git push. More info on the text format can be found here:

* `Sphinx reStructuredText Primer<https://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html>`
* `Sphinx reStructuredText Directive<https://www.sphinx-doc.org/en/master/usage/restructuredtext/directives.html>` (aka images, tables, etc)


How to use a Pull Request to Add Images
---------------------------------------

Adding new-to-the-wiki images is not as straightforward as it could be. However, it is possible to use the github web-editor and Pull Requests to preview changes including image uploads. This technique can also be used to edit multiple files or add a whole page tree at once.

..  note::
    Image names cannot include spaces. A directive with a image path including spaces will remove them when looking for the file.
    For example, ``Screenshot 2023-07-04 at 08.05.42 PM.png`` will make an html page looking for the image at ``Screenshot2023-07-04at08.05.42PM.png``.

1. Start editing the page or create a new page using the "Edit" button.
2. To add an image to the page, use the ``.. image::`` directive with the desired options.
   The first line must include a path to the image; relative paths are allowed.
   It is recommended to also include at least the ``:height:`` and ``:alt:`` attributes.
3. Click "Commit changes..."
4. Change the radio button to "Create a new branch..." and then click "Propose changes."
5. On the next page, make the Pull Request (PR). The title will be used as the overall commit name.
6. Navigate to editing this branch by clicking on the branch name at the top of the page.
7. Navigate to the folder where the images should go and drag-and-drop them onto the page.
8. When done editing, check the "Preview" on the pages that have been edited and merge the PR when satisfied.

Where to find the results
-------------------------

Write me ...
