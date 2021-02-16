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
      "io.elhan.facebook-sdk": "https://github.com/oae/unity-package-facebook-sdk.git#0.1.0",
    }
  }
  ```

> For the official plugin, check out the [original repository](https://github.com/facebook/facebook-sdk-for-unity)
