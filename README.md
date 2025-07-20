# Shipwrecked AltStore Repo

## Guide for adding your app!


### Step 1 - Upload your .ipa file
- Upload your .ipa file to either the #cdn channel on the Hack Club Slack, or another service, I created a GitHub release for my app.
- Make sure the URL is accessible, and that you can download it through an incognito window
> Mark down the file size in bytes, you'll need it later!

### Step 2 - Prepare Your Content
- First of all, you'll need an app icon, recommended as a 1024x1024 PNG file, as well as screenshots, I'd recommend 3-4, and also a description of your app's features and functionality.
> Remember to not go crazily into detail for the description!

### Step 3 - Fork this repo and edit the altstore.json file
- Add your app to the `apps` array in alstore.json, using the template below / in AltStore Example.json

```
      {
        "name": "My Example App",
        "bundleIdentifier": "com.exampledeveloper.exampleapp",
        "marketplaceID": "",
        "developerName": "Example Developer",
        "subtitle": "An awesome app.",
        "localizedDescription": "This is an awesome app only available on AltStore.",
        "iconURL": "https://test.jpeg",
        "tintColor": "#22b0e3",
        "category": "other",
        "screenshots": [],
        "versions": [],
        "appPermissions": {
          "entitlements": [],
          "privacy": {}
        }
```

### Step 4 - Fill in your details!