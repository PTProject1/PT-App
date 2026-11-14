# PT App

A hypertrophy training tracker that runs in the phone browser and installs to the home screen.

- Program builder: days per week, experience, equipment, session length and priority muscles
- Set logging with rest timer, warm-up sets and next-session targets (double progression)
- Weekly sets per muscle against typical ranges, with indirect volume
- Body weight, body composition and tape measurements
- Session history, personal records, export and restore
- "How muscle grows": a scroll-through explainer (`how-muscle-grows.html`), linked from the Train and Program screens
- "Feeding muscle growth": a nutrition explainer with a calorie and macro calculator (`feeding-muscle-growth.html`), linked from the Train and Body screens
- Three more guides: "Recovery and sleep", "Choosing exercises" and "Progressing your lifts", all listed in the Guides card on the Train screen
- Weekly weight check on the Body screen: compares weekly average weight with the pace for your goal and suggests calorie changes
- Body map on the Progress screen: each muscle coloured by this week's sets against its range

All data is stored in the browser on the device. Nothing is sent to a server.

No build step: `index.html`, `how-muscle-grows.html`, `feeding-muscle-growth.html`, the other guide pages, `sw.js` and `manifest.webmanifest` are served as they are.
