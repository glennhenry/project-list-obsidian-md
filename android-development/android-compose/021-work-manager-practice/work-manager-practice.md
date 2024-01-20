---
id: work-manager-practice
title: Work Manager Practice
---
GitHub Repo: **Private**

![[work-manager-practice.mp4|300]]
**Description**: Toy app made to learn how to use WorkManager API. The first one is to use work manager to do potentially long background task (image processing), this includes opening image, actual processing, and saving the image. 

The second is a reminder, it sends a notification every 15-20 minutes. The notification is supposed to be an important one. In real case, in may works like an alarm.

The third is made to simulate a data synchronization with server, although it is just local state. After making the third example, I realized that the example was too oversimplified that using WorkManager doesn't make sense.

---
**What I used** :
- WorkManager
- File Manipulation & Bitmap API
- Notification API
---
**What I did/made/learned** :
- Learned how to use WorkManager for one time, periodic, and unique request
- Became more comfortable doing file manipulation and also editing images.
---
System Design (application flow) :

![[work-manager-practice-image-processing-flow.png|600]]
![[work-manager-practice-update-data-flow.png|500]]
UI Design : **None**