# UnityAdaptiveIconsSupport
Create adaptive icon for app using Android Studio 3.0+.
Replace the res folder of the plugin with your app icons.
Copy paste the plugin under Plugins/Android.
If your project doesn't have has AndroidManifest.xml under Plugins/Android then create one and add support for adaptive icons by adding roundIcon property inside application tag.

        <application
        android:icon="@mipmap/ic_launcher"
        android:roundIcon="@mipmap/ic_launcher_round">
