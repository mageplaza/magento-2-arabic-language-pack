## Magento 2 Arabic Language Pack

*Arabic Language* is your native language and you need to use that language on your magento 2 store. Please follow this article to get the **Magento 2 Arabic Language Pack** from Magento 2 translation project and install it more easily

Read more [Magento 2 Arabic Language Pack](https://www.mageplaza.com/magento-2-arabic-language-pack.html)


## Overview

- Download & Contribute
- Install Arabic Language Pack
- How to Install Arabic Language Pack

## 1. Download & Contribute to Arabic Language Pack

Below are two active buttons which are required operations before installing the language package. Let's hit them to download and contribute Magento 2 Arabic Language Pack immediately!

**Download packages**:

- [Download .zip](https://github.com/mageplaza/magento-2-arabic-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-arabic-language-pack/tarball/master)


Find other [language packs here](https://www.mageplaza.com/kb/magento-2-language-pack/)

## 2. How to Install Arabic Language Pack

There are 3 different methods to install this language pack.

### ✓ Method #1. Composer method (Recommend)
Install the Arabic language pack via composer is never easier.

**Install Arabic pack**:

```
composer require mageplaza/magento-2-arabic-language-pack:dev-master
php bin/magento setup:static-content:deploy ar_SA
php bin/magento cache:flush

```


**Update  Arabic pack**:

```
composer update mageplaza/magento-2-arabic-language-pack:dev-master
php bin/magento setup:static-content:deploy ar_SA
php bin/magento cache:flush

```

#### Authentication required (If any)

![Authentication required](https://cdn.mageplaza.com/media/general/dmryiPk.png)

If you have not added this authentication, you can follow [this guide](http://devdocs.magento.com/guides/v2.0/install-gde/prereq/connect-auth.html)


### ✓ Method #2. Copy & Paste method (Not recommended)

This method suitable for non-technical people such as merchants. Just download the package then flush cache.

**Overview**

- Step 1: Download the Arabic language pack
- Step 2: Unzip Arabic pack
- Step 3: Flush Magento 2 Cache

#### Step 1 : Download the Arabic language pack

You can download the language pack from above link

#### Step 2: Unzip Arabic pack

Unzip the Arabic language pack to Magento 2 root folder. In this guide, we extract to `/var/www/html/`
Your Magento 2 root folder can be: `/home/account_name/yourstore.com/public_html/`

```
unzip fr.zip app/i18n/Mageplaza/ar_sa
```

You also can unzip locally and upload them to Magento 2 root folder.

#### Step 3: Flush Magento 2 Cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


### ✓ Method #3. Download and install manually (Not recommended)

To download and install Arabic pack manually, you have to access to your server via FTP or SFTP.

#### Step 1: Download the package

- [Download .zip](https://github.com/mageplaza/magento-2-arabic-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-arabic-language-pack/tarball/master)

#### Step 1: Unzip and upload

Unzip the compressed file and upload file `ar_SA.zip` into `app/i18n/mageplaza/ar_SA/ar_SA.csv`

#### Step 2: Flush cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


## 3. How to active Arabic language pack
O
Now time to active the Arabic language pack for your Magento 2 store. From Magento 2 admin panel, navigate to `Stores > Configuration > General > Locale Options`
![{{Magento 2 Arabic language pack}}](https://cdn.mageplaza.com/media/general/aPSUA0l.png)


## 4. How to contribute

![language pack](http://progressed.io/bar/{{process}}?title=translated)

Contribute to this language at https://crowdin.com/project/magento-2/ar

## 5. Supported Magento versions

It supports all Magento 2 versions include [Magento 2 open-source](https://www.mageplaza.com/download-magento/), Magento 2 Commerce.


- Magento v2.0.x
- Magento v2.1.x
- Magento v2.2.x



## 6. Note

- This project automatically updates weekly from Crowdin.
- Any question, issue please [create a new issue](https://github.com/mageplaza/magento-2-arabic-language-pack/issues/new)

## 7. Language package authors

- [Magento official translations project for Magento 2](https://crowdin.com/project/magento-2)
- Language packages built by [Mageplaza team](https://www.mageplaza.com/)


## 8. References:

- https://www.mageplaza.com/magento-2-arabic-language-pack.html
- https://crowdin.com/project/magento-2








## Mageplaza extensions on Magento Marketplace, Github


- [Layered Navigation](https://marketplace.magento.com/mageplaza-layered-navigation-m2.html)
- [One Step Checkout](https://marketplace.magento.com/mageplaza-magento-2-one-step-checkout-extension.html)
- [SMTP](https://marketplace.magento.com/mageplaza-module-smtp.html) ; [SMTP on Github](https://github.com/mageplaza/magento-2-smtp)
- [Blog](https://github.com/mageplaza/magento-2-blog)
- [Security](https://marketplace.magento.com/mageplaza-module-security.html)
- [Social Login](https://github.com/mageplaza/magento-2-social-login)

- [SEO](https://github.com/mageplaza/magento-2-seo) ; [SEO on Marketplace](https://marketplace.magento.com/mageplaza-magento-2-seo-extension.html)

- [SMTP](https://github.com/mageplaza/magento-2-smtp)

- [Product Slider](https://github.com/mageplaza/magento-2-product-slider)

- [Banner](https://github.com/mageplaza/magento-2-banner-slider)

- [Sample Payment Method](https://github.com/mageplaza/magento-2-sample-payment-method)



