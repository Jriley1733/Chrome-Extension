# Chrome-Extension
 {
    "name": "Calculator",
    "update": "2.1",
    "description": "helps you with math!",
    "icons": {
      "128": "icon_16.png",
      "128": "icon_32.png",
      "128": "icon_48.png",
      "128": "icon_128.png"
    },
    "background": {
      "persistent": false,
      "scripts": ["background_script.js"]
    },
    "permissions": ["https://*.google.com/", "activeTab"],
    "browser_action": {
      "default_icon": "icon_16.png",
      "default_popup": "popup.html"
    }
  }
