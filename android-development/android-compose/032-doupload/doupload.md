---
id: doupload
title: Doupload
---
GitHub Repo: **Private**

![[doupload.mp4|300]]
**Description**: Second app to learn more about networking stuff in Android. It's an app that supposed to see/download/upload on a server. The server is made by myself using Ktor, the server is quite simple, it can write file to local system and transmit whatever files it has.

The download functionality works as expected nicely, however, the upload functionality is not. I can seamlessly upload using Retrofit client, but the server receives meaningless `NUL` value. It seems like the server fail to read the multipart request or the Retrofit client mess something up.

---
**What I used** :
- Retrofit HTTP Client
- Ktor server
- DownloadManager
---
**What I did/made/learned** :
- Learned how to use DownloadManager class
- Learned more about Ktor server to parse upload multipart and download request
- Learned how to upload using retrofit
---
System Design : **None**
UI Design : **None**