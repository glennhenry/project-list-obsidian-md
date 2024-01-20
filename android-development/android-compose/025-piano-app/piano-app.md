---
id: piano-app
title: Piano App
---
GitHub Repo: **Private**

![[piano-app.mp4|300]]
**Description**: Second out of four project to learn about Media API in Android.
In this project, neither I used Media3 or MediaPlayer the native media API. It was quite simple, a piano app that supposed to load audio using `SoundPool` and then cache it somewhere.

The first time audio is played, it experienced few seconds delay. One way to optimize is to preload all the audio. Preloading will obviously help reducing the time it takes to play for the first time. However, the main issue is the playback, which is the most crucial for user. Even after caching it, still experiences some delay (or maybe because it's a debug mode).

The UI component used to make the piano is native jetpack compose, without any external assets. I tried to make the piano notes UI myself, but it didn't work, ended up opening a question in Stack Overflow.

The audio used for the actual playback was taken from some free sound website, it may sound slightly different from each other.

---
**What I used** :
- Custom Layout
- SoundPool
---
**What I did/made/learned** :
- Learned how to quickly play relatively small or short audio file using SoundPool
- Learned how to make custom layout (custom measure and placement)
---
System Design : **None**
UI Design : **None**