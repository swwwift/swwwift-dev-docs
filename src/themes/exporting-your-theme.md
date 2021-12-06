# Exporting Your Theme

When you have built your page templates, template parts, completed your page designs and built your pages out with the blocks you can now package up your theme.

## Exporting Content

First thing to do after completing your theme is to use the WPCLI to export your theme content which will contain all the above with the exception to styling.

Simply run `wp export` and the .xml file will be placed in the directory the CLI command is run from.

Copy this export file into `/wp-content/uploads/swft_{theme_name}_swwwift/content/import.xml`.

Now in your theme folder, `/wp-content/uploads/swft_{theme_name}_swwwift` do a `git init`. Create a new repo in github with the following naming convention `swft_{theme_name}_swwwift` and push your theme up.

Congrats! You're all done!