# Theme Block Patterns

Themes can have their own block patterns. These will live in `/wp-content/uploads/swft_{theme_name}_swwwift/block-patterns/{category}`.

To create a block pattern, in the editor create a "group" and place your blocks inside the group. When finished, click the group and click the option "make block reusable". In the page options, click "manage reusable blocks". On the overview, find your reusable block and click "export JSON". Rename and paste this file into the directory above. Note `{category}` as a folder name will place your reusable blocks into that category name on the block editor.

You can also create post type specific block patterns that will automatically fill new posts with the defined pattern. To do this:

In the theme folder `/swwwift_themes/{your_theme}/block-patterns/page-templates`, place your block pattern and rename it to the slug of the post type you want to autofill. For example, `page.json` or `post.json`.
