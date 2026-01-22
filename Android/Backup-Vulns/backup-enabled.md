#### In this we gonna talk about backup vulnerabilities

We have to look for `android:allowBackup = "true"` or `android:backup="allow"` or word `backup` in `androidmanifest.xml` 

##### Steps for Exploitation
1. Find backup enabled (If true. so this means that we can backup the app internal data which resides under /data/data/<app-pkg>)
2. Use ADB backup feature to backup data
3. After getting backup convet to TAR using ABE (Android Backup Extractor) https://github.com/nelenkov/android-backup-extractor/releases

.ab extension indicates that it’s an Android Backup File


1. Android Backup enabled & exploit via ADB - https://hackerone.com/reports/12617

2. *Backup Enabled exploitation steps* - https://medium.com/@barrysahya/non-root-android-application-data-extraction-case-study-com-shopee-id-0dc25a33e681

3. *Full Exploitation of backup enabled* - https://vishwarajbhattrai.wordpress.com/2017/07/17/finding-backup-vulnerabilities-in-android-apps/

4. Backup enabled exploitation steps - https://infosecwriteups.com/backup-vulnerabilities-android-mobile-application-187ec3420982
