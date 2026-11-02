# 🍟 Deepfryer

> **Upload it. Burn it. Download it.**

Deepfryer is a lightweight, frontend-driven web application built with vanilla HTML, CSS, and the native browser **Web Audio API**. It allows users to upload or record audio clips and instantly blast them with a massive 90% hard-clipping distortion and sub-bass blowout—replicating the classic, crushed "deep-fried" meme aesthetic directly in the browser.

🔗 **Live Demo:** [niklas-h1y.github.io/Deepfryer/](https://niklas-h1y.github.io/Deepfryer/)

---

## 🔥 Features

* **Instant Audio Upload:** Drop in any common audio file format (.mp3, .wav, .ogg).
* **Live Recording:** Capture raw microphone input directly through the browser.
* **90% Fry Engine:** Combined serial pipeline utilizing an aggressive 110Hz low-shelf bass multiplier and a 450x sigmoid waveshaping curve for complete wave flattening.
* **Real-time Spectrum Visualizer:** Interactive custom canvas reflecting active playback frequency bands.
* **Local Compilation:** Converts your cooked audio buffers directly into standalone 16-bit PCM WAV files for immediate download.
* **Zero Server Overhead:** Processes everything client-side—no files are ever uploaded to a remote server.

---

## 🛠️ Built With

* **HTML5 & CSS3** – For the dark, visual layout shell.
* **Web Audio API** – Managing real-time `OfflineAudioContext` digital signal processing and sound synthesis.
* **JavaScript (ES6)** – Audio buffer manipulation and binary WAV file rendering.

---

## 🚨 Warning

⚠️ **Do not use this application while wearing headphones.** The processing logic is designed to aggressively compress dynamic range and clip signal volume violently. An automatic safety limiter is included to protect hardware, but user discretion is advised.

---

## 👤 Author

* **Niklas** - [@niklas-h1y](https://github.com/niklas-h1y)
