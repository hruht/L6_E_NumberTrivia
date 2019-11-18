# L6_E_NumberTrivia
Level 6 - Example

Fetch random number trivias from REST Api (JSON) and display that data


NOTE!


Dependencies:
///////////////////

// ViewModel and LiveData
def lifecycle_version = "2.1.0"
implementation "androidx.lifecycle:lifecycle-extensions:$lifecycle_version"

// Retrofit
implementation 'com.squareup.retrofit2:retrofit:2.6.2'
implementation 'com.squareup.retrofit2:converter-gson:2.6.2'
implementation 'com.squareup.okhttp3:okhttp:3.12.0'
implementation 'com.squareup.okhttp3:logging-interceptor:3.12.0'

///////////////////


In AndroidManifest.xml:

///////////////////

<?xml version="1.0" encoding="utf-8"?>
<manifest xmlns:android="http://schemas.android.com/apk/res/android"
         xmlns:tools="http://schemas.android.com/tools" package="com.example.numberskotlin">

   <uses-permission android:name="android.permission.INTERNET" />

   <application
           android:usesCleartextTraffic="true"
           ...
           ...
           
///////////////////
           
