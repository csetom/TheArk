---
tags: example
---
{{||H1}}
This [[Tiddler|tiddler]] uses [[Transclusion|transclusion]] to include an SVG image tiddler and shows how to use it as an image map. Here is a brief summary of the SVG creation/import process (based on a post from the [[https___groups.google.com_forum_#!forum_tiddlywiki|TiddlyWiki Google Group]] by Derivation Bud):

In Inkscape:

- Create your image
- Select a group or a shape, right-click/create link
-- Set **Href:** to ``#MyTargetTiddler``
-- Set **Target:** to ``_parent``
-- Set **Title:** to ``Some text`` (optional mouse over text)
- From the File menu select **Save As** and choose **Plain SVG** format

In TW5:

- **Import** the SVG file as a tiddler (found on the **Tools** sidebar)
-- SVG image type will be inferred from the file extension
- Edit the new tiddler:
-- Change the tiddler's type to **text/vnd.tiddlywiki**
-- Remove ``<?xml ...?>`` prolog
-- Remove the ``<metadata> ... </metadata>`` sub tree (not strictly necessary)
- Do not insert blank lines.

Here is a sample image imported using this process: [[plain_svg_test.svg]]

And here it is in action:

{{plain_svg_test.svg}}

Minor gotcha with using this technique: If you click on one of the linked objects and close the tiddler the object opens, clicking on it again does not reopen the tiddler.