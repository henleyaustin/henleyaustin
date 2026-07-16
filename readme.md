# Hey, I'm Austin

I'm a software developer specializing in the **.NET / Angular** stack.

Most of my recent GitHub projects are personal explorations or apps I'm actively developing privately, so they aren't fully open-source. I enjoy building small products to experiment with new stacks, APIs, and architectural approaches outside my day-to-day work.

Below are a few of the projects I've built and some of the engineering challenges or lessons that came out of them.

If you're interested in any of these projects or want to chat about implementation details, feel free to reach out. I'm always happy to talk through code or share what I'm working on.

---

# Recent Personal Projects

## Vinyl Router
Route your turntable's audio through your PC to any speaker or Google Cast group, with live song identification and album art.

**Tech Stack:** C# / WPF (.NET 8), NAudio, Google Cast protocol

### Challenges / Lessons
- Built a **single-capture audio pipeline** where one WASAPI stream fans out to playback, level meters, song fingerprinting, and casting at the same time.
- Implemented **native Google Cast output** by discovering devices over mDNS and hosting a local HTTP server that streams live audio, so no virtual audio driver is needed.
- Integrated **Shazam-style audio fingerprinting** (FFT and spectral peak extraction) with self-imposed rate limiting against an unofficial API.
- Hand-rolled a **custom WPF dark theme** with control templates instead of using a UI library, and learned more about WPF's quirks than I ever planned to.

🔗 https://github.com/henleyaustin/VinylRouter

---

## Roulette Together
Add options to a spinning wheel and let chance decide.

### Modes
- **Spin Alone** – Add items and spin the wheel locally.  
- **Spin Together** – Create or join a lobby where multiple users can suggest and veto items before spinning.  
- **Prize Picker** – Randomly select winners and assign prizes for raffles or giveaways.

**Tech Stack:** React, Firebase Realtime Database

### Challenges / Lessons
- Implemented **real-time multiplayer state syncing** using Firebase's realtime database.
- Designed a **simple lobby system** where users could join sessions and collaboratively edit the wheel contents.
- Learned a lot about **frontend state synchronization in multiplayer scenarios**.

🔗 https://roulettetogether.com

---

## EncoreScout
Search for the closest tour stops of your favorite bands.

**Tech Stack:** Next.js, PostgreSQL, Google Maps API, Ticketmaster API

### Challenges / Lessons
- Integrated the **Google Maps platform** for geolocation and distance calculations.
- Pulled tour data from the **Ticketmaster API** and normalized results for searching and filtering.
- Implemented **query caching and request throttling** to avoid excessive third-party API usage.
- Focused heavily on **cost optimization**, since map and ticket APIs can get expensive quickly.

🔗 https://www.encorescout.com

---

**Feel free to reach out anytime!**
