---
id: steganography
title: Steganography
---
GitHub Repo: **Private**

![[steganography-1.png|300]]
![[steganography-2.png|300]]
![[steganography-3.png|300]]
![[steganography-4.png|300]]
**Description**: While learning Kotlin, I tried to make a [steganography app](https://hyperskill.org/projects/160), although I failed. I decided to try again by making it in android app.

The app will takes image and string message. Message will be turned into bytes and will be hidden in the image by manipulating least significant bit of the blue color. It will also create some breakpoint as end of message indicator.

After manipulating image, it will make a copy of the image with message hidden in it.
The app will read message hidden in image if the image actually has hidden message in it. In real scenario, this app probably won't work fine in some cases. As it always checks in the 100th pixel if it's breakpoint or not. The problem is there could be a pixel where it's color is same as the breakpoint, this can make the app mistakenly think that it has hidden message and will show some random character.

---
**What I used** :
- Android Image Bitmap API
---
**What I did/made/learned** :
- Learned more about image and bitmap in Android
- Learned how to manipulate image
- Learned about least significant bit
---
System Design: **None**
UI Design: **None**