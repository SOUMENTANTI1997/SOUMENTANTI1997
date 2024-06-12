{
  "update_url": "https://clients2.google.com/service/update2/crx",
  "name": "IRCTC Tatkal Automation Tool",
  "description": "IRCTC Tatkal Automation Tool helps you book IRCTC tatkal tickets at an ease. It autofills and submits all data during tatkal booking",
  "version": "0.1.0",
  "manifest_version": 3,
  "action": {
    "default_popup": "popup.html",
    "default_icon": "irctc400.png",
    "default_title": "IRCTC Auto fill"
  },
  "icons": {
    "16": "irctc16.png",
    "48": "irctc48.png",
    "128": "irctc128.png"
  },
  "background": {
    "service_worker": "./background_script.js"
  },
  "permissions": [
    "scripting",
    "tabs",
    "storage"
  ],
  "host_permissions": [
    "https://www.irctc.co.in/"
  ]
}
