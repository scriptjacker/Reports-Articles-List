##### R/W in external or internal storage
##### sensitive data in logs
##### sensitive data via notification
##### sensitive data via clipboard
##### sensitive data in Internal Storage

**1.** WebView storing third party info in plain text - https://hackerone.com/reports/44727 (In /data/data/co.app_name.android/databases/db_name.db)

2. App stores data using binary sqlite database - https://hackerone.com/reports/57918

**3.** Insecure storage leads download cookie - https://hackerone.com/reports/876192

**4.** Leaked password in Shared Preferences - https://www.rapid7.com/blog/post/2024/01/03/genie-aladdin-connect-retrofit-garage-door-opener-multiple-vulnerabilities/ (In /data/data/com.eg/shared_prefs/com.eg.MainActivity.xml)

**5.** JWT in shared preference - https://medium.com/@AlQa3Qa3_M0X0101/how-i-was-able-to-get-account-takeover-via-insecure-data-storage-and-webview-with-exported-activity-5308a330ab80 ( In data/data/com.redirect.app/shared_prefs/OK_PREF.xml)
