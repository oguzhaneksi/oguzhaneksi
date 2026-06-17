# Hi, I'm Oğuzhan 👋

Android engineer specialising in **video streaming** — HLS/DASH, Media3/ExoPlayer, DRM/Widevine, and QoE analytics. After years of debugging playback issues the slow way (Charles Proxy + manual logcat + manifest inspection by hand), I started building tools that make the invisible visible.

Currently freelancing — open to Android contract and senior full-time roles.

📍 Dubai, UAE · [Medium](https://medium.com/@ouzhaneki) · [LinkedIn](https://www.linkedin.com/in/oguzhan-eksi-185ab4130/) · [X](https://x.com/oguzhaneksi97)

---

## 🔬 Open Source

### [StreamProbe](https://github.com/oguzhaneksi/StreamProbe)
Real-time HLS/DASH debug overlay for Android — manifests, segment metrics, CDN headers, ABR decisions, all on-screen without touching your production build.

[![Maven Central](https://img.shields.io/maven-central/v/io.github.oguzhaneksi/streamprobe?label=Maven%20Central)](https://central.sonatype.com/search?q=io.github.oguzhaneksi)

```kotlin
debugImplementation("io.github.oguzhaneksi:streamprobe:<latest>")
```

**Why it exists:** Charles Proxy works, but takes 20+ minutes to set up every session. StreamProbe pulls the full debug workflow — manifests, segment timing, CDN cache, ABR switches — directly into the app.

---

### [Media3Watch](https://github.com/oguzhaneksi/Media3Watch)
QoE analytics SDK for Media3 — startup time, stall events, and session summaries in Logcat + optional self-hosted Grafana dashboard (Ktor + PostgreSQL + Docker).

[![Maven Central](https://img.shields.io/maven-central/v/io.github.oguzhaneksi/media3watch-sdk?label=Maven%20Central)](https://central.sonatype.com/artifact/io.github.oguzhaneksi/media3watch-sdk)

```kotlin
implementation("io.github.oguzhaneksi:media3watch-sdk:1.1.0")
debugImplementation("io.github.oguzhaneksi:media3watch-overlay:1.1.0")
```

**Why it exists:** Crash logs don't explain poor playback UX. Media3Watch tracks what users actually experience.

---

### [TikTokCompose](https://github.com/oguzhaneksi/TikTokCompose) · ⭐ 26
Shorts/Reels-style vertical video feed — Media3 + Jetpack Compose reference architecture for paged video playback.

### [AndroidTvCompose](https://github.com/oguzhaneksi/AndroidTvCompose) · ⭐ 7
Self-initiated Android TV app built with Jetpack Compose — R&D side project that shipped to production.

---

## 🚀 Currently building

- **StreamProbe KMP Migration** — Real-time HLS/DASH debug overlay for Kotlin Multiplatform (Android, iOS).

---

## ✍️ Writing

- [Building a Local-First Native Video Analytics SDK for Android Media3](https://medium.com/@ouzhaneki)
- [Basic background playback with Media3 MediaSessionService](https://medium.com/@ouzhaneki)
- [Android MediaSession nedir? Nasıl kullanılır?](https://medium.com/@ouzhaneki)
- [Jetpack Media3 Nedir?](https://medium.com/@ouzhaneki)

👉 [medium.com/@ouzhaneki](https://medium.com/@ouzhaneki)

---

## 📊 Stats

<p align="left">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=oguzhaneksi&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" />
  <img height="165" src="https://streak-stats.demolab.com?user=oguzhaneksi&theme=tokyonight&hide_border=true" />
</p>

---

## 🌍 Connect

- LinkedIn: [Oğuzhan Ekşi](https://www.linkedin.com/in/oguzhan-eksi-185ab4130/)
- X: [@oguzhaneksi97](https://x.com/oguzhaneksi97)
- Medium: [@ouzhaneki](https://medium.com/@ouzhaneki)
