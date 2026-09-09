# Jean E. Brink Pool — Aquatics page (Pool Relay calendar)

A replica of the City of Pacifica Aquatics page with the static weekly schedule image
replaced by the live [Pool Relay](https://www.poolrelay.com) calendar for the Jean E. Brink Pool.

**This is not an official City of Pacifica website.** It is an unofficial demonstration copy.
The page text and photos come from the city's Aquatics page:
<https://www.cityofpacifica.org/departments/parks-beaches-recreation/aquatics>

For official schedules, fees, and closures, see the city page above or call the pool front desk
at 650-738-7460.

## What is different from the city page

- The weekly schedule image is replaced by an embedded Pool Relay calendar, which updates itself
  as the pool's schedule changes.
- The typed-out swim hours and the full-day and part-day closure lists are gone. The calendar
  already shows both: closed days appear empty, and part-day changes appear as the event that
  replaces the usual session.
- The city seal in the header is a CSS placeholder rather than the city's mark.
- Navigation links are inert placeholders.

## Local preview

```
python3 -m http.server 8777
```

Then open <http://localhost:8777/>.

## Files

- `index.html` — the whole page, styles inline.
