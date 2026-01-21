This will include bugs related to misconfiguration and leaked firebase file.

Try replacing firebase.io with appspot.com as applications also use that.

#### This can be find in `res/values/strings.xml` or file google-services.json and can search for firebaseio or firebase.io or firebase or firebase_database in that file or in the app after reversing the code.

1. *Firebase* DB takeover - https://hackerone.com/reports/1065134 (In strings.xml)

2. Firebase DB Takover - https://hackerone.com/reports/684099 (In strings.xml)

3. Firebase DB Exposed - https://hackerone.com/reports/731724 

4. Firebase DB misconfigured - https://omespino.com/write-up-private-bug-bounty-firebase-database-exposed-by-misconfiguration-2000-usd/

5. Firebase DB *Exploitation* - https://blog.securitybreached.org/2020/02/04/exploiting-insecure-firebase-database-bugbounty/

6. https://medium.com/@secshubhamsharma/bug-hunting-101-the-firebase-misconfig-that-earned-me-a-bounty-dd600cef8ade

7. *Firebase DB Enumeration & Ways* - https://raw.githubusercontent.com/sahad-mk/FireVu/master/Documents/Misconfigured%20Firebase%20Database.pdf (NICE ONE)

8. *Firebase DB Enumeration & Ways (FIRESTORE)* - https://medium.com/@mustafamohammed789mm/firebase-misconfigurations-from-discovery-to-exploitation-0a282b81ad4f
