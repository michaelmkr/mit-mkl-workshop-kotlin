
# mit-mkl-workshop-kotlin  
The demo repository for our workshop in the MIT masterclass.  
  
## Steps to run the app  
  
* Clone this repo locally  
  ```  
  git clone https://github.com/michaelmkr/mit-mkl-workshop-kotlin  
  ```  
* [Create a Firebase project in the Firebase console, if you don't already have one](https://firebase.google.com/docs/android/setup)  
* Add a new Android app into your Firebase project with package name com.google.firebase.ml.md  
* Download the config file (google-services.json) from the new added app and move it into the module folder (i.e. [app/](./app/))  
* Build and run it on an Android device  
  
## What is this exactly? 

The goal of this repository is to make it as easy as possible for you in the masterclass industry 4.0 to integrate ML Kit into your app.
Currently it contains:
* Barcode detection using the Barcode API in live camera 
* The basic code for visual search using the Object Detection & Tracking API - a complete workflow from object detection to product search in live camera and static image  (but this is still in alpha for our usecase)

In short this app demonstrates how to build an end-to-end user experience with [Google ML Kit APIs](https://developers.google.com/ml-kit) and of course is following the [new Material for ML design guidelines](https://material.io/collections/machine-learning/).  The repository this Demo App is based on is [mlkit-material-android](https://github.com/firebase/mlkit-material-android).
  
## License  
© Google, 2019. Licensed under an [Apache-2](./LICENSE) license.