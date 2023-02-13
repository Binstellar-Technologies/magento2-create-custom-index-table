## Magento2 Create custom Index table

> Magento2 an open-source e-commerce platform written in PHP.

&nbsp;
&nbsp;

> In this extension we will learn how to create an Indexer Reindex in Magento 2. Indexer is an important feature in Magento 2 Indexing.

&nbsp;
&nbsp;

> Indexing is how Magento transforms data such as products, categories, and so on, to improve the performance of your storefront.

&nbsp;
&nbsp;

> As data changes, the transformed data must be updated. To optimise storefront performance, Magento accumulates data into special tables using indexers.

&nbsp;
&nbsp;

## Installation Steps

##### Step 1 : Download the Zip file from Github & Unzip it
##### Step 2 : Create a directory under app/code/Binstellar/CustomIndexer
##### Step 3 : Upload the files & folders from extracted package to app/code/Binstellar/CustomIndexer
##### Step 4 : Go to the Magento2 Root directory & run following commands

php bin/magento setup:upgrade

php bin/magento setup:di:compile

php bin/magento setup:static-content:deploy -f

php bin/magento cache:flush

&nbsp;
&nbsp;

<kbd>

![image1](https://user-images.githubusercontent.com/123800304/218386958-e4e55ac0-7506-4b86-8435-fd4f658a66b4.png)


</kbd>

&nbsp;
&nbsp;

## Note : We have tested this option in Magento ver. 2.4.5-p1
