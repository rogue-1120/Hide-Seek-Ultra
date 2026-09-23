Night Ops is a thrilling live, location-based hide-and-seek web application built for 2 to 12 players! 🏃‍♂️💨 Operating as a decentralized app, it completely transforms the real physical world into a massive game board where your smartphone becomes a tactical field radio to track, hide, and survive the night 📱🔦.

🎮 Gameplay Mechanics
🚪 Lobbies & Secret Roles: Jump into a host's lobby using a quick 6-character alphanumeric code and pick your signature identity color. Got a tie for the seeker? A built-in Rock-Paper-Scissors (RPS) mini-game settles the score! ✂️🪨📄

🗺️ The Play Zone: Don't wander too far! The game is locked to a strict 500-meter radius centered right on the seeker's starting point 🎯. If a hider steps out of bounds, they are instantly disqualified ❌.

⏳ Phases & Timers: Ready, set, scatter! The game kicks off with a 5-minute wait phase for hiders to vanish before the seeker is unleashed 🏃‍♀️💨. Once the active hunt begins, the clock ticks down from a maximum of 1 hour ⏱️.

👁️ Visibility Rules: Hiders have the edge—they can track each other's live locations on the map continuously, but they'll only spot the seeker if they get within a nerve-wracking 20 meters 👀. The seeker? They fly mostly blind, surviving on a 10-second radar reveal that exposes all hiders every 3 minutes 📡🚨.

🎯 The Catch: A seeker eliminates a hider when their GPS coordinates lock them within a tight 3-meter catch range 📍. The round is over when the seeker catches everyone (Seeker wins! 🏆) or the timer runs out (Surviving hiders win! 🎉).

🎨 UI & Design Language
The app rocks a "Field Kit" aesthetic—think brutalist, tactical instrument panel built for quick glances while you're sprinting through the dark 🏃‍♂️🌙.

🖤 Color Palette: Pure dark mode energy! It uses a near-black canvas with ultra-high-contrast elements and a pulsing electric "Signal" green to highlight live actions 🟢.

🔤 Typography: It mixes Space Grotesk for razor-sharp display headings, DM Sans for easy daytime reading, and JetBrains Mono for crucial tabular data like distance readouts and access codes ⌨️.

⚙️ Technical Stack
💻 Frontend Frameworks: Supercharged by React, TypeScript, and Vite ⚡. It utilizes TanStack Router for smooth navigation, React Hook Form for quick inputs, and Radix UI primitives with Tailwind CSS for a sleek, accessible, unstyled foundation 🛠️. A specialized geolocation hook smartly throttles GPS updates based on how far and fast you move, completely preventing backend overload 🛰️.

🧠 Blockchain Backend: Powered by Motoko and deployed directly on the Internet Computer! 🌐. This smart contract handles state transitions, secures lobby access, and crunches complex equirectangular approximation math to perfectly calculate real-world distances between players 📐.
