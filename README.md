# Navigate Core for Magento 2

## How to install Navigate_Core


### 1. Install via composer (recommend)

We recommend you to install Navigate_Core module via composer. It is easy to install, update and maintaince.

Run the following command in Magento 2 root folder.

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

Run compile if your store in Product mode:

```
php bin/magento setup:di:compile
```

### 2. Copy and paste

If you don't want to install via composer, you can use this way. 

- Download [the latest version here](https://github.com/navigatecommerce/module-core/archive/refs/heads/main.zip) 
- Extract `main.zip` file to `app/code/Navigate/Core` ; You should create a folder path `app/code/Navigate/Core` if not exist.
- Go to Magento root folder and run upgrade command line to install `Navigate_Core`:

```
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```