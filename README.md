# What does this extension do?
 It will add html block with Facebook and Twitter icons on Thank You magento2 page, once clicked pop up window will open with link to product that was in cart. 
### Steps to install it
```bash
    mkdir -p <Your Magento2 Installation directory>/app/code/Airslamit/ThankYou && cd $_
    git clone https://github.com/aleksandar-babic/airslamitShareOrder.git .
    php <Your Magento2 Installation directory>/bin/magento module:enable Airslamit_Thankyou
    php <Your Magento2 Installation directory>/bin/magento setup:upgrade
    php <Your Magento2 Installation directory>/bin/magento setup:static-content:deploy
    php <Your Magento2 Installation directory>/bin/magento cache:flush
```
> If you have any additional cache layers you should flush them as well
