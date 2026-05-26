# Lab8-Starter

Aidan Rikic

### How are graceful degradation and service workers related?

Graceful degradation and service workers are related because service workers are one of the tools that we can use to implement graceful degradation on a website. Graceful degradation means designing an application to function at full capacity under ideal conditions, but when things go wrong (like poor network connection) still providing some sort of usable experience. Service workers can help with this by looking at network requests and using cached responses when the network is unavailable. So instead of the app completely breaking when you're offline, it degrades gracefully by falling back to whatever it has stored locally. In this lab specifically our app fully loads recipes from the network on first visit, but on later visits (which can be offline) the service worker can step in and serve cached data, keeping the app functional even without internet access.


### App Screenshot
![Lab 8 App Screenshot](pwa.png)

### Link
[Page's Link](https://aidanrik.github.io/Lab8_Starter/)
