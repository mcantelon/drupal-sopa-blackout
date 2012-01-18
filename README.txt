Blackout your Drupal site on January 18, 2012 as part of the global
anti-SOPA/PIPA protest! Politicians have reportedly backed down on
SOPA, but PIPA still remains so best to proceed with the blackout.

This module automates this via a quick hack.

Your site will look like:

  http://mikecantelon.com/?sopa_test=1

Your site will work normally until January 18, but on January 18 you
will only be able to access URLs starting with "user" and "admin"
without seeing the SOPA blackout page. After January 18 your site will
be back to normal.

Developed for/tested with Drupal 6 or Drupal 7.

Edit sopa.info and change to your preferred core version or:
* D6: checkout 6.x-1.x
* D7: checkout 7.x-1.x

If you're new to GitHub here are some quick instructions:

1. Go to https://github.com/mcantelon/drupal-sopa-blackout/zipball/master
2. Unzip the resulting file and you should get a folder
3. Rename this folder to sopa
4. In the folder, edit the "sopa.info" file changing the Drupal version to
   match your version (6 or 7)
5. Put the folder in your sites/all/modules directory
6. Enable the module through the Drupal web administration interface

Inspired by WP-SOPA-Blackout:

  https://github.com/chrisguitarguy/WP-SOPA-Blackout

SOPA template from:

  http://www.zachstronaut.com/lab/text-shadow-box/stop-sopa.html

Let me know if there's any problems with this version.

-Mike
