# Starting a New Theme

To begin creating a new theme, the following process should be observed.

Step 1: Create a WordPress install\
Step 2: Delete everything in wp-content\
Step 3: In your terminal, cd into the wp-content directory\
Step 4: Run `git clone --recurse-submodules git@github.com:swwwift/swwwift-starter-theme.git .`\
Step 5: Install the database provided in the wp-content folder\
Step 6: Run the following to create yourself a user: `wp user create bob bob@example.com --role=administrator`\
Step 7: Change the default URL by defining the following in `wp-config.php`:
```
define( 'WP_HOME', 'http://example.com' );
define( 'WP_SITEURL', 'http://example.com' );
```
Step 8: Login and enable **ALL** plugins
Step 9: In `Settings > Permalinks`, set to **Post name**

That's it, you're ready to go.

