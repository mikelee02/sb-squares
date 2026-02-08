# Super Bowl LIX Squares — Live Dashboard

Live scoreboard for our Super Bowl Squares pool. Auto-pulls scores from ESPN every 30 seconds.

**🏈 [View the Dashboard](https://mikelee02.github.io/sb-squares/)**

## How It Works

- **Live score** from ESPN updates every 30 seconds
- **The board** shows all 100 squares with player names and ROLLOVER cells
- **Quarter results** lock in as the game progresses, tracking payouts and rollovers
- **Winnings leaderboard** tallies who's won what

## The Pool

- 8 players, 10 squares each, $50 buy-in
- Total pot: $400
- Q1: $80 | Halftime: $100 | Q3: $80 | Final: $140

## Rules

- **Rollover (Q1, Halftime, Q3):** If a quarter lands on a grey ROLLOVER square, the money rolls into the next quarter's payout.
- **Closest Square (Final only):** If the final score lands on ROLLOVER, the prize goes to the nearest paid square (up/down/left/right, no diagonals). Ties split.

## Commissioner

The commissioner locks in quarter scores via the ⚙️ panel at the bottom of the page. Locked scores are encoded in the URL hash — the updated link gets shared to the group chat after each quarter.

---

Built with [Claude Code](https://claude.ai/code)
