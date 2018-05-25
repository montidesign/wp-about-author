# wp-about-author
Fork of the WP About Author plugin by John Bishop

The original is available at https://wordpress.org/plugins/wp-about-author/.

The problem with the original is that it prepends "http://socialdomain.com/" to the social user profile meta data entered in the WP user profile. This works fine for the Twitter handle; unfortunately, for social profile URLs like Facebook, it causes the href attribute for the corresponding social icon in the bio box to be rendered "http://socialdomain.com/https://facebook.com/user.name," which of course will not resolve properly.

This fork rectifies that issue.

Other than that problem, this plugin appears to perform reliably. Given the paucity of actual working author bio plugins in the WP plugin repository, this is a useful item to have in one's WP toolbelt.
