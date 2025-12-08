### In this we gonna talk abut breaking the encryption.

##### Some mobile or web apps encrypt their network traffic on the client side using AES, with a hardcoded key and IV (Initialization Vector).
##### Because the key and IV are hardcoded (i.e. embedded in the app code) not dynamically generated per user. An attacker who obtains the app binary (or intercepts traffic) can decrypt or re-encrypt traffic themselves. This allows the attacker (or pentester) to intercept, modify, and re-send requests/responses as if they were the legitimate client, even if the traffic is “encrypted”.

**1.** Hardcoded *key and IV* break *AES* Encryption - https://blog.dixitaditya.com/manipulating-aes-traffic-using-a-chain-of-proxies-and-hardcoded-keys (In .java & native)

**2.** leaked *API* key & enryption (AES) - https://emptynebuli.github.io/tooling/2021/03/22/rustyiron.html (In .java file)

3. Token Accessable in Request Header & IV & AES - https://www.vaadata.com/blog/insecure-authentication-tokens-leading-to-account-takeover/

**4.** Breaking encryption & Chaning - https://ahmdhalabi.medium.com/the-art-of-chaining-vulnerabilities-e65382b7c627 (In .so file, Ghidra/IDA Pro)
