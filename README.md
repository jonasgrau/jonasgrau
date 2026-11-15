# Hi, I'm Jonas 👋

I build software around **mobility, maps and public data**, and small native apps for the Mac.
I like tools that take messy real-world data — departure feeds, tree registers, routing
benchmarks — and turn it into something clear, tested and actually usable.

📍 Hamburg · ✉️ [mail@jonasgrau.de](mailto:mail@jonasgrau.de)

## Projects

### 🚌 [AVV Departures](https://github.com/jonasgrau/avv-departures) · [live](https://bushof-monitor.vercel.app)
Real-time departure board for Aachen and the whole AVV area, styled like the amber LED
displays at the stops. Disruption notices, line filters, a full-screen display mode for wall
screens, and offline fallback. No dependencies, no build step; parser tests run against
recorded API responses.
`JavaScript` `Vercel serverless`

### 🌳 [Pollenkarte Hamburg](https://github.com/jonasgrau/pollenradar) · [live](https://hamburg-pollenkarte.vercel.app)
Today's pollen forecast for Hamburg on a map of the allergy-relevant street trees around you.
Combines the Deutscher Wetterdienst forecast with Hamburg's street tree register. A monthly
GitHub Action refreshes the tree data and refuses to publish if a dataset suddenly shrinks.
`JavaScript` `Open data` `GitHub Actions`

### ♞ [Knightbar](https://github.com/jonasgrau/knightbar)
Chess in the macOS menu bar: play Stockfish at eight levels, solve the daily puzzle from
Lichess or Chess.com, and play Lichess correspondence games right in the popover. Rules
engine with perft tests, OAuth login, a dot in the menu bar when it's your move. Released
through GitHub and Homebrew with a one-command release script.
`Swift` `SwiftUI` `Swift Testing`

### 🚚 [vrp-baselines](https://github.com/jonasgrau/vrp-baselines) + [routeviz](https://github.com/jonasgrau/routeviz)
Tools for the vehicle routing problem (CVRP). **routeviz** plots, animates and *verifies*
solutions: every customer visited once, capacities respected, cost recomputed.
**vrp-baselines** benchmarks Clarke–Wright savings, Google OR-Tools and Hybrid Genetic Search
on CVRPLIB instances, with every result checked by routeviz rather than trusted from the solver.
`Python` `OR-Tools` `Optimization`

## Tech I work with

**Languages:** Swift · JavaScript / TypeScript · Python
**Areas:** native macOS apps · web apps and serverless APIs · open & public transport data ·
route optimization · automated testing and releases (GitHub Actions, Homebrew)
