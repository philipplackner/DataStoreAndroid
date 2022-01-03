# DataSource Usage Demo

This is a demo project which using DataSource to save data.

> Jetpack DataStore is a data storage solution that allows you to store key-value pairs or typed objects with [protocol buffers](https://developers.google.com/protocol-buffers). DataStore uses Kotlin coroutines and Flow to store data asynchronously, consistently, and transactionally.
>
> If you're currently using [`SharedPreferences`](https://developer.android.com/reference/kotlin/android/content/SharedPreferences) to store data, consider migrating to DataStore instead.

This is the information from Android developer website



In the project, we create 2 edit text to get the user input：

1. dataStore key EditText
    + which equals to SharedPreferences key
2. dataStore value EditText
    + which equals to SharedPreferences value

in the demo case, we just using write and read `String` value as examples, DataStore can store those values:

+ String
+ Int
+ Float
+ Long
+ Boolean
+ Double
+ `Set<String>`

this support data type was declared in `PreferencesKeys.kt` files using Kotlin extends functions.



---

## The Key Code in Demo

please view the  `MainActivity.kt` file to check the demo code, this is really very easy.



## For More Information

1. check Android Developer website
    + [DataStore  | Android Developers](https://developer.android.com/topic/libraries/architecture/datastore#synchronous)
2. the blog from Android Developer, which you can get more info about the libs design

    + [Prefer Storing Data with Jetpack DataStore](https://android-developers.googleblog.com/2020/09/prefer-storing-data-with-jetpack.html)
3. 2 CodeLabs about using DataSource by Android Team

    + [Working with Preferences DataStore  | Android Developers](https://developer.android.com/codelabs/android-preferences-datastore#0)
    + [Working with Proto DataStore  | Android Developers](https://developer.android.com/codelabs/android-proto-datastore#0)
4. **Philipp Lackner's Videos on Youtube**
+ [Preferences DataStore in 10min (SharedPreferences deprecated) - YouTube](https://www.youtube.com/watch?v=McnVx7l5awk)



