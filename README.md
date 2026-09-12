# Porter first-trip flow — concept prototype

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FVijayraman1998%2Fporter-first-trip-prototype)

**Live:** https://vijayraman1998.github.io/porter-first-trip-prototype/

An **independent product-management capstone exercise** (Airtribe PM Launchpad). Two interactive concept
prototypes for a first-time-user booking flow in intra-city goods transport.

| Page | What it is |
|---|---|
| [`/`](./index.html) | The full nine-screen first-trip flow — six new screens plus three from the existing experience, with the design rationale and the user evidence beside each screen |
| [`/engine`](./engine.html) | The sizing engine on its own, with the decision trace exposed |

Both run the same logic: declare what you are moving, get a right-sized vehicle **with its reasoning**, and a
price that holds. Change the load and the recommendation, the reasoning and the price all move.

### Not affiliated with Porter
This is a concept recreation built for a course assignment. It is **not affiliated with, endorsed by, or built
for Porter / SmartShift Logistics Solutions**. No Porter code, assets or fonts are used. Vehicle capacities, item
volumes and fare components are **modelled illustrations**, not Porter's published rates.

### Running locally
No build step and no dependencies — open `index.html`, or:

```bash
python -m http.server 8000
```
