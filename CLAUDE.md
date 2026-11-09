# Radiata Dora

Business context for all work here: site, GTM tooling, inbound marketing, outreach.

## Company
- Radiata Ltd (Radiata Oy in Finnish), a one-person Finnish company founded by Neelabh Kashyap,
  a data and AI professional with a PhD who builds data platforms for Nordic companies.
- Dora is Radiata's first product: an automated DORA register of information service. Stage: customer discovery.

## Problem
- DORA Article 28(3) requires every EU financial entity to keep a register of its ICT service arrangements.
  It is filed in xBRL-CSV (ITS (EU) 2024/2956), and the regulator can ask for it at any time.
- Every fact in the register already sits in source systems: accounts payable, Entra ID, the contract repository, Azure.
- Yet most firms rebuild it by hand from spreadsheets each spring. They cannot prove it is complete,
  and services added between cycles go unrecorded.
- Evidence: 6.5% of registers passed all ESA checks in the 2024 dry run (ESAs, 2024); 46% of firms called
  the register their hardest DORA task (Deloitte European DORA Survey, 2025).

## Business idea
- Automate and outsource register creation so staff can move to more valuable work.
- Dora reconciles source systems against the register, shows the gaps and produces a validated xBRL-CSV file.
- Value: time saved, provable completeness, fewer validation failures.

## Customers
- In-scope financial entities: insurers, fund managers, investment firms, payment and e-money institutions, crypto-asset providers.
- Mid-size firms first, starting in Finland and the Nordics. Users sit in compliance, risk, procurement or vendor management.

## GTM today
- Site: https://dora.radiata.fi (English and Finnish). Main call to action: a 30-minute research interview, winter 2026–27.
- Participants get a benchmarking report and favourable pricing and terms on future products.
- Interview data is confidential. Pricing and integrations are undecided: do not invent them.

## Writing rules
- Calm and explanatory, like Neelabh's thesis abstract: context first, then the point. Number points when there are several.
- Short and skimmable. Prefer lead line, short list, closing line over long paragraphs.
- No AI slop or hype words.
- Say "regulator", not "supervisor". Say "Radiata Ltd" in English and "Radiata Oy" in Finnish. Do not mention Espoo.
- Founder bio: no named technologies or doctoral field.
- Cite every number. Never invent statistics or customers.
- All public copy needs English and Finnish versions.

## Repo
- Static index.html on GitHub Pages; .en/.fi spans switch language. Pushing to main deploys.
