# Electric Dance Affair Website

Static GitHub Pages site at electric-dance-affair.de.

## Events

Events live in `events.json`, rendered by JS in `index.html`. Max 10 visible, rest behind toggle button.

Adding an event — prepend to the array:
```json
{
  "date": "DD.MM.YYYY",
  "name": "Event Name",
  "meta": "Genre · Uhrzeit · Eintritt",
  "link": "https://www.instagram.com/...",
  "location": "Venue, Stadt"
}
```
Only `date` and `name` are required.

## Deployment

Push to `main` → GitHub Pages auto-deploys. Remote uses SSH alias `github.com-eda` (account: electricdanceaffair).

## Language

Communicate in German with the user. Site content is German.
