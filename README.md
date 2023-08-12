# Kotlin App Network Checker

1. copy NetworkChecker.kt in the folder that MainActivity.kt exist and add your package name in the first line of the file.

2. Add this lines in AndroidManifest.xml.

```bash
    <uses-permission android:name="android.permission.INTERNET"/>
    <uses-permission android:name="android.permission.ACCESS_NETWORK_STATE"/>
```
3. Use this Condition for check network.


```bash
    if ( NetworkChecker(this).isInternetConnected ) {
        Toast.makeText(this, "Network is connected", Toast.LENGTH_SHORT).show()
    }else{
        Toast.makeText(this, "Network is not connected", Toast.LENGTH_SHORT).show()

    }
```


   
