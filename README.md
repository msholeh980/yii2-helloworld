# yii2-helloworld

Simple Yii2-extension

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require msholeh980/yii2-helloworld "dev-master"
```

or add

```
"msholeh980/yii2-helloworld": "dev-master"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```
<?php
use msholeh980\helloworld\Helloworld;

echo Helloworld::widget();
?>
