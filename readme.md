# Members - Role Levels

Members - Role Levels is an add-on plugin for the [Members plugin](http://themehybrid.com/plugins/members) that provides access to the old user levels system.

The plugin fixes a longstanding bug in which users don't appear in the author drop-down on the edit post screen.

## The author drop-down issue

In WordPress 2.1, user levels were deprecated and replaced with the newer roles and caps system.  Roles and caps make for a far superior system for managing user permissions.  However, parts of core WordPress still require the use of user levels to function correctly.  One item in particular is the author drop-down on the edit posts screen.

The author drop-down requires that the `user_level` be set for a user in order for that user to appear in the drop-down, even if that user has the `edit_posts` capability (or whatever capability is required for your post type).  So, when you create custom roles without one of the available levels, new users won't get the appropriate user level nor will they appear in the author drop-down.

It's a mess that should've been cleaned up in core WP ages ago.  This plugin corrects this mess behind the scenes and provides a nice UI on the Edit Role screen for managing levels on a per-role basis.

If none of this makes sense to you, just know that it will correct the issue if you have users who are not correctly appearing in the author drop-down.

## Professional Support

If you need professional plugin support from me, the plugin author, you can access the support forums at [Theme Hybrid](http://themehybrid.com/board/topics), which is a professional WordPress help/support site where I handle support for all my plugins and themes for a community of 60,000+ users (and growing).

## Copyright and License

This project is licensed under the [GNU GPL](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html), version 2 or later.

2015 &copy; [Justin Tadlock](http://justintadlock.com).