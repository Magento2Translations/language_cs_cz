# Czech (čeština) Magento2 Language Pack (cs_CZ)
This is a Language Pack generated from the [official Magento2 translations project](https://crowdin.com/project/magento-2) at [Crowdin](https://crowdin.com).
The Czech (čeština) translations used can be found [here](https://crowdin.com/project/magento-2/cs).
This translation is usefull for people living in the Czech Republic (Česká republika).

For our other language packs look at the [Magento2Translations](http://magento2translations.github.io/) page.

# Instalation
## Via composer
To install this translation package with composer you need access to the command line of your server and you need to have [Composer](https://getcomposer.org).
```
cd <your magento path>
composer require magento2translations/language_cs_cz:dev-master
php bin/magento cache:clean
```
## Manually
To install this language package manually you need access to your server file system.
* Download the zip file [here](https://github.com/Magento2Translations/language_cs_cz/archive/master.zip).
* Upload the contents to `<your magento path>/app/i18n/magento2translations/cs_CZ`.
* The composer files should then be located like this `<your magento path>/app/i18n/magento2translations/cs_CZ/cs_CZ.csv`.
* Go to your Magento admin panel and clear the caches.

#Usage
To use this language pack login to your admin panel and goto `Stores -> Configuration -> General > General -> Locale options` and set the '*locale*' option as '*Czech (Czech Republic)*'

# Contribute
To help push the '*Czech (čeština) Magento2 Language Pack (cs_CZ)*' forward please goto [this](https://crowdin.com/project/magento-2/cs) crowdin page and translate the lines.