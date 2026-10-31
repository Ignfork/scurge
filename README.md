# Scurge ($SCURGE)

A rough little computer script that puts your SOL to work 24/7. It earns yield, grabs airdrops and rewards, and compounds. It never trades. The site has a 2000s internet look, and the landing page is a hacker terminal wall with monitors running agent tasks.

## Deploy
The site is a single `index.html` with no folders and no build step. Drop it into a GitHub repo or Vercel.

## Settings
Open `index.html` and find `CONFIG` near the top of the script:

```js
var CONFIG={xUrl:'',ca:'',buyUrl:'',chartUrl:''};
```

Fill in your X link, contract address, buy link and chart link. Until the CA is set, the page says "CA drops on X at launch".

## What's on the page
- **Terminal wall:** a main terminal with the animated Scurge, typed commands and a live clock, surrounded by 8 monitors running tasks (yield, airdrop scan, rewards, compound, watchdog, opportunity sniffer, points farm, nap). A status bar runs along the bottom.
- **Builder:** 9 colours, 12 mods, 6 moods and a name, with a randomize button and 9 presets. Compiling saves your Scurge on the visitor's device for now.
- **Info sections:** How it works (3 steps), How Scurge earns (TRADES: 0), a day-in-the-life log, the $SCURGE token with holder perks, and an FAQ.

Everything on the monitors is a labelled, simulated preview until launch.
