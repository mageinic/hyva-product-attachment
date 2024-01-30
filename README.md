# Hyvä Product Attachment

**Hyvä Product Attachment is a part of MageINIC Product Attachment extension that adds Hyvä features.** This extension extends Product Attachment definitions.

## 1. How to install

Run the following command in Magento 2 root folder:

```
composer require mageinic/hyva-product-attachment

php bin/magento maintenance:enable
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
php bin/magento maintenance:disable
php bin/magento cache:flush
```

**Note:**
Magento 2 Product Attachment requires installing [MageINIC Product Attachment](https://github.com/mageinic/product-attachment) in your Magento installation.

**Or Install via composer [Recommend]**
```
composer require mageinic/product-attachment
```

## 2. Get Support

- Feel free to [contact us](https://www.mageinic.com/contact.html) if you have any further questions.
- Like this project, Give us a **Star**
