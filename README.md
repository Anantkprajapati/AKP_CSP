# AKP_CSP

Allow Content Security Policy form Magento2

# INSTALLATION STEPS
1. Download module or git clone from here
2. add module under <magento_directory>/app/code/AKP/CSP/
3. Run below Commands

php bin/magento setup:upgrade <br>
php bin/magento setup:static-content:deploy -f <br>
php bin/magento setup:di:compile (if site on production mode) <br>
php bin/magento cache:flush <br>

If any query or doubt please create new issue or you can drop the main on anant101289@gmail.com

Thank you
