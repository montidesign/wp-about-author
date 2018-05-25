# wp-about-author
Fork of the WP About Author plugin by John Bishop

The original is available at https://wordpress.org/plugins/wp-about-author/.

The problem with the original is that it prepends "http://socialdomain.com/" to the social user profile meta data entered in the WP user profile. This works fine for the Twitter handle, but for social profile URLs like Facebook, this causes the href attribute for the corresponding social icon to be rendered "http://socialdomain.com/https://facebook.com/user.name," which of course will not resolve properly.

This fork rectifies that issue.
