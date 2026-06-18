# AI-Powered SEO Content Production — Research Project

## Why This Topic

I picked AI-powered SEO content production over the other options because it's the most 
contested space in B2B marketing right now — half the industry is using AI to scale content 
production, the other half is publishing case studies on how it tanked their rankings. I wanted 
to actually read what people who do this for a living are saying, not just skim Twitter takes.

## Who I Followed and Why

**LinkedIn:**
- **Lily Ray** — SVP of SEO at Amsive, one of the most cited voices on E-E-A-T and how 
  Google's quality systems treat AI-assisted content. [add your specific takeaway from her recent posts here]
- **Bernard Huang** — Co-founder of Clearscope, builds tools that sit at the exact 
  intersection of AI content generation and search optimization. [your takeaway]
- **Steve Toth** — Known for documenting real, ongoing programmatic SEO experiments in public — 
  not theory, actual sites and actual numbers. [your takeaway]
- **Cyrus Shepard** — Founder of Zyppy, ex-Moz, focuses on technical SEO and what actually 
  moves rankings vs. what's noise. [your takeaway]
- **Dani Leitner** — In-house SEO perspective, useful as a counterweight to the agency/consultant 
  voices above. [your takeaway]

**Other sources:**
- **Kevin Indig** — Writes the Growth Memo newsletter, ex-Shopify/G2/Atlassian. Brings a 
  growth-team lens rather than a pure-SEO lens, which is closer to how a B2B GTM role would 
  actually use this. [your takeaway]
- **HV SEO** — [one line on why you included this source]

**YouTube:**
- A video on ranking #1 on Google in under 24 hours — wanted to see if the claim held up 
  or was clickbait
- Ryan Stewart's breakdown of how AI is changing SEO agencies' business models
- A video specifically on AI SEO strategies backfiring — included this on purpose, not 
  just the success stories, because the failures tell you more about where the limits are

## How I Collected This

- **LinkedIn posts** — collected manually since LinkedIn doesn't have a public API for this
- **YouTube transcripts** — pulled via the Supadata API rather than YouTube's own API, 
  which has stricter quota limits for transcript access
- **Web research** — used TinyFish as a web agent to find and verify expert profiles and 
  recent activity before committing to a source
- **AI tooling** — ran this through Claude Code, routed through Ollama Cloud once I hit 
  Anthropic's usage limits, with sub-agents handling the transcript organization separately 
  from the source curation so I could parallelize the work
- **Notes** — kept working notes in Obsidian before formalizing them into this repo

## Repo Structure

research/
├── sources.md              — all 10 experts, links, dates, why each one made the list
├── linkedin-posts/         — posts organized by author
├── youtube-transcripts/    — transcripts organized by video
└── other/                  — additional material that didn't fit the above two buckets