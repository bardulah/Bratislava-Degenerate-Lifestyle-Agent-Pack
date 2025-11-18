# Customization Guide: Adapt for Your City

This pack is built for Bratislava, but the frameworks work anywhere. Here's how to fork it for your location.

---

## Location-Specific Variables

Each agent has these location-dependent elements:

### Cycle God
- **Trails and routes:** Replace Malé Karpaty, Záhorie with your local terrain
- **Beer spots:** Your post-ride culture spots
- **Weather patterns:** Your microclimate rules
- **Bike shops:** Local maintenance options
- **Strava segments:** Your area's KOM targets

### Betting Degenerate
- **Bookmakers:** Replace Tipsport/Niké/Fortuna with legal books in your country
- **Leagues:** Your local leagues that books are soft on
- **Currency:** EUR → your currency
- **Help resources:** Your national gambling helpline

### Chad Optimizer
- **Grocery stores:** Lidl/Kaufland → your budget chains
- **Food prices:** Adjust all € amounts for your cost of living
- **Job platforms:** Profesia.sk → your local job sites
- **Outdoor gyms:** Your free workout locations
- **Supplement sources:** Where to buy cheap in your country

### Integration Coach
- **Professional resources:** Your local psychedelic-informed therapists
- **Integration circles:** Your city's psychedelic society/community

---

## How to Customize

### Step 1: Global Find-Replace

In the JSON or markdown files:

| Find | Replace With |
|------|-------------|
| `Bratislava` | Your city |
| `Slovakia`/`Slovak` | Your country |
| `EUR`/`€` | Your currency |
| `Tipsport`/`Niké`/`Fortuna` | Your local bookmakers |
| `Profesia.sk` | Your job platform |
| `Lidl`/`Kaufland` | Your budget grocery |

### Step 2: Location-Specific Sections

#### Cycle God Sections to Replace:

```
### Routes & Trails
- [Your MTB trails with difficulty ratings]
- [Your gravel routes with surface descriptions]
- [Your road classics with climb profiles]

### Post-Ride Culture
- [Your beer spots ranked by: proximity, quality, bike parking]

### Weather Optimization
- [Your microclimate patterns]
- [Your wind corridors]

### Cheap Bike Maintenance
- [Your local shops ranked by price/quality/speed]
- [Your used parts marketplaces]
```

#### Chad Optimizer Sections to Replace:

```
### Nutrition on [X]€/Month
- [Your local cheap protein: eggs, cottage cheese equivalent, cheap meat cuts]
- [Your grocery store hierarchy]
- [Your reduced-section timing]

### Job Application Strategy
- [Your local job platforms]
- [Your industry-specific sites]
- [Your networking events/locations]

### Cheap Dates & Social Life
- [Your coffee spots]
- [Your parks]
- [Your cheap beer culture]
```

#### Betting Degenerate Sections to Replace:

```
### [Country] Bookmaker Ecosystem
- [Book 1]: Bonus structures, line characteristics, withdrawal speed
- [Book 2]: Same breakdown
- [Book 3]: Same breakdown

### Sports-Specific Angles
- [Your local leagues where books are soft]
- [Sports popular in your country]
```

### Step 3: Adjust Budget Numbers

The Chad Optimizer uses specific budgets. Scale these to your cost of living:

**Bratislava baseline:**
- 200€/month total budget
- 45€/week groceries
- 10€ cheap date

**To adjust:** Calculate the ratio of your city's cost index to Bratislava's (~0.65 of Western Europe) and multiply.

Example for Berlin (1.1 ratio):
- 200€ × 1.1 = 220€/month
- 45€ × 1.1 = 50€/week groceries

Example for Sofia (0.5 ratio):
- 200€ × 0.5 = 100€/month
- 45€ × 0.5 = 22€/week groceries

---

## Agents That Need Less Customization

### Mushroom Trip DJ
- **Works globally** — music is universal
- Only change: local Spotify market availability for some tracks

### Psychedelic Integration Coach
- **Works globally** — psychology is universal
- Change: professional resources section for your country

---

## Template: Customization Checklist

Use this checklist when forking for a new city:

### General
- [ ] City name replaced throughout
- [ ] Country/nationality replaced
- [ ] Currency replaced and amounts scaled

### Cycle God
- [ ] All routes replaced with local equivalents
- [ ] Strava segments researched and added
- [ ] Post-ride spots researched
- [ ] Weather patterns documented
- [ ] Bike shops researched

### Betting Degenerate
- [ ] Legal bookmakers identified
- [ ] Bookmaker characteristics researched
- [ ] Local leagues identified (where books are soft)
- [ ] Gambling helpline updated
- [ ] Legal status verified for your jurisdiction

### Chad Optimizer
- [ ] Grocery stores identified
- [ ] Prices researched and adjusted
- [ ] Job platforms identified
- [ ] Outdoor gym locations found
- [ ] Cheap date spots researched
- [ ] Supplement sources identified

### Integration Coach
- [ ] Professional resources updated
- [ ] Local psychedelic society/community identified (if exists)

---

## Contribution

If you create a solid fork for another city, consider sharing it:
- Keep the same structure
- Document your research sources
- Note what's different about your city's culture

---

## Example Forks to Inspire

If someone creates a quality fork for any of these, I'd feature it:
- Berlin Degenerate Pack
- Prague Degenerate Pack
- Budapest Degenerate Pack
- Vienna Degenerate Pack
- Krakow Degenerate Pack

The Central European optimization lifestyle transcends borders.
