# E-bike Savings Tracker 🚲

A tiny, single-file front end to show my dad how much money he still needs to save up for his electric bike.

That's it. That's the whole project.

## Why does this exist?

I didn't know where else to host something this simple without paying for hosting 😂, so it's just a plain HTML file. No build step, no server, no dependencies — open it in a browser and it works.

## How it works

- `ebike_savings.html` displays three numbers: how much has been saved, the goal, and how much is still needed — plus a progress bar.
- All the logic lives in a small `<script>` block at the bottom of the file. It calculates the remaining amount and the percentage automatically from just two numbers.

## How to update it

Whenever more money gets saved, open `ebike_savings.html` in any text editor and update these two lines near the bottom of the file:

```javascript
const saved = 100;   // <-- how much money has been saved so far (euros)
const goal  = 4000;  // <-- total goal (euros)
```

Save the file, refresh the page, done. Everything else (amounts, percentage, progress bar) updates on its own.

## How to view it

Just double-click `ebike_savings.html` to open it in a browser. Works on desktop and mobile (the layout adjusts automatically on smaller screens).

## Goal

🎯 €4,000 for the e-bike. Every euro saved gets us closer.
