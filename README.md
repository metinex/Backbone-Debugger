Backbone Debugger
=================

Chrome Developer Tools extension for debugging Backbone.js applications.

Features
--------
* Adds a panel under the Chrome Developer Tools that displays in real-time all your application views, models, collections and routers. Data displayed includes:
    * Views: rendering status, html element, associated model and/or collection, **handled page events**, events triggered
    * Models: last sync status, **attributes**, id, cid, url, associated collection, events triggered, **sync actions**
    * Collections: last sync status, **models**, url, events triggered, **sync actions**
    * Routers: events triggered (include **routes**)
* Extends the sidebar of the developer tools "Elements" panel to display the Backbone View of the inspected html element.

Install from source
--------
Using Google Chrome:
* [Download the project archive](https://github.com/Maluen/Backbone-Debugger/archive/master.zip) and extract it somewhere.
* Click on Tools -> Settings -> Extensions
* Select "Enable developer mode" in the upper right of the window.
* Click on "Load unpacked extension".
* Select the extracted folder.
* Enjoy!

Install from Chrome Web Store
--------
* Go to the [extension page](https://chrome.google.com/webstore/detail/backbone-debugger/bhljhndlimiafopmmhjlgfpnnchjjbhd) and follow the instructions. Leave a review if you can!    

Follow this method if you want the latest stable release, it will also update automatically.

Known Limitations
--------
Support for apps that modify the standard Backbone behavior, e.g. apps that patch core methods like extend or 
delegateEvents, or that replace part of Backbone functions with custom code, is uncertain.
However, constant efforts are taken in this direction to address the most possible use cases, so even if your application falls into this category you may still give it a try, [open an issue](https://github.com/Maluen/Backbone-Debugger/issues) or wait for newer versions.

Contribute
--------
Want to contribute? You can [report bugs](https://github.com/Maluen/Backbone-Debugger/issues), [suggest features](https://github.com/Maluen/Backbone-Debugger/issues), [write code](https://github.com/Maluen/Backbone-Debugger/pulls) and [write documentation](https://github.com/Maluen/Backbone-Debugger/wiki)!

Searching for other ways? You can also support this project by [donating on Gittip](https://www.gittip.com/Maluen/)

Screenshots
--------
**Views**:

![Views](http://cloud.githubusercontent.com/assets/1434239/3420660/ec70f9d0-feb7-11e3-8639-fdafd1152992.png "Views")

**Models**:

![Models](http://cloud.githubusercontent.com/assets/1434239/3420661/133eec20-feb8-11e3-9a73-3d69cb9b3b51.png "Models")

**Collections**:

![Collections](http://cloud.githubusercontent.com/assets/1434239/3420664/25bc273c-feb8-11e3-823b-31f799754ff0.png "Collections")

**Routers**:

![Routers](http://cloud.githubusercontent.com/assets/1434239/3420665/3000371a-feb8-11e3-8e11-86df8b9dcfdd.png "Routers")

**Elements sidebar extension**:

![Elements sidebar extension](http://cloud.githubusercontent.com/assets/1434239/3420666/3b8c4d4e-feb8-11e3-9c1a-b764be6beacb.png "Elements sidebar extension")
