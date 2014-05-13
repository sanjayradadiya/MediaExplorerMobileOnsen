MediaExplorerMobileOnsen
========================

iTunes Media Explorer mobile application sample written with Cordova+OnsenUI (AngularJS+Topcoat).

#### Create Project
You can create your own new project locally using the Cordova CLI based on my code (after you've cloned or downloaded) with:

    $ cordova create MyMediaExplorerOnsen "com.mediaexplorer.app" "MediaExplorerOnsenApp" --copy-from /MediaExplorerMobileOnsen/www

Or create a new project and manually replace the www folder with mine.

    $ cordova create MyMediaExplorerOnsen

#### Add Plugins

Add the following plugins to the application:

    $ cordova plugin add org.apache.cordova.console 
    $ cordova plugin add org.apache.cordova.device 
    $ cordova plugin add org.apache.cordova.inappbrowser 
    $ cordova plugin add org.apache.cordova.statusbar

#### Add a Platform
    $ cordova platform add ios

#### Run the App

    $ cordova run ios
