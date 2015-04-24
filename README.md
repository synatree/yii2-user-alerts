Yii2 User Alerts Extension
==========================
An extension that allows messages to be broadcast to users based on their role, including functionality to dismiss messages after they've been read.

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist synatree/yii2-user-alerts "*"
```

or add

```
"synatree/yii2-user-alerts": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \synatree\useralerts\AutoloadExample::widget(); ?>```