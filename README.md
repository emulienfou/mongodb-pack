A pack for the Doctrine MongoDB ODM
===================================
To be able to use this symfony-pack, you must follow the instruction.   
Since the legacy driver (referred to as `ext-mongo`) is not available on PHP 7, you will need the new driver
(`ext-mongodb`) installed and use a polyfill to provide the API of the legacy driver.

To do this, run the following command before requiring this package:
```bash
composer config "platform.ext-mongo" "1.6.16"
```