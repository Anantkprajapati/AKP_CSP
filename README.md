# AKP_CSP

Allow Content Security Policy in Magento2

# INSTALLATION STEPS
1. Download module or git clone from here
2. add module under <magento_directory>/app/code/AKP/CSP/
3. Please open etc/config.xml file and replace url
<pre>http://www.example.com/</pre>

to 
<pre>YOUR-SITE-URL</pre>

4. Run below Commands

4.1 php bin/magento setup:upgrade 

4.2 php bin/magento setup:static-content:deploy -f 

4.3 php bin/magento setup:di:compile (if site on production mode) 

4.4 php bin/magento cache:flush

If any query or doubt please create new issue or you can drop the mail on anant101289@gmail.com

Thank you
