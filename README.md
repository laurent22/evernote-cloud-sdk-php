Evernote Cloud SDK 2.0 for PHP (beta)
=====================================

A newly-redesigned, simple, workflow-oriented library built on the Evernote Cloud API. It's designed to drop into your web app easily and make most common Evernote integrations very simple to accomplish. (And even the more complex integrations easier than they used to be.)

Installation
------------

The recommended way to install the SDK is through composer.

Just run these two commands to install it:

``` bash
$ curl -sS https://getcomposer.org/installer | php
$ composer require evernote/evernote-cloud-sdk-php dev-master
```

Now you can add the autoloader, and you will have access to the library:

``` php
<?php

require 'vendor/autoload.php';
```

If you don't use  **Composer** , just require the provided autoloader:

``` php
<?php

require_once 'src/autoload.php';
```

Note for users of the 1.x SDK for PHP
-------------------------------------
This SDK is a complete revision of the previous Evernote SDK for PHP. (Migration guide to come)

FAQ
---

#### Where can I find out more about the Evernote API?

Please check out the [Evernote Developers Portal](https://dev.evernote.com).
