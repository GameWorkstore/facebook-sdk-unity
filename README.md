# Game Workstore Facebook SDK for Unity NPM

Unity NPM version of Facebook SDK! This repository applies the same license terms of the original version. 

Original version: [facebook-sdk-for-unity](https://github.com/facebook/facebook-sdk-for-unity)

# Installation

- Add the Google Scope:
  
  ```json
  "scopedRegistries": [
    {
      "name": "Game Package Registry by Google",
      "url": "https://unityregistry-pa.googleapis.com",
      "scopes": [
        "com.google"
      ]
    }
  ]
  ```

- Add following dependency to `Packages/manifest.json` in your project;

  ```json
  {
    "dependencies": {
      "com.google.external-dependency-manager": "1.2.164",
      "com.gameworkstore.facebooksdkunity": "git://github.com/GameWorkstore/facebook-sdk-unity?path=Assets/Package"
    }
  }
  ```

> For the official plugin, check out the [original repository](https://github.com/facebook/facebook-sdk-for-unity)

# FAQ

For Unity Android games, add on facebook settings your packageName (com.example.etc) and your activityClass from manifest.
Go to advanced settings and enable "Native or desktop app?" to true. Respond "Is App Secret embedded in the client?" to false.
Don't include your client secret if not necessary in the app.

