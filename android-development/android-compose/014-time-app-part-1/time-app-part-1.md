---
id: time-app-part-1
title: Time App Part 1
---
GitHub Repo: **Private**

![[time-app-part-1-1.png|300]]
![[time-app-part-1-2.png|300]]
![[time-app-part-1-3.png|300]]
![[time-app-part-1-4.png|300]]
![[time-app-part-1-5.png|300]]
![[time-app-part-1-6.png|300]]
**Description**: The app made to explore about time system on android. Time system includes alarm, timer, world clock timezone, stopwatch, and date time calendar. Because this app is kinda long, I separated it into 2 part. This app is about alarm, world clock, and date time calendar. Learned many things about time in Android with just this half part of the app.

---
**What I used** :
- Kotlin DSL Gradle Migration
- Alarm
	- AlarmManager
    - Ringtone Picker Intent
    	- Time Picker Dialog
- Clock
	- java.util.Timezone
  - Date Picker
    - Date Picker Dialog
  - java.util.Calendar
  - SimpleDateFormat class
- Manual DI
- Multiple Room DB Tables and DAO
- Unmutable StateFlow + stateIn()
- Bottom Nav Bar
---
**What I did/made/learned** :
- Learned how to use Kotlin DSL for migrating `build.gradle`
- Learned how to use alarm manager
- Utilize ringtone picker intent to pick default phone ringtone
- Used material 3 time picker dialog
- Familiarize myself in some java packages
- Checkbox toggle layout
---
System Design: **None**
UI Design: **None**