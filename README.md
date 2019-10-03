A pack for the Doctrine MongoDB ODM
===================================
To be able to use this symfony-pack, you must follow the instruction.   
Since the legacy driver (referred to as `ext-mongo`) is not available on PHP 7, you will need the new driver
(`ext-mongodb`) installed and use a polyfill to provide the API of the legacy driver.

Provide virtual packages
------------------------
This pack also provide 2 virtual packages who can be used to require a doctrine database support:
* `doctrine/implementation`
* `doctrine/mongodb-implementation`
