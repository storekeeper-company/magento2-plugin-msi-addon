# Description

Addon module for [Storekeeper Magento 2 plugin](https://github.com/storekeeper-company/magento2-plugin) which modulfies default flow of Magento MSI stock management.
Needs to be installed in case if your project have Magento MSI modules enabled (Core modules with Magento_Inventory prefix).


## Installation

1. Go to your Magento 2 directory and install the plugin via `composer`:
```
composer require storekeeper/magento2-plugin-msi-addon
```

2. Recompile your Magento 2 installation by running:
```
bin/magento setup:upgrade;
bin/magento setup:di:compile;
bin/magento setup:static-content:deploy;
bin/magento cache:clean;
```
