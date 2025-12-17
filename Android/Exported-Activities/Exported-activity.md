#### Only exported activity dosen't make it vulnerable, but it get vulnerable id there is some misconfiguration too!

##### CWE-926: Improper Export of Android Components

##### Almost every bug will be related to Android Manifest.xml and .Java file


1. Steal protected files via Exported Activity - https://hackerone.com/reports/377107 (In AndroidManifest.xml File)

2. XSS via exported activity true - https://hackerone.com/reports/189793 (In AndroidManifest.xml and .Java)

3. Theft of arbitrary files - https://hackerone.com/reports/288955 (In AndroidManifest.xml and .Java)

4. Open Redirect/XSS via exported activity - https://hackerone.com/reports/283058

5. XSS in exported ImageViewerActivity - https://hackerone.com/reports/283063 

6. Theft of arbitrary file - https://hackerone.com/reports/1094702

**7.** Universal XSS in webview via exported activity - https://hackerone.com/reports/1455987

