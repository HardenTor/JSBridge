## Debug folder

Use this folder and its files in case you want to debug the sample.
Please follow below instructions to run sample properly.

## Installation

Prepare Woodford environment according below instructions to try provided sample code.

1. download Debug folder to your local machine
2. import deleteProduct.html file to Offline HTML section of your Woodford project <br />[deleteProduct.html file](https://github.com/Resconet/JSBridge/blob/master/samples/UI/EntityForm/DetailCollection/GetAndDeleteProduct/deleteProduct.html)
3. go to Order entity in Woodford and open its form
4. tap on 'Add IFrame' command
5. set IFrame name to DeleteProduct_example
6. tap on 'Browse' button and select deleteProduct.html file
7. save all changes, publish your project and synchronize the application
8. navigate to your IFrame in the application

**Before testing the example, please make sure you have added some products to the order.**

> Make sure you have latest JSBridge.js file in your Offline HTML section.
<br />[JSBridge.js file](https://github.com/Resconet/JSBridge/blob/master/src/JSBridge.js)

## Installation for debugging

Use this steps if you want to debug the sample and try your own code changes without need to replace the .html file in Offline HTML section every time you make a change.

1. **follow all the steps mentioned above**
2. open project (.sln file) of Debug folder in Visual Studio
3. download debbuging tools and follow installation instructions [Debugging tools](https://github.com/Resconet/JSBridge/tree/master/tools), [Resco Mobile CRM JSDev Edition](https://github.com/Resconet/JSBridge/tree/master/MobileCRM)
4. to run project in the application, click on 'Tools' in VS and choose 'Run in MobileCRM'
<br />

> 'Run in MobileCRM' button replaces your current Offline HTML files in the application folder (WWW folder).
<br />To get Offline HTML files from your Woodford solution, perform Full Sync in the application or make change in Offline HTML folder, publish project and perform Incremental Sync in the application.
