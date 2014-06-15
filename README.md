AuthBucket\Bundle\OAuth2Bundle
============================

[![Build
Status](https://travis-ci.org/authbucket/oauth2-bundle.png?branch=master)](https://travis-ci.org/authbucket/oauth2-bundle)
[![Coverage
Status](https://coveralls.io/repos/authbucket/oauth2-bundle/badge.png?branch=master)](https://coveralls.io/r/authbucket/oauth2-bundle)
[![Latest Stable
Version](https://poser.pugx.org/authbucket/oauth2-bundle/v/stable.png)](https://packagist.org/packages/authbucket/oauth2-bundle)
[![Total
Downloads](https://poser.pugx.org/authbucket/oauth2-bundle/downloads.png)](https://packagist.org/packages/authbucket/oauth2-bundle)

[AuthBucket\Bundle\OAuth2Bundle](https://github.com/authbucket/oauth2-bundle)
is a Symfony2 Bundle, which integrate
[AuthBucket\OAuth2](https://github.com/authbucket/oauth2) as easy as
possible into your [Symfony2](http://www.symfony.com) Project.

Installation
------------

First you need to add `authbucket/oauth2-bundle` to `composer.json`:

    {
      "require": {
        "authbucket/oauth2-bundle": "1.0.*@dev"
      }
    }

You also have to add `OAuth2Bundle` to your `AppKernel.php`:

    class AppKernel extends Kernel
    {
        public function registerBundles()
        {
            $bundles = array(
                new AuthBucket\Bundle\OAuth2Bundle\OAuth2Bundle()
            );
            return $bundles;
        }
    }

Continuous Integration
----------------------

This project is coverage with phpunit test cases, where CI result can be
found from https://travis-ci.org/authbucket/oauth2-bundle.

Code coverage CI result can be found from
https://coveralls.io/r/authbucket/oauth2-bundle.

If you hope to run the test cases locally, please execute
`phpunit -c phpunit.xml.dist`. Coverage report can be found from
`build/logs/html` folder.

References
----------

-   http://authbucket.github.io/oauth2-bundle/
-   https://coveralls.io/r/authbucket/oauth2-bundle
-   https://github.com/authbucket/oauth2-bundle
-   https://packagist.org/packages/authbucket/oauth2-bundle
-   https://travis-ci.org/authbucket/oauth2-bundle

License
-------

-   The bundle is licensed under the [MIT
    License](http://opensource.org/licenses/MIT)

