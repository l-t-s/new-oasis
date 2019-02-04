# new-oasis

>I got tired of the default [New Tab] page on [Chrome] and the bad extensions on the Web Store.

This [Chrome] extension is supposed to make your **[New Tab]** page into **<https://weboas.is>**, because it lists a lot of useful resources and works as a kind of starting page for searching the web.  
The reason why I must make an extension for this is because **[Chrome] currently DOES NOT allow for you to choose your own [New Tab] page**. *There is no setting for it.*  
Therefore with this extension I try to change it using the extension [``manifest.json``](https://github.com/l-t-s/new-oasis/blob/master/manifest.json).  
  

## FYI

What this does, is tell [Chrome] to use [``html/refresh.html``](https://github.com/l-t-s/new-oasis/blob/master/html/refresh.html) as the [New Tab] page which will immediately redirect you to <https://weboas.is>.  
Sadly I cannot set [Weboasis] as the [New Tab] page directly, extension packager didn't accept the value as a web URL, instead it gave me an error reading [``manifest.json``](https://github.com/l-t-s/new-oasis/blob/master/manifest.json) that the location ``/.`` does not exist.  
  

## Links

- [<img src="https://raw.githubusercontent.com/l-t-s/new-oasis/master/images/icon16.png" alt="Weboasis Logo" height="16"> Weboasis](https://weboas.is)
- [<img src="https://developer.chrome.com/webstore/images/ChromeWebStore_Badge_v2_206x58.png" alt="Chrome Web Store Logo" height="16"> Chrome Web Store](https://chrome.google.com/webstore/detail/new-oasis/fbhknamebagjckhlmkhcnnjgkaghille)
- [<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="GitHub Logo" height="16"> GitHub Repository](https://github.com/l-t-s/new-oasis)


[New Tab]: chrome://newtab
[Chrome]: https://www.google.com/chrome/
[Weboasis]: https://weboas.is/
