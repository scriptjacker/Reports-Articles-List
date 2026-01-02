#### Only exported activity dosen't make it vulnerable, but it get vulnerable id there is some misconfiguration too!

##### CWE-926: Improper Export of Android Components

##### Almost every bug will be related to Android Manifest.xml and .Java file

##### Activities listed in &lt;intent-filter&gt; in androidmanifest.xml is consider exported by default and no need to be set as explicitly set android:exported="true" 


1. Steal protected files via Exported Activity - https://hackerone.com/reports/377107 (In AndroidManifest.xml File)

2. XSS via exported activity true - https://hackerone.com/reports/189793 (In AndroidManifest.xml and .Java)

3. Theft of arbitrary files - https://hackerone.com/reports/288955 (In AndroidManifest.xml and .Java)

4. Open Redirect/XSS via exported activity - https://hackerone.com/reports/283058

5. XSS in exported ImageViewerActivity - https://hackerone.com/reports/283063 

6. Theft of arbitrary file - https://hackerone.com/reports/1094702

**7.** Universal XSS in webview via exported activity - https://hackerone.com/reports/1455987

**8.** Exported activites allow load internal webview leads cookie stealing - https://hackerone.com/reports/532836 

**9.** Access to andorid any protected component - https://hackerone.com/reports/200427 (Intents)

10. Private application files can be uploaded/downloaded - https://hackerone.com/reports/375083

11. Malicious URL parse via exported activity WebView - https://hackerone.com/reports/694053

**12.** Exported Acitvity accept malicious Intent URI - https://hackerone.com/reports/537670

**13.** Theft of protected files by exported activity - https://hackerone.com/reports/1454002

**14.** Exported Acivity allow to save things - https://infosecwriteups.com/exploiting-activity-in-medium-android-app-e2e6f3553eef

**15.** ATO & XSS via Exported Activity and Webview - https://medium.com/@AlQa3Qa3_M0X0101/how-i-was-able-to-get-account-takeover-via-insecure-data-storage-and-webview-with-exported-activity-5308a330ab80

16. Exported activity is true - https://hackerone.com/reports/1455987

**17.** Exported Activity in webview leads XSS and steal JWT chainig - https://medium.com/@AlQa3Qa3_M0X0101/how-i-was-able-to-get-account-takeover-via-insecure-data-storage-and-webview-with-exported-activity-5308a330ab80
