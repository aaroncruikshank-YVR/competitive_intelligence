# CI source catalogue

A working taxonomy of where to look for what. Organized roughly from "most authoritative and verifiable" to "most signal-rich and most noisy." The right CI project triangulates across categories. No single category is sufficient.

For each category: what you find, reliability profile, and search tips for someone working with a general-purpose AI plus a browser.

---

## Tier 1: Authoritative and verifiable public sources

These are primary-source documents. They have the highest evidentiary weight and should anchor any consequential finding.

### Regulatory filings (public companies)

**What you find:** Strategy disclosures, risk factors, financial trajectory, segment data, executive compensation (a proxy for strategic priorities), legal exposure, recent transactions, off-balance-sheet commitments.

**Key documents (US):**
* **10-K** (annual report): the foundational document for any US public competitor. Read the "Business" section, the "Risk Factors," and "MD&A." Most people read only the financials. The strategic disclosures are richer.
* **10-Q** (quarterly): mid-year updates, often where strategic shifts first surface.
* **8-K** (current report): material events, including executive changes, M&A, major contracts.
* **S-1** (IPO prospectus): often the most candid strategic document a company ever files. Required reading on pre-IPO competitors.
* **DEF 14A** (proxy): executive compensation structure reveals incentive alignment; activist filings reveal investor pressure points.

**Equivalents elsewhere:** SEDAR+ (Canada), Companies House (UK), EDINET (Japan), Chinese exchanges, etc.

**Search tip:** SEC EDGAR full-text search (efts.sec.gov) is free. The AI can summarize, but verify exact wording from the filing for any quoted material.

### Patent and trademark databases

**What you find:** R&D direction, technical capability, geographic strategy (where they file matters), partnership signals (joint filings), pipeline timing.

**Where to look:** USPTO (US), EPO (Europe), WIPO (international), Google Patents (best free interface), Lens.org (free, includes citation network).

**Search tip:** Filter by assignee (the company), date range (last 18 to 36 months for direction), and CPC classification. Look at *who* the inventors are. A new inventor cluster signals a new team.

### Court records and litigation

**What you find:** Disputes that reveal what a company values enough to defend, what its competitors view as threatening, supplier and customer relationships (through breach-of-contract suits), trade secret claims.

**Where to look:** PACER (US federal), state court systems, CourtListener (free), Justia.

**Search tip:** A competitor's litigation history reveals strategic vulnerabilities. Trade secret cases are particularly informative about what they consider their "crown jewels."

### Government data and statistics

**What you find:** Market sizing, industry trends, demographic shifts, regulatory direction, procurement patterns (government as customer).

**Where to look:** Census bureaus, BLS (US), Eurostat, OECD, World Bank, sector-specific regulators (FDA, FCC, Health Canada, EMA, etc.).

**Search tip:** For market sizing, top-down from government industry classification (NAICS, SIC, NACE codes) and reconcile with bottom-up from company filings.

---

## Tier 2: Industry, trade, and analyst sources

High reliability if the publisher is reputable. These translate raw data into context. Watch for publisher bias (a vendor-sponsored analyst report is not the same as an independent one).

### Industry analyst houses

**What you find:** Market sizing, competitive landscape positioning, technology trajectories, buyer behavior trends.

**Key houses:** Gartner, IDC, Forrester (technology); McKinsey, BCG, Bain (cross-industry); sector specialists (e.g., Aite for financial services, IQVIA for pharma, Wood Mackenzie for energy, Rystad for oil and gas, Frost & Sullivan, Kantar, NielsenIQ).

**Caveats:** Paid analyst content reflects the analyst's view, which is informed but not impartial. Magic Quadrant and Wave-style reports privilege vendors who brief the analysts. Read accordingly.

**Search tip:** Free analyst content (blogs, webinars, press releases) often previews the paid reports. Search "[Analyst house] [topic] 2024" for the free version.

### Trade publications and industry press

**What you find:** Sector-specific developments, executive interviews, product launches, deal flow, the social fabric of the industry.

**Examples by sector:** TechCrunch, Information, Stratechery (tech); Modern Healthcare, FiercePharma (healthcare); Risk.net, American Banker (finance); WWD (retail); GreenTechMedia (energy); Defense News (defense). Every meaningful industry has 3 to 8 publications worth following. Find them.

**Search tip:** Sharp's recommendation is to subscribe to 3 to 4 core trade pubs plus one rotating subscription from an *adjacent* industry. The adjacency rotation is where you catch substitutes and convergent threats early.

### Industry associations

**What you find:** Sector statistics, regulatory positions, member directories, conference programming (which reveals what the industry is talking about).

**Caveat:** Associations advocate for the average member's view. They lag innovation and over-state continuity. Useful for baselines, less useful for early signal.

### Conference proceedings and decks

**What you find:** Executive thinking, product roadmaps (often more candid in conference talks than in press releases), partnership announcements, technology trajectories.

**Search tip:** Search for "[conference name] 2024 keynote" or "[conference] presentations." Many conferences post slide decks. SlideShare and corporate IR sites are gold.

---

## Tier 3: Company-disclosed sources

Useful but inherently self-interested. Read with awareness of the framing.

### Corporate websites and investor relations

**What you find:** Official positioning, product portfolio, leadership team, customer references, IR presentations, ESG reports.

**Search tip:** The IR section is usually more candid than the marketing site. Quarterly earnings presentations are particularly rich.

### Press releases and corporate blogs

**What you find:** What the company wants publicly known. Announcement framing reveals strategic priorities.

**Search tip:** Track press release volume and topic mix over 12 to 24 months. A shift in the dominant theme (e.g., from "product" to "platform") usually precedes a strategy change by 6 to 18 months.

### Earnings calls and investor presentations

**What you find:** Strategic narrative, segment performance, capital allocation, executive concerns (especially in Q&A).

**Where to look:** Seeking Alpha (free transcripts), corporate IR sites, AlphaSense (paid).

**Search tip:** The Q&A portion is more revealing than the prepared remarks. Pay attention to analyst questions that get hedged answers.

### Executive speeches and interviews

**What you find:** Strategic worldview, what the CEO is paying attention to, signals about upcoming announcements.

**Search tip:** Conference keynotes, podcast appearances, and trade press interviews. Track each major exec for 12+ months.

### Job postings

**What you find:** Strategic direction. Aggressively under-used as a CI source. Patterns in hiring reveal market entries (regional sales leadership), capability builds (a new function appearing), and product strategy (skills demanded reveal what they are building).

**Where to look:** Company careers pages, LinkedIn, Indeed, Glassdoor.

**Search tip:** Track quarterly hiring volume by function and geography for each tracked competitor. A spike in "channel partnerships" or "regional sales managers" in a region is a signal worth alerting on.

### Patent and product filings tied to launches

(Covered in Tier 1.) Cross-reference with job postings and analyst commentary to triangulate launch timing.

---

## Tier 4: Customer, channel, and HUMINT

The highest-value category if executed well. Also the slowest, hardest, and most ethically sensitive.

### Customer reviews and complaints

**What you find:** Real product strengths and weaknesses, unmet needs (which become opportunities), competitor pain points.

**Where to look:** G2, Capterra, TrustRadius (B2B SaaS); Google reviews, Yelp, Trustpilot (consumer); industry-specific review sites; subreddits (use the Reddit search and watch for moderator and community norms).

**Sharp's tip:** Treat complaints as opportunities. Pattern-matching across reviews surfaces the gap that the next entrant will exploit.

### Channel partners and distributors

**What you find:** Who is winning, who is slipping, which products move and which sit, regional dynamics, post-sale support quality, real pricing (versus list).

**Why it matters:** Distributors see the whole channel. Sharp considers this the second-most-valuable source category after expert interviews.

**Approach:** Existing distributor relationships are best. If the user's company has channel partners, those people will talk to them. Outside-in research requires identifying distributors and approaching them as a researcher, not as a buyer.

### Suppliers

**What you find:** Who is buying what, in what volumes, which direction the industry is moving (because suppliers sell across the sector).

**Approach:** Trade show conversations, industry events, and supplier conferences. Suppliers are often more open than expected because they want visibility into customer planning.

### Expert interviews

**What you find:** Synthesis from people who have spent years in the space. Forward-looking interpretation. Context for everything else.

**Sources of experts:**
* Former employees of target companies (LinkedIn search)
* Industry analysts (sometimes available for inquiry calls, paid or unpaid)
* Academic researchers in the space
* Specialist journalists
* Retired executives (often willing to talk for the engagement)
* Consultants who specialize in the sector

**Expert networks (paid):** GLG, AlphaSights, Guidepoint, Third Bridge, Mosaic. These connect researchers with vetted experts for paid calls (typically $300 to $1,500 per hour). The cost is justified when an answer would otherwise require weeks of desk research.

**Approach:** Have a clear question. Send the topic in advance. Take notes verbatim. Send a thank-you. Build the relationship for follow-up. Never ask for confidential information; ask for the expert's perspective.

### Field observation

**What you find:** What is actually happening in stores, factories, distribution centers, and conferences (versus what is reported).

**Examples:** Retail audits, mystery shopping, trade show walks, attending conferences as a delegate.

**Trade show tip (Sharp):** Have a plan before you arrive. Identify exhibitor targets, the booths to visit, the people to meet, and the questions to ask. Debrief each evening. The most common waste is going without a plan and "seeing what's there."

---

## Tier 5: Digital signals and social

High volume, high noise, useful as early-warning flags. Never as primary evidence.

### LinkedIn

**What you find:** Hiring patterns, executive moves, employee count trends, organizational structure (by browsing employees), partnership announcements, conference attendance, executive thinking (via posts).

**Search tips:**
* Track executive job changes (especially senior leaders) as inflection signals.
* Use LinkedIn Sales Navigator or similar for systematic employee tracking (paid).
* Read what target executives post and comment on. It reveals their priorities.

### X / Twitter, Bluesky, and similar

**What you find:** Real-time industry commentary, executive thinking, customer complaints, breaking news.

**Caveat:** Echo chambers. Pundits with confidence and no data. Treat as input, never as conclusion.

### Reddit and specialist forums

**What you find:** Authentic user voice on products, real pain points, candid employee perspectives (in subreddits like r/cscareerquestions, r/sales, sector-specific subs).

**Approach:** Identify the relevant subreddits and read 50 to 100 posts before drawing any conclusion. Sample size matters more here than anywhere.

### Glassdoor and Blind

**What you find:** Internal culture signals, leadership perceptions, compensation benchmarks, organizational pain points.

**Caveat:** Selection bias toward dissatisfied employees. Useful for patterns, not for individual data points.

### News media

**What you find:** Major announcements, M&A, regulatory actions, scandals.

**Approach:** Google News, Bing News, sector-specific aggregators. Avoid relying on a single outlet's framing; cross-read at least three sources for any significant story.

---

## Tier 6: Adjacency and substitutes

The category most often missed. Sharp is emphatic: the disruptive threat usually comes from outside the industry as currently defined.

**What you look for:**
* Companies serving the same customer with a different mechanism
* Technologies that could replace the current basis of competition
* Business models from adjacent industries that could be imported
* New entrants from "below" with a simpler, cheaper, or more focused offering (Christensen's disruption pattern)

**How to find it:**
* Subscribe to one trade publication outside the industry, rotated every 6 to 12 months
* Track venture capital activity in adjacent sectors (Crunchbase, CB Insights, Pitchbook)
* Track patents filed by companies *not* currently in the industry but with capability that could enter
* Listen to customer descriptions of the problem they are trying to solve (not the product they currently use); the substitute often serves the same job-to-be-done with a different mechanism

---

## Tier evaluation summary

| Tier | Reliability | Speed to acquire | Cost | When to use |
|---|---|---|---|---|
| 1: Authoritative | Highest | Fast | Free | Anchor every consequential finding |
| 2: Industry/trade/analyst | High | Fast | Mixed | Context and synthesis |
| 3: Company-disclosed | Moderate (self-interested) | Fast | Free | Positioning and stated strategy |
| 4: HUMINT/customer/channel | Highest *if* well-executed | Slow | Variable | The "why" behind everything else |
| 5: Digital signals | Low to moderate | Fast | Free | Early flags, never primary evidence |
| 6: Adjacency/substitutes | Variable | Slow | Free | The disruptive threats nobody is watching |

The mature project draws from all six. The rushed project skips 4 and 6 and pays for it later.

---

## Source evaluation discipline

For any non-trivial finding, log:

* **Source:** what was the origin?
* **Date accessed:** when did you collect it? (Information has a shelf life.)
* **Reliability:** A (proven track record) / B (usually reliable) / C (unverified) / D (questionable)
* **Access level:** primary (the entity itself) / secondary (reporting on the entity) / tertiary (commentary on the reporting)
* **Bias profile:** what is this source's interest? Vendor pitch? Activist agenda? Self-promotion?
* **Corroboration:** how many independent sources confirm this?

Single-source findings on consequential matters get flagged in the deliverable, with the limitation stated. This is not weakness; it is defensibility.
