# Ad Blocker
Simple chrome extension which blocks request from different urls

This is a simple ad blocker more like a url blocker.

You can clone the repository on to your local machine and follow the below steps to use this extension

1. Open chrome and go to this URL -  chrome://extensions
2. Toggle developer mode on the right side 
  ![alt text](https://github.com/satyavamsi/ad_blocker/blob/master/screenshots/dev_mode.png)
3. Click on "Load Unpacked"
4. Select the cloned repository.
5. You should see a new extension gets added to the list as shown below
   ![alt text](https://github.com/satyavamsi/ad_blocker/blob/master/screenshots/unpack_ad.png)
   
# Adding more URLs to extension.

I have already added some of the famous ad urls but if you want to add more follow the steps below.

1.Open background.js and add the url to defaultFilters variable
```
const defaultFilters = [
    "*://*.doubleclick.net/*",
    "*://partner.googleadservices.com/*",
    "*://*.googlesyndication.com/*",
    "*://*.google-analytics.com/*",
    "*://creative.ak.fbcdn.net/*",
    "*://*.adbrite.com/*",
    "*://*.exponential.com/*",
    "*://*.quantserve.com/*",
    "*://*.scorecardresearch.com/*",
    "*://*.zedo.com/*",
]
```
2. And finally just remove the extension and load it again. And that's it!!
