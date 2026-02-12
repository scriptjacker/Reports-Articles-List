### If you think its exported or vulnerable then simply try to access it and same with other components and then create a PoC app and done :)

**1.** Misconfigured Content Provider leads steal cookie and download malicious file  - https://hackerone.com/reports/876192

2. Client all request response leakage - https://hackerone.com/reports/56002

3. Query content provider expose passwrod hashed - https://hackerone.com/reports/242727 (content query --uri content://org.app/path)

4. SQLi using drozer in vulnerable content providers - https://hackerone.com/reports/291764 (run scanner.provider.injection -a com.app.client)

5. File disclosure via contet provider - https://hackerone.com/reports/534541

6. SQLi in content provider - https://hackerone.com/reports/1650264

7. Exploitation of exported content provider to ATO - https://medium.com/@ahmedelmorsy312/unsecure-content-provider-led-to-account-takeover-1e45d716bd7c
