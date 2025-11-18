# Bratislava Degenerate Lifestyle Agent Pack v2.0

5 custom AI agents for the ambitious, broke, and optimized Bratislava lifestyle.

## What's Inside

| Agent | Use Case |
|-------|----------|
| **Bratislava Cycle God** | Routes, trails, KOM hunting, cheap maintenance, post-ride beers |
| **Mushroom Trip DJ** | Phase-by-phase playlists for psychedelic journeys |
| **Slovak Betting Degenerate** | +EV hunting, bonus extraction, bankroll management |
| **Unemployed Bratislava Chad Optimizer** | Daily schedules, 200€/month nutrition, nootropics, cheap dates |
| **Psychedelic Integration Coach** | Post-trip processing, shadow work, insight-to-action |

---

## Quick Start

### For ChatGPT Custom GPTs
1. Go to ChatGPT → Explore → Create a GPT
2. Open `json/[agent-name].json`
3. Copy `system_prompt` value into "Instructions"
4. Copy `conversation_starters` into the conversation starters field
5. Name your GPT and add a profile picture

### For Claude Projects
1. Go to Claude → Projects → Create Project
2. Copy the `system_prompt` from JSON or markdown file
3. Paste into "Custom Instructions"
4. Start chatting

### For Platforms with Token Limits
Use the `/lite/` versions — same personality, 70% smaller footprint.

---

## File Structure

```
agents/
├── 01-bratislava-cycle-god.md       # Full prompt + examples
├── 02-mushroom-trip-dj.md
├── 03-slovak-betting-degenerate.md
├── 04-unemployed-chad-optimizer.md
├── 05-psychedelic-integration-coach.md
│
├── json/                            # Structured for easy import
│   ├── 01-bratislava-cycle-god.json
│   ├── 02-mushroom-trip-dj.json
│   ├── 03-slovak-betting-degenerate.json
│   ├── 04-unemployed-chad-optimizer.json
│   └── 05-psychedelic-integration-coach.json
│
├── lite/                            # Compressed prompts (~500 tokens each)
│   ├── 01-bratislava-cycle-god-lite.txt
│   ├── 02-mushroom-trip-dj-lite.txt
│   ├── 03-slovak-betting-degenerate-lite.txt
│   ├── 04-unemployed-chad-optimizer-lite.txt
│   └── 05-psychedelic-integration-coach-lite.txt
│
├── resources/                       # Practical templates & tools
│   ├── cycle-god-segments-and-routes.md
│   ├── trip-dj-playlist-templates.md
│   ├── chad-optimizer-templates.md
│   └── integration-coach-journal-prompts.md
│
├── CUSTOMIZATION-GUIDE.md           # Fork for your city
└── README.md
```

---

## What's in Each Format

### Full Markdown (`.md`)
- Complete system prompt
- 4 example conversations
- All knowledge domains detailed
- Best for: learning how agents work, using as reference

### JSON (`.json`)
- Structured system prompt
- Conversation starters
- Config section (location, currency, etc.)
- Related agents cross-references
- Best for: importing into platforms, programmatic use

### Lite (`.txt`)
- Core personality and knowledge compressed
- ~500 tokens vs ~2000 for full
- Best for: platforms with token limits, API cost optimization

### Resources
- **Cycle God:** Strava segments, route templates, GPX waypoints, beer spots
- **Trip DJ:** Phase-by-phase Spotify playlist templates, emergency music
- **Chad Optimizer:** Budget tracker, job application tracker, meal plans, nootropic protocol
- **Integration Coach:** 50 structured journal prompts by timeline

---

## v2.0 Improvements

### Format
- ✅ JSON exports with conversation starters
- ✅ Lite versions for token-limited platforms
- ✅ Separated resources/templates

### Content
- ✅ Stronger betting guardrails (session limits, red flag detection, help resources)
- ✅ Cross-references between agents
- ✅ Location parameterization for forking

### Practical Tools
- ✅ Actual Strava segment targets
- ✅ Copy-paste Spotify playlist templates
- ✅ Budget tracking spreadsheet templates
- ✅ 50 structured integration journal prompts

---

## Customization

See `CUSTOMIZATION-GUIDE.md` for detailed instructions on forking for your city.

Quick version:
1. Find-replace: Bratislava → Your City, Slovakia → Your Country, EUR → Your Currency
2. Replace local-specific sections (routes, shops, bookmakers, etc.)
3. Scale budget numbers for your cost of living

---

## Disclaimers

- **Betting Agent:** Gambling carries serious addiction risk. Includes guardrails and help resources, but use responsibly. Never bet more than you can afford to lose.
- **Trip DJ & Integration Coach:** Harm reduction information only. Always research substances, test materials, and prioritize safety. Not medical advice.
- **All Agents:** AI assistants with creative personalities. Verify critical information independently.

---

## Safety Resources

**Gambling:**
- Slovakia: OLÚP - 02/5341 4111
- International: gamblersanonymous.org

**Psychedelic Support:**
- MAPS Integration: maps.org/integration
- Fireside Project: 62-FIRESIDE
- Crisis: Your local emergency services

---

Built with care for the funemployed chads of Bratislava.

*v2.0 — Now with 100% more templates and 50% less bullshit.*
