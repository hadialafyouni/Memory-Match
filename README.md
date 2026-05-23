Memory Matching Game

I was bored one afternoon and wanted to build something fun that actually had some depth to it. Memory match seemed simple enough on the surface, but once I started building it I realized there was a lot more to think about — card flip animations, state management, making sure two cards couldn't be flipped at the same time, and storing the high score so it actually persists between sessions.
What it does
Flip cards to find matching pairs. The game tracks your moves and saves your best score locally so it's still there next time you open it. Smooth animations, clean UI, and no external libraries — just vanilla HTML, CSS, and JavaScript.
What I learned

Managing game state without a framework is actually a great exercise
CSS animations and timing functions for the card flip effect
Web Storage API for persistent data without a backend
Handling edge cases like preventing a third card flip mid-animation

play here: https://hadialafyouni.github.io/memory-match-leaderboard/
Built with
HTML · CSS · JavaScript
