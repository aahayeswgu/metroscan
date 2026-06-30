# MetroScan

MetroScan came out of watching someone close to me grind through B2B sales. A big chunk of the
day goes to just figuring out who is even worth calling. I wanted to build the thing that does
that part for them.

So MetroScan reads public information about contractors across a metro and works out which ones
look like they are hiring or ramping up right now, then ranks them. The rep starts the day on the
best accounts instead of guessing. I built it because I wanted to, and because it actually helps a
real person do their job.

![MetroScan - ranked leads (illustrative, fictional data)](docs/metroscan.png)

## How it's put together

High level only. The sources and the scoring approach are private.

```
metroscan/
├── sources/     gather public signals about contractors in a metro
├── enrich/      summarize and read with an LLM
├── score/       rank firms by how likely they are hiring now
└── deck/        build the ranked report for the sales team
```

## Tech

Python, public data sources, a large-language model for reading and summarizing, automated report
output.

## Status

A real, working product I built and put in front of a sales team. The code and the scoring are
private; this is an overview.

Built by Tracecast LLC.

---

![Tracecast LLC - custom signal engines for B2B](docs/tracecast-logo.png)
