# Editing Page Templates

Page templates are traditionally developed with PHP in WordPress. This is now no longer the case with full site editing. You can now edit everything about the block templates using the Gutenberg editor and that is now each themes templates are to be developed.

## Template Editor
Go to `Appearance > Editor` to find the template editor.

In here, you'll see a sstandard template to get you started though these are very basic implementations.

You should at the very top, see the header, a group below that and then finishing with a footer.

In the group (below header, above footer), you can start to add blocks to develop your layout for the specified template. 

By default, all blocks are 100% width. Any content should ideally start with a "columns" block to give width and margin between columns.

When you save a template you have been editing, you'll notice it wants to "overwrite" the specified template. This is fine to go ahead and do that. From there, you'll see in `Appearance > Templates` that your newly edited template is now available as an editable post type. This will be exported in your content export later on and can be added to your theme folder in the uploads directory in:

```
- swft_{theme_name}_swwwift
-- content
--- import.xml // Where this file is your content export
```

Simply add all your default (single, archive, category, etc) layouts in this editor.

## Template Parts

The header and footer are known as template parts can can be edited separately. If you choose to edit one of these areas, what you do in the area you are editing becomes used on all pages that area is used. You can remove one or both from a template but generally it's not advised.

When you do make a change to a template part, you'll see in `Appearance > Template Parts` that your newly defined template part is available to edit as a custom post.

This will once again be exported in your content export later on and can be added to your theme folder in the uploads directory as defined above.