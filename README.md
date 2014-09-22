This simple native Android application shows a Google Map view. When you select the "Get location from GX" button it gets simulated location coordinates from the Inmarsat Global Xpress Location API. When you select the Get accessnetwork button it shows the type of network you are currently connected to from the AccessNetwork sandbox API (this is hard coded to GX).

You will need to use the Android developer kit available from Google to compile the code for this project (http://developer.android.com)

You will need to get your own API key from Google so that you can use the Maps API:
A fast way to get started with the [Google Maps Android API v2](http://developers.google.com/maps/documentation/android).

Once you have this put your key in the manifest.xml file in the highlighted place.

There is also a pre-compiled hellomap.apk file included with this project, you can just install that on your Android device and it will work. Note you will need to allow installation from untrusted sources on your Android device (see http://developer.android.com/distribute/tools/open-distribution.html#unknown-sources for details on this option)
