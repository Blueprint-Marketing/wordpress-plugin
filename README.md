# awe.sm for WordPress

This is the Git repository for the awe.sm WordPress plugin.

The WordPress Plugin Directory uses SVN. Work in the Git repository. Release to the public via WordPress.org's SVN suppository <http://plugins.svn.wordpress.org/awesm/>. Use the WordPress.org/bbPress.org username and password.

How to release
==============

1. Place the new files in both /trunk/ and /tags/x.x/ (where x.x is the version number of the release). Make sure the version number of the "tag" matches the version number in /trunk/readme.txt

2. Commit and push.

> svn ci --username snowballfactory -m "Hello, world. 0.6 release."


References
----------
FAQ about the WordPress Plugins Directory
http://wordpress.org/extend/plugins/about/faq/

Using Subversion with the WordPress Plugins Directory
http://wordpress.org/extend/plugins/about/svn/

WordPress Plugins Directory readme.txt standard
http://wordpress.org/extend/plugins/about/readme.txt

readme.txt validator:
http://wordpress.org/extend/plugins/about/validator/