# Discovering Composer

This repository acts as a sample to accompany a blog post ([http://grantpalin.com/blog/discovering-composer-php-dependencies/](http://grantpalin.com/blog/discovering-composer-php-dependencies/)) on the usage of Composer in PHP projects.

The included `composer.json` is deliberately simple, just enough to show how to require a dependency. Dropping `composer.json` (and optionally-yet-ideally the accompanying `composer.lock`) into an empty directory and running `composer install` will cause the specified dependency to be downloaded.

Also note that the `.gitignore` file contains a directive to ignore the Composer-created `vendor` directory so that it is not mistakenly added to the source control.
