# Bulgarian (български) Magento2 Language Pack (bg_BG)
This is a Language Pack generated from the [official Magento2 translations project](https://crowdin.com/project/magento-2) at [Crowdin](https://crowdin.com).
The Bulgarian (български) translations used can be found [here](https://crowdin.com/project/magento-2/bg).

# Version & progress
This translation is generated from the branch [2.0.7](https://crowdin.com/project/magento-2/bg#/2.0.7) at Crowdin and based on the Magento 2.0.7 sourcefiles.
There have been  10372 strings translated of the 10372 strings in the Magento source.

Translation progress:![Progress](http://progressed.io/bar/100)

# Instalation
## Via composer
To install this translation package with composer you need access to the command line of your server and you need to have [Composer](https://getcomposer.org).
```
cd <your magento path>
composer require magento2translations/language_bg_bg:dev-master
php bin/magento cache:clean
```
## Manually
To install this language package manually you need access to your server file system.
* Download the zip file [here](https://github.com/Magento2Translations/language_bg_bg/archive/master.zip).
* Upload the contents to `<your magento path>/app/i18n/magento2translations/language_bg_bg`.
* The composer files should then be located like this `<your magento path>/app/i18n/magento2translations/bg_BG/bg_BG.csv`.
* Go to your Magento admin panel and clear the caches.

#Usage
To use this language pack login to your admin panel and goto `Stores -> Configuration -> General > General -> Locale options` and set the '*locale*' option as '*Bulgarian (Bulgaria)*'

# Contribute
To help move the '*Bulgarian (български) Magento2 Language Pack (bg_BG)*' forward please goto [this](https://crowdin.com/project/magento-2/bg) crowdin page and translate the untranslated string or propose better translations.

# Authors
The translations are done by the [official Magento2 translations project](https://crowdin.com/project/magento-2).

Composer package generation originally written by [Wijzijn.Guru](http://www.wijzijn.guru/).
