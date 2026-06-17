# Hi, I'm Oğuzhan 👋

6 years building Android, the last few deep in OTT video: HLS/DASH delivery, Media3/ExoPlayer, DRM/Widevine, and QoE analytics.

Here's the thing though: debugging a streaming issue the conventional way means Charles Proxy + adb logcat + manually fetching the manifest in a browser. All at the same time. On a tethered device. Each round takes 15–30 minutes. I got tired of that, so I started building tools to pull that whole workflow into the app itself, then shipped them to Maven Central.

Currently freelancing. Open to Android contract and senior full-time roles.

📍 Dubai, UAE · [Medium](https://medium.com/@ouzhaneki) · [LinkedIn](https://www.linkedin.com/in/oguzhan-eksi-185ab4130/) · [X](https://x.com/oguzhaneksi97)

---

## 🔬 Open Source

### [StreamProbe](https://github.com/oguzhaneksi/StreamProbe)
Real-time HLS/DASH debug overlay for Android. Manifests, segment metrics, CDN headers, and ABR decisions: all on-screen, no Charles Proxy, no tethered device, no production risk.

[![Maven Central](https://img.shields.io/badge/Maven%20Central-available-brightgreen?logo=apache-maven)](https://central.sonatype.com/search?q=io.github.oguzhaneksi+streamprobe)

```kotlin
debugImplementation("io.github.oguzhaneksi:streamprobe:<latest>")
```

---

### [Media3Watch](https://github.com/oguzhaneksi/Media3Watch)
QoE analytics SDK for Media3. Crash logs tell you something broke. They don't tell you a user sat through an 8-second startup time. Media3Watch tracks startup duration, stall count, and buffer health, in Logcat or on a self-hosted Grafana dashboard (Ktor + PostgreSQL + Docker).

[![Maven Central](https://img.shields.io/badge/Maven%20Central-1.1.0-brightgreen?logo=apache-maven)](https://central.sonatype.com/artifact/io.github.oguzhaneksi/media3watch-sdk)

```kotlin
implementation("io.github.oguzhaneksi:media3watch-sdk:1.1.0")
debugImplementation("io.github.oguzhaneksi:media3watch-overlay:1.1.0")
```

---

### [TikTokCompose](https://github.com/oguzhaneksi/TikTokCompose) [![Stars](https://img.shields.io/github/stars/oguzhaneksi/TikTokCompose?style=flat&logo=github&label=%E2%AD%90&color=2b3137&labelColor=2b3137)](https://github.com/oguzhaneksi/TikTokCompose/stargazers)
Shorts/Reels-style vertical video feed. Media3 + Jetpack Compose reference architecture for paged video playback.

### [AndroidTvCompose](https://github.com/oguzhaneksi/AndroidTvCompose) [![Stars](https://img.shields.io/github/stars/oguzhaneksi/AndroidTvCompose?style=flat&logo=github&label=%E2%AD%90&color=2b3137&labelColor=2b3137)](https://github.com/oguzhaneksi/AndroidTvCompose/stargazers)
Self-initiated Android TV app built with Jetpack Compose. R&D side project only.

---

## 🚀 Currently building

- **StreamProbe KMP Migration:** Real-time HLS/DASH debug overlay for Kotlin Multiplatform (Android, iOS)

---

## ✍️ Writing

- [What is Android MediaSession and How to Use It?](https://medium.com/@ouzhaneki/what-is-android-mediasession-and-how-to-use-it-3cf911c74b77) · Apr 2026
- [From Alpha to Almost-Production: Building Media3Watch (Part 2)](https://medium.com/@ouzhaneki/from-alpha-to-almost-production-building-media3watch-part-2-5c60cebebfcc) · Mar 2026
- [Building a Local-First Native Video Analytics SDK for Android Media3](https://medium.com/@ouzhaneki/building-a-local-first-native-video-analytics-sdk-for-android-media3-117c3cf77baa) · Feb 2026
- [Basic Background Playback with Media3 MediaSessionService](https://medium.com/@ouzhaneki/basic-background-playback-implementation-with-media3-mediasessionservice-4d571f15bdc2) · Dec 2023

👉 [medium.com/@ouzhaneki](https://medium.com/@ouzhaneki)

---

## 📊 Stats

<p align="left">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=oguzhaneksi&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" />
  <img height="165" src="https://streak-stats.demolab.com?user=oguzhaneksi&theme=tokyonight&hide_border=true" />
</p>

---

Open to interesting streaming and Android problems. Easiest to reach me on [LinkedIn](https://www.linkedin.com/in/oguzhan-eksi-185ab4130/) or [X](https://x.com/oguzhaneksi97).
