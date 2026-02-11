It can be in many places like `R/W in external or internal storage`, `sensitive data in logs`, `sensitive data via notification`, `sensitive data via clipboard`, `sensitive data in Internal Storage`, `SQLITE DB or Unencrypted DB`, `Sensitive Info in Shared Prefs`, `Hardcoded secrets`.



**1.** WebView storing third party info in plain text - https://hackerone.com/reports/44727 (In /data/data/co.app_name.android/databases/db_name.db)

2. App stores data using binary sqlite database - https://hackerone.com/reports/57918

**3.** Insecure storage leads download cookie - https://hackerone.com/reports/876192

**4.** Leaked password in Shared Preferences - https://www.rapid7.com/blog/post/2024/01/03/genie-aladdin-connect-retrofit-garage-door-opener-multiple-vulnerabilities/ (In /data/data/com.eg/shared_prefs/com.eg.MainActivity.xml)

**5.** JWT in shared preference - https://medium.com/@AlQa3Qa3_M0X0101/how-i-was-able-to-get-account-takeover-via-insecure-data-storage-and-webview-with-exported-activity-5308a330ab80 ( In data/data/com.redirect.app/shared_prefs/OK_PREF.xml)

6. leaked creds in shared prefs - https://medium.com/@tirthshah23/insecure-data-storage-83c35bc0b0b2

7. In shared prefs, sqlite db (Unencrypted database), external storage - https://medium.com/@kushyadav2708/android-application-security-part4-insecure-data-storage-6dee5775b97d

8. In file storage - https://pallabjyoti218.medium.com/android-insecure-file-storage-e770eed9a3fa (/data/data/app/files)

9. In logcat, class - https://medium.com/@princeoffl/exploring-common-vulnerabilities-in-android-insecure-logging-hardcoded-credentials-insecure-data-a3c9e0cb2611
