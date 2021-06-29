
# How to make a Chrome Extension

- Making a chrome extension is as simple as creating a navbar in a website.
- Also you have to make only desktop version and that's why you don't need to take care of responsiveness. 





## Steps: 

- First step is to create a `manifest.json` file same as given below -
```
{ 
    "manifest_version": 2,
    "name": "Name_Of_Extension",
    "description": "Short_Description_of_Extension",
    "version": "Version",
    "icons": { "128": "128_logo.png" }, 
    "browser_action": {
      "default_icon": "logo.png",
      "default_popup": "pop.html"
    },
    "permissions": ["activeTab"]
  }
  ```

  - Second step is to create a `html` file **:** this file is nothing but a normal code of extension and you can use html,css and javascript to create basic extensions.
  
  - Extension code has been created now it's time to use it.
  - Go to Chrome , in search bar go to - 
  ```http
  chrome://extensions/
```

- Make developer mode **ON** and click on **Load Unpacked** and upload your extension folder and **Congratulations!** You have created your first Chrome Extension. 
## How to upload on chrome store?
- Uploading on chrome web store takes one time investment of ***5$.***
- I have also not uploaded my extension but I can use it and anyone who want to use it can use my code.
- If you want to upload on chrome store then [Read this blog](https://developer.chrome.com/docs/webstore/publish/).

  
## Happy Learning.. 



  