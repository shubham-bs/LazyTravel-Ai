<h1 align="center">LazyTravel Ai</h1>

<p align="center">
  <img src="https://img.shields.io/badge/status-in%20progress-f59e0b.svg" alt="Status">
  <a href="https://github.com/KalyanM45/TravelBrain-Multi-Agent-AI-Travel-Planner/issues"><img src="https://img.shields.io/github/issues/KalyanM45/TravelBrain-Multi-Agent-AI-Travel-Planner.svg" alt="GitHub Issues"></a>
  <a href="https://github.com/KalyanM45/TravelBrain-Multi-Agent-AI-Travel-Planner/pulls"><img src="https://img.shields.io/github/issues-pr/KalyanM45/TravelBrain-Multi-Agent-AI-Travel-Planner.svg" alt="GitHub Pull Requests"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-GPL--3.0-blue.svg" alt="License"></a>
</p>

---

<p align="center"> A multi-agent AI travel planner. Describe the trip you want in
    plain English and get back flights, hotels, weather and a day-by-day
    itinerary — researched for you in about a minute.
    <br>
</p>

## 📝 Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Usage](#usage)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [Authors](#authors)
- [Acknowledgements](#acknowledgement)

## 🧐 About <a name = "about"></a>

Planning a trip usually means juggling half a dozen browser tabs — one for flights, another for hotels, a third for the weather, and a notes app where you try to fit it all into a sensible order. LazyTravel collapses that into a single conversation. You describe the trip you want in your own words, the way you'd describe it to a friend — *"Plan a 10 day Europe trip from India in April, mid-range budget"* — and a team of AI specialists goes and researches it. One looks into flights, another finds places to stay, another checks what the weather will be doing while you're there. Their findings are then pulled together into a single plan you can actually act on, complete with a day-by-day schedule and a cost estimate. The result is a trip plan in about a minute, rather than an afternoon of research. Each part of the trip gets its own attention:

| | |
|---|---|
| ✈️ **Flights** | Likely airports, airlines on the route, typical duration and fare range |
| 🏨 **Hotels** | Accommodation options matched to your destination and budget |
| 🌤️ **Weather** | Current conditions and the forecast, with travel advice |
| 🗺️ **Itinerary** | A realistic day-by-day plan you can actually follow |
| 💰 **Budget** | An estimated breakdown of what the trip will cost |

Plans are saved as you go, so you can reopen a trip later and ask follow-up
questions without starting over.

## 🏁 Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your
local machine.

### Prerequisites

You'll need the following before you start:

- **Python 3.11**
- **[uv](https://docs.astral.sh/uv/)** — used to install dependencies
- **A PostgreSQL database** — a free [Render](https://render.com/) instance works fine
- **API keys** from the services below. All of them have free tiers:
  - [Groq](https://console.groq.com/)
  - [Tavily](https://tavily.com/)
  - [AviationStack](https://aviationstack.com/)
  - [OpenWeather](https://openweathermap.org/api)

