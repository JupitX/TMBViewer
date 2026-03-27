# TMBViewer 🚌

> A real-time public transport tracker for Barcelona, built on open government data.

---

## 🚧 Project Status: IN PROGRESS

---

## The Story

Ever since I was a kid taking the bus to school, I always wondered the same thing:

**Where is the bus right now?**

Not "it arrives in 4 minutes" — I mean *actually* seeing it move on a map.
There's something psychologically different between watching a countdown timer
and seeing your bus turn the corner in real time. One makes you anxious.
The other gives you control.

Years later, with programming and automation skills, I decided to finally build
what I always wished existed.

---

## What It Does

TMBViewer pulls **open big data provided by the Barcelona city government**
and renders it into a clean, real-time interactive map — showing the actual
position of buses and public transport vehicles across the city, calculated
based on their scheduled arrival times and real traffic data.

Instead of staring at a countdown, you see your bus moving. You see where it is,
how fast it's moving, and whether it's worth running or not.

### Features
| Feature | Description |
|---|---|
| **Live vehicle positions** | Real-time location of buses on an interactive map |
| **Arrival time estimation** | Position calculated from scheduled times and stops |
| **Full route visualization** | See the entire route and all stops at a glance |
| **Friendly UI** | All data represented visually on screen, no raw numbers |
| **Barcelona open data** | Powered by official government big data APIs |

---

## How It Works

The Barcelona city government publishes real-time transit data as open data.
TMBViewer consumes that data, processes it, and translates arrival time
information into geographic coordinates — allowing vehicles to be plotted
on a live map even without direct GPS tracking on every vehicle.

---

## Why This Matters

Public transport apps tell you *when*. TMBViewer tells you *where*.

That difference is small on paper. In practice, it changes how you experience
waiting entirely. Knowing your bus is stuck two blocks away in traffic feels
completely different from watching a timer count down with no context.

TMBViewer is also a demonstration of what's possible with open government
data — Barcelona publishes a wealth of real-time information that very few
people know exists or know how to use.

---

## Tech Stack

| Layer | Technology |
|---|---|
| **Language** | Python |
| **Data source** | Barcelona Open Data API (data.tmb.cat) |
| **Map rendering** | Interactive map visualization |
| **Data processing** | Real-time parsing and coordinate calculation |

---

## Roadmap

- [x] Data ingestion from Barcelona Open Data API
- [x] Arrival time to position calculation
- [ ] Full interactive map UI
- [ ] Multi-line support
- [ ] Mobile-friendly interface
- [ ] Live refresh without page reload

---

## Author

**Jefrey Hernández** — Junior Information Security Engineer
[LinkedIn](https://www.linkedin.com/in/jefrey-hernandez) · [HackTheBox](https://app.hackthebox.com/users/1151098)
