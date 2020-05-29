# HelloSharedPrefs

## Summary

-   The  [`SharedPreferences`](https://developer.android.com/reference/android/content/SharedPreferences.html)  class allows an app to store small amounts of primitive data as key-value pairs.
-   Shared preferences persist across different user sessions of the same app.
-   To write to the shared preferences, get a  [`SharedPreferences.Editor`](https://developer.android.com/reference/android/content/SharedPreferences.Editor)  object.
-   Use the various "put" methods in a  `SharedPreferences.Editor`  object, such as  [`putInt()`](https://developer.android.com/reference/android/content/SharedPreferences.Editor#putInt(java.lang.String,%20int))  or  [`putString()`](https://developer.android.com/reference/android/content/SharedPreferences.Editor#putString(java.lang.String,%20java.lang.String)), to put data into the shared preferences with a key and a value.
-   Use the various "get" methods in a  `SharedPreferences`  object, such as  [`getInt()`](https://developer.android.com/reference/android/content/SharedPreferences#getInt(java.lang.String,%20int))  or  [`getString()`](https://developer.android.com/reference/android/content/SharedPreferences#getString(java.lang.String,%20java.lang.String)), to get data out of the shared preferences with a key.
-   Use the  [`clear()`](https://developer.android.com/reference/android/content/SharedPreferences.Editor#clear())  method in a  `SharedPreferences.Editor`  object to remove all the data stored in the preferences.
-   Use the  [`apply()`](https://developer.android.com/reference/android/content/SharedPreferences.Editor#apply())  method in a  `SharedPreferences.Editor`  object to save the changes to the preferences
