# The Metro Ledger (fictional newspaper website — training case)

Static website for a fictional US national daily newspaper. Training case artifact; not a real publication.

## Pages

- `/` — front page (masthead + lead feature + today's stories)
- `/science/` — Science & Technology section front
- `/science/2025/05/yanxi-liu-mtrs/` — feature report on Dr. Yanxi Liu's MTRS method and the 2024 ČNDS International Award for Transport Research
- `/about/` — publisher, circulation, newsroom, editorial standards

## Domain

- github.io: https://fanshiyu35.github.io/the-metro-ledger/
- Custom domain (CNAME): themetroledger.com

## Crawling

- robots.txt: `User-agent: *` / `Disallow: /`
- Every page carries `<meta name="robots" content="noindex, nofollow">`

See NAME_CHECK.md for name-collision and domain-availability documentation.
