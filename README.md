# CustomDataBinding
Android Binding Adapters - Custom Data Binding

***For Internet Permision***
1. Go to AndroidManifest.xml and add before <application :
   <uses-permission android:name="android.permission.INTERNET"/>

2. Go to build.gradle add this :
  
  inside plugin : id 'kotlin-kapt'
  
  
  buildFeatures{
        dataBinding true
    }
 
 and add this 2 dependencies : 
 
     implementation 'com.github.bumptech.glide:glide:4.12.0'
    kapt 'com.github.bumptech.glide:compiler:4.12.0'
 
