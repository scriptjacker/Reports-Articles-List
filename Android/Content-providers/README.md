### If you think its exported or vulnerable then simply try to access it and same with other components and then create a PoC app and done :)

#### There can be android:grantUriPermissions="true" also other then exported. If exported=flase stil we can take advantage of granturi

grantUriPermissions - This indicates that any third-party entity can still gain temporary read/write access to the content provider's data.


**1.** Misconfigured Content Provider leads steal cookie and download malicious file  - https://hackerone.com/reports/876192

2. Client all request response leakage - https://hackerone.com/reports/56002

3. Query content provider expose passwrod hashed - https://hackerone.com/reports/242727 (content query --uri content://org.app/path)

4. SQLi using drozer in vulnerable content providers - https://hackerone.com/reports/291764 (run scanner.provider.injection -a com.app.client)

5. File disclosure via contet provider - https://hackerone.com/reports/534541

6. SQLi in content provider - https://hackerone.com/reports/1650264

7. Exploitation of exported content provider to ATO - https://medium.com/@ahmedelmorsy312/unsecure-content-provider-led-to-account-takeover-1e45d716bd7c

8. Steal wifi password via exported - https://vishwarajbhattrai.wordpress.com/2020/08/16/disclosing-wifi-password-via-content-provider-injection-in-xiaomi/

**9.** Gaining contorl on protected content provider (exported=false) - https://blog.mzfr.me/posts/2021-06-24-unexported-component/ 

**10.** Content provider exploitation ways - https://wiki.mzfr.me/Android/Content_Providers/ (NICE)

11. SQLi and info disclosure via content provider - https://meetcyber.net/150-bug-bounty-sql-injection-in-nextcloud-android-content-provider-87bda01ea633
