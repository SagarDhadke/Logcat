
# Logcat

How to use Logcat in Android Studio.


## Debugging All Types

To run this project, you will need to add the following environment variables to your .env file

`DEBUG:` Used for debugging messages

`INFO:` Used for general information messages

`WARN:` Used for warning messages

`ERROR:` Used for error messages

`ASSERT:` Used for critical errors that may cause the app to crash



## All Logs

Log.v

```bash
Log.v(tag, message): Logs a verbose message
```

Log.d

```bash
  Log.d(tag, message): Logs a debug message
```

Log.i

```bash
 Log.i(tag, message): Logs an informational message.
```

Log.w

```bash
  Log.w(tag, message): Logs a warning message,
```

Log.e

```bash
  Log.e(tag, message): Logs an error message,
```

Log.wtf

```bash
 Log.wtf(tag, message): Logs an assertion failure message
```


