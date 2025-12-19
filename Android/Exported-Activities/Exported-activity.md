#### Only exported activity dosen't make it vulnerable, but it get vulnerable id there is some misconfiguration too!

##### CWE-926: Improper Export of Android Components

##### Almost every bug will be related to Android Manifest.xml and .Java file

##### Activities listed in <intent-filter> in androidmanifest.xml is consider exported by default and no need to be set as explicitly set android:exported="true" 


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
