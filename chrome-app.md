
Manifest.json


``` JSON
{
  "manifest_version": 2,

  "name": "Getting started example",
  "description": "This extension shows a Google Image search result for the current page",
  "version": "1.0",
  "icons": { "128": "icon_128.png", "16": "16.png" },

  "browser_action": {
    "default_title": "",
    "default_icon": "icon.png",
    "default_popup": "popup.html"
  },
  "permissions": [
    "activeTab",
    "https://ajax.googleapis.com/"
  ]
}
```


## Paramètres

Pour faire tourner comme une app

``` JSON
 
  "app": {
    "background": {
      "scripts": ["background.js","app.bundle.js"]
    }
  },
  
```

Arrière plan

``` JSON
 "background": {
    "persistent": false,
    "scripts": ["bg.js"]
  }
 ```
