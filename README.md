# BA Mentorship Survivor — Live Scoreboard

An interactive, retro game-night-inspired scoreboard created for the University of Houston C. T. Bauer College of Business Bauer Ambassadors mentorship program.

## About

This browser-based scoreboard tracks points earned during **Mentorship Survivor: BA Edition**, including the contributions that count toward the yearlong mentorship competition. The interface takes inspiration from the event's red, cream, light-blue striped, and yellow-star presentation theme.

## Features

- Four editable mentorship team names
- Four scoring rounds: **Do You Know Bauer?**, **Bauer Scavenger Hunt**, **Flight Challenge**, and **Bauer Taboo**
- **±1-point** controls for trivia, scavenger hunt, and Taboo; **±10-point** controls for the flight challenge
- Automatic totals and live team rankings, including negative flight-bet scores
- Presentation mode to display rankings without editing controls
- Placement bonuses: **+5 for first**, **+3 for second**, and **+1 for third**
- Browser-based score saving, CSV export, and JSON backup/restore

## How to use

1. Enter your mentorship group names.
2. Select the round and adjust each team's points.
3. Switch to presentation view to show the leaderboard.
4. Once the event is complete, confirm the placements and apply the placement bonuses.
5. Export the final results for the yearlong mentorship tracker, and download a JSON backup.

## Important notes

- Scores are stored **locally in the current browser**, not on GitHub or a shared server. Other devices do not see live changes automatically.
- Use the same browser during the event and download backups regularly.
- The placement bonus should be applied **only once**, after final rankings are confirmed and any ties are resolved.
- This scoreboard covers the event; export results to your separate yearlong points tracker.

## Project files

```text
ba-mentorship-survivor/
├── index.html   # Page structure
├── style.css    # Retro visual theme
├── script.js    # Scoring and browser persistence
└── README.md    # Documentation
```

Created for the **2026–2027 Bauer Ambassadors mentorship program** at the University of Houston.
