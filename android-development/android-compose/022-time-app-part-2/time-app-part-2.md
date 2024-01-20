---
id: time-app-part-2
title: Time App Part 2
---
GitHub Repo: **Private**

![[time-app-part-2.mp4|300]]
**Description**: The continuation of the previous [Time App Part 1](/android-development/android-compose/time-app-part-1), not much addition in here, just a timer. The timer is a foreground service which persist when app is in background even if app is closed. There are two approach to achieve this, one is through the use of broadcast receiver that receive intent from service and send it to activity and pass it down to composable.

I didn't use this approach because it's kinda complicated, instead I made a live data inside the service and observe it from composable by `observeAsState()`, it is much easier than the broadcast approach. I observed all the necesarry information to make composable aware even after app is closed such as `isTimerRunning`, `remainingTimer`, `totalDuration`.

---
**What I used** :
- Foreground Service
- MutableLiveData & `observeAsState()`
- CountdownTimer
- `animateFloatAsState()`
---
**What I did/made/learned** :
- Learned more about foreground service and notification
- Even though I didn't take the broadcast approach, I became more comfortable using broadcast receiver
including sending and receiving data by intent from service to broadcast to activity.
- Learned how to use CountdownTimer
- Appreciated live data more
---
System Design : **None**
UI Design : **None**