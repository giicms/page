Page
=================

Module page

## Installation

The preferred way to install this extension is through composer.

Either run

```
php composer.phar require "giicms/page" "dev-master"
```
or add

```json
"giicms/page": "dev-master"
```

to the require section of your application's `composer.json` file.

## Usage Example
~~~php

 'modules' => [
        'page' => [
            'class' => 'giicms\page\Module',
        ],
  ],
~~~
