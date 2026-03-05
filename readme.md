# Hey, I'm Austin

I'm a software developer specializing in the **.NET / Angular** stack.

Most of my recent GitHub projects are personal explorations or apps I'm actively developing privately, so they aren't fully open-source. I enjoy building small products to experiment with new stacks, APIs, and architectural approaches outside my day-to-day work.

Below are a few of the projects I've built and some of the engineering challenges or lessons that came out of them.

If you're interested in any of these projects or want to chat about implementation details, feel free to reach out. I'm always happy to talk through code or share what I'm working on.

---

# Recent Personal Projects

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

## Movie-Go-Round
Upload your watchlists from IMDb or Letterboxd and let the wheel decide what movie you watch next.

**Tech Stack:** Svelte, PostgreSQL

### Challenges / Lessons
- Explored **Svelte’s component model and reactive state**, which makes building the UI pretty lightweight.
- Had to work around the lack of affordable **public APIs for IMDb and Letterboxd**, which required alternative approaches for ingesting user watchlists.
- Built a **custom spinning disc animation** inspired by old burned DVDs, which required a mix of CSS animation and state control.
- Learned a lot about balancing **UX expectations with external data limitations**.

🔗 https://www.movie-go-round.com

---

**Feel free to reach out anytime!**
