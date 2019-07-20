# ntlm4okhttp

NT LAN Manager (NTLM) implementation for Okhttp

**Min JDK:** 8

## Announcement

This project is modified from [Android_Ntlm](https://github.com/netcosports/Android_Ntlm), Thanks for Netco Sports.

## Simple usage

```java
OkHttpClient client = new OkHttpClient.Builder()
                .authenticator(new NTLMAuthenticator(userName, password, null))
                .build();
```
