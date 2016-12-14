## Magento 2 Arabic Language Pack

*Arabic Language* is your native language and you need to use that language on your magento 2 store. Please follow this article, **Magento 2 Arabic Language Pack** from Magento 2 translation project. The tutorial will help you get Arabic pack and install it fluently.

Read more [Magento 2 Arabic Language Pack](https://www.mageplaza.com/magento-2-arabic-language-pack.html)


## Overview

- Download & Contribute
- Install Arabic Language Pack
- How to Install Arabic Language Pack

## Download & Contribute to Arabic Language Pack

Below are two active buttons which are required operations before installing the language package. Let's hit them to download and contribute Magento 2 Arabic Language Pack immediately!

**Download packages**:

- [Download .zip](https://github.com/mageplaza/magento-2-arabic-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-arabic-language-pack/tarball/master)
- [Copy & paste package](https://crowdin.com/project/magento-2/ar.zip)


Find other [language packs here]({https://www.mageplaza.com/kb/magento-2-language-pack/)

## How to Install Arabic Language Pack

There are 3 different methods to install this language pack.

### #1. Composer method
Install the Arabic language pack via composer is never easier.

**Install Arabic pack**:

```
composer require mageplaza/magento-2-arabic-language-pack:*
php bin/magento cache:clean
php bin/magento setup:static-content:deploy ar-sa

```


**Update  Arabic pack**:

```
composer update mageplaza/magento-2-arabic-language-pack:*
php bin/magento cache:clean
php bin/magento setup:static-content:deploy ar-sa

```

### #2. Copy & Paste method

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
unzip fr.zip /var/www/html/
```

You also can unzip locally and upload them to Magento 2 root folder.

#### Step 3: Flush Magento 2 Cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


### #3. Download and install manually

To download and install Arabic pack manually, you have to access to your server via FTP or SFTP.

#### Step 1: Download the package

- [Download .zip](https://github.com/mageplaza/magento-2-arabic-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-arabic-language-pack/tarball/master)

#### Step 1: Unzip and upload

Unzip the compressed file and upload file `ar_SA.zip` into `app/i18n/mageplaza/ar_SA/ar_SA.csv`

#### Step 2: Flush cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


## How to active language pack

Now time to active the language pack for your Magento 2 store. From Magento 2 admin panel, navigate to `Stores > Configuration > General > Locale Options`
![{{Magento 2 Arabic language pack}}](https://i.imgur.com/aPSUA0l.png)


## Translation process of Arabic Language Pack
![process](http://progressed.io/bar/80)

Contribute to this language at https://crowdin.com/project/magento-2/ar

## Supported Magento versions

- Magento v2.0.0
- Magento v2.0.1
- Magento v2.0.2
- Magento v2.0.3
- Magento v2.0.4
- Magento v2.0.5
- Magento v2.0.6
- Magento v2.0.7
- Magento v2.0.8
- Magento v2.1.0
- Magento v2.1.1
- Magento v2.1.2



## Language package authors

- [Magento official translations project for Magento 2](https://crowdin.com/project/magento-2)
- Language packages built by [Mageplaza team](https://www.mageplaza.com/)


References:
- https://www.mageplaza.com/magento-2-arabic-language-pack.html
- https://www.mageplaza.com/kb/magento-2-language-pack/