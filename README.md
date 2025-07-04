# Lab Week 8 - Fetch API & ServiceWorkers

GitHub Pages: https://annadoannn.github.io/Lab8_Starter/

**By: Anna Doan**

**How are graceful degradation and service workers related?**
> Graceful degradation refers to designing an application to provide the best possible user experience in modern environments while still maintaining basic funcionality on older or less capable browsers. Service Workers help support graceful degradation by providing offline capabilities and caching strategies. When a user doesn’t have a stable network connection, Service Workers can intercept network requests and supply data that’s already saved locally, ensuring that essential parts of the application continue to work. In this way, service workers help maintain a baseline user experience even when some of the more advanced features of the web app might not be fully supported.

![PWA Image](pwa.png)

**NOTE:** I changed the src file path for the icons in `manifest.json` to get rid of the errors in the DevTools Console about not having the right filepath. Due to that error, I was getting an image does not exist error. Otherwise, I would have left the original `"src": "/assets/images/icons/icon-192x192.png"` untouched. 