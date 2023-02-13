# Workshop_Tools_Manager

## Introduction

Welcome to our Workshop , today we will see how to create an application using [Flutter](https://flutter.dev/).\
We hope that you will enjoy and learn as much as you can during this workshop ! :)

---
## Prerequisites

### **What we need ?**
 For this workshop you will need to have **Android Studio**, **Flutter** installed on your computer. If it's not already done, you can find the installations guides bellow :
- https://developer.android.com/studio/install?hl=fr
- https://docs.flutter.dev/get-started/install

You can also create an android emulator using the following tutorial :
- https://developers.foxit.com/developer-hub/document/create-an-emulator-for-testing-in-android-studio/#:~:text=In%20Android%20Studio%20go%20to,on%20the%20%E2%80%9CNext%E2%80%9D%20button

---
---
## __STEP 0__ : Creation of a POC
- First of all, we will create an simple page with a colored rectangle which contains a text in the center of the page.\
**IMPORTANT: Don't forget to follow the documentation [here](https://docs.flutter.dev/development/ui/widgets-intro) or with the following link : https://docs.flutter.dev/development/ui/widgets-intro**

Here is an example page of what we exoect :\

![](/.assets/poc.png "POC")

---
---
## **DOCUMENTATION /!\\**
- _You will find all the documentation you need by clicking [here](https://docs.flutter.dev/) or with the following link: https://docs.flutter.dev/_

---
---
## __STEP 1__ :
*For this first step, will a create a page with boxes that redirect to a specific destination*

### **STEP 1.1 : Create Multiple Boxes**
Now with what you learned from the Step 0 you'll have to create multiple boxes with text in it to specify to what will the box redirect to (ex:Intra Epitech)

### **STEP 1.2 : Interaction with boxes**
Once you have created the boxes, you will have to try to interact with them in order to display a text with a print. Then you have two options:
 - You can use the dart class named "TextButton", that will allow you to do action after only pressing the text.\
 or
 - You can also use the dart class "GestureDetector", that will allow you to do action after pressing on all his children.

### **STEP 1.3 : Launch a webpage with url**
Now you will use the function "launch" and "canlaunch" to simply open the url you want :D

---
---
## __STEP 2__ :
*For this step you will create a new page in order to display your futur requests*

### **STEP 2.1 : Create a new class that will contain your new page**
For this step you will take as example the page you were working on previously and create a simple page.

### **STEP 2.2 : Create a button that will allow you to move into the new page**
For this step you will use the "Navigator" class and change page with a button that you will create that will use the Navigator class.

---
---
## __STEP 3__ :
 *Now we will learn how to interact with an API, in our case we will use the API of citymapper.*

### **STEP 3.1 : Create a requestGet class**
Let's use the code given and the documentation to do so. To see if it's working you will get from this url: "https://jsonplaceholder.typicode.com/posts"

### **STEP 3.2 : Get your current location (longitude and latitude)**
In this step you will use Geolocator to get your position. Make sure you have the correct permissions to do it.

### **STEP 3.3 : Make a simple request using your position**
With your position and the position of th Eiffel Tower, you will make a request to get the travel time on any sort of transport.


API Documentation :
http://docs.external.citymapper.com/api/

---
---
## __BONUS ON DOCKER__:

    For the Bonus Part and if you already done the entire workshop. You can create a Dockerfile to generate an image and build an apk for your application.
