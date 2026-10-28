## Randy Barnhill

Engineering technician with close to 40 years in the field: process controls, industrial automation, petroleum terminals,
biogas and pyrolysis. Founder of [Barnhill Industrial Group](https://barnhillig.com) (Industrial AI Consulting),
Nokomis, Florida.

I build working data tools by **steering AI**. I design the system, set the rules and judge the results; Claude
(Anthropic's model) writes the code under my direction. I say so on every site I publish. The skill I care about is
directing AI to produce something people can rely on.

### The Wire & Ledger — [thewireandledger.com](https://www.thewireandledger.com)

A live news aggregator that ranks stories by how many outlets cover them, not by anyone's opinion.

- **AI-built aggregation engine.** It reads the public feeds of dozens of outlets across the political spectrum,
  recognizes when different newsrooms report the same story in different words, and ranks each story by how widely
  it's covered, with newer stories weighted higher. The ranking rule is published on the site. No headline is
  rewritten and no story is picked by hand.
- **Three editions on one engine:** English, Spanish ([/es](https://www.thewireandledger.com/es/), Spain's outlets)
  and Korean ([/ko](https://www.thewireandledger.com/ko/), 29 Korean outlets, with North Korea and DMZ coverage).
  Each language gets its own headline-matching rules; Korean, for example, attaches particles and endings to words,
  and its headlines abbreviate with single Chinese characters.
- **Data desks built on public records:**
  - [Health](https://www.thewireandledger.com/health): FDA recalls and FDA's drug shortage database, grouped by drug,
    with brand names taken from FDA's own records.
  - [Follow the money](https://www.thewireandledger.com/money): federal spending, and DOJ fraud and corruption
    cases.
  - Bills, elections, local news for every US state.
- **Reliability by design:**
  - an automated test suite (hundreds of regression tests built from real mistakes the site made) runs before every
    push and blocks a bad change,
  - scheduled site checks load every page in a real browser on phone and desktop sizes,
  - every change goes to a preview before going live.
- **Rules I hold it to:** *bad data is no data* (real, sourced figures only, nothing estimated or illustrative),
  documented facts only on politics, and gaps stated openly on the page instead of hidden.

### Sister desks

| Desk | What it does | Code |
|---|---|---|
| [Global Outbreak Desk](https://global-outbreak-desk.vercel.app) | Disease outbreaks worldwide; US foodborne outbreaks mapped by state from FDA and CDC data | private |
| [North America Hazard Desk](https://hazard-desk.vercel.app) | Severe weather, earthquakes, volcanoes and other hazards | [public](https://github.com/fv6ntdqpg5-pixel/hazard-desk) |
| [Earth Desk](https://the-ledger-of-the-earth.vercel.app) | Resource reserves on a live globe | private |
| [Overhead Now](https://overhead-now.vercel.app) | Every active satellite overhead, live | [public](https://github.com/fv6ntdqpg5-pixel/overhead-now) |

The Wire & Ledger and two of the desks are private repositories (© 2026 Randy Barnhill, proprietary). Happy to walk
through the architecture and the code on request.

**Contact:** [randy@barnhillig.com](mailto:randy@barnhillig.com) · [barnhillig.com](https://barnhillig.com)
