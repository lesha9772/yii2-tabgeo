Yii2 TabGeo extension 
======================
extension based on php tabgeo library (http://tabgeo.com)


Instalation
===

add to composer.json into 'require' seaction

	"lesha9772/yii2-tabgeo": "dev-master"



Either run

```
php composer.phar update
```


Usage
-----

Once the extension is installed, simply use it in your code by  :



```php
use lesha9772\tabgeo\TabGeoWidget;

$ip  = "ip address"

<?= TabGeoWidget::contry($ip);   ?>```

