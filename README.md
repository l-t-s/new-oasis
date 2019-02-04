# new-oasis

>I got tired of the default new tab page on Chrome and the shitty extensions on the webstore.

This Chrome extension is supposed to make your New Tab page into [https://weboas.is](), because it lists a lot of useful resources and works as a kind of starting page for searching the web.  
The reason why I must make an extension for this is because Chrome currently DOES NOT allow for you to choose your own New Tab page. There is no setting for it.  
Therefore with this extension I try to change it using the extension [``manifest.json``]().  
  

## FYI

What this does, is tell Chrome to use [``html/refresh.html``]() as the New Tab page which will immediately redirect you to [https://weboas.is]().  
Sadly I cannot set [Weboasis](https://weboas.is) as the New Tab page directly, Chrome didn't accept the value as a web URL, instead it gave me an error reading [``manifest.json``]() that the location ``/.`` does not exist.  
  

## Links

- [Weboasis ![Weboasis Logo]()](https://weboas.is)
- [Chrome Web Store]()
- [Github Repository]()
