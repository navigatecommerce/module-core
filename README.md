# Navigate Commerce Core module for Magento 2

## How to install Navigate_Core


### 1. composer Installation (The most recommended method)

Run the following command in Magento 2 root directory to install Navigate_Core module via composer.

#### Install

```
composer require navigate/module-core
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```

#### Update

```
composer update navigate/module-core
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```

Run below command if your store in the production mode:

```
php bin/magento setup:di:compile
```

### 2. Manual Installation

If you prefer to install this module manually, kindly follow the steps described below - 

- Download [the latest version here](https://github.com/navigatecommerce/module-core/archive/refs/heads/main.zip) 
- Extract `main.zip` file to `app/code/Navigate/Core` ; You should create a folder path `app/code/Navigate/Core` if not exist.
- Go to Magento root directory and execute upgrade command to install `Navigate_Core`:

```
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```
