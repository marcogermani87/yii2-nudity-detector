PHP Nudity Detector
===================
This algorithm tries to detect nudity in the image based on the amount os skin colors in it. Based on work of FreebieStock (https://github.com/FreebieStock/php-nudity-detector)

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist necrox87/yii2-nudity-detector "*"
```

or add

```
"necrox87/yii2-nudity-detector": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \necrox87\NudityDetector\AutoloadExample::widget(); ?>```