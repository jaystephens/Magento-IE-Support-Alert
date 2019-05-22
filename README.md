# Magento-IE-Support-Alert
Magento Module to alert customers that you are no longer supporting IE. ( And you shouldn't be )
It sets a cookie for 1 day to keep the popup from reapearing should a user not heed the warning.

Step 1: Put the folder in the app>code>vendor directory in your project
Step 2: Edit the "vendor" line to be your vendor in the following 3 files 
    1.registration.php
    2.etc>module.xml
    3.view>frontend>layout>default.xml
Step 3: Run the bin/magento setup:upgrade script to install the new module.
Step 4: Enjoy!
