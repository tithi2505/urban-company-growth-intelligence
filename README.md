# Urban Company Growth Intelligence — Graduation Project

**Goal:** Discover customer-side opportunities to increase the share of customers completing another Urban Company service within 90 days of an eligible anchor booking.

**Status:** Research and discovery engine in progress. No customer problem or solution has been predetermined.

## Core metric

For a selected anchor month:

- **Denominator:** Unique customers whose first completed booking during that month is in an eligible core category (excluding InstaHelp/quick-service housekeeping).
- **Numerator:** Those customers who subsequently complete another booking, in any category, within 90 days of their anchor booking.
- **Exclusions from qualifying repeat bookings:** Redos, warranty claims and bookings ending in refunds.

**90-day repeat completion rate = numerator / denominator.**

Public feedback cannot directly establish this population metric. We will distinguish *customer-reported behaviors and opportunity signals* from verified company cohort data.

## Discovery engine: planned workflow

1. **Collect permitted public sources** (app store reviews, public complaint forums, Reddit, public company materials). Record source, URL, date, category, and access limits.
2. **Normalise and de-duplicate** feedback; keep original text and traceable links.
3. **Label user needs and journey evidence**: trigger for needing a service, post-service expectations, decision path for the next job, off-app substitutes, friction, trust signals, category/city context, and whether repeat behavior is explicitly stated or unknown.
4. **Compare opportunity areas** by evidence volume, cross-source consistency, relevance to a repeat booking, counterevidence, and confidence. Do not treat the share of complaints as a measure of churn or a true population prevalence.
5. **Quality-check** around 20 manually labelled public items, calculate agreement by label, preserve disagreements and log 2–3 corrections to AI output.
6. **Validate** the best-supported opportunity with 5–6 interviews (both repeat and non-repeat customers), then build and test a customer-side MVP.

### Bias controls

- **Selection bias:** Public reviewers are not a random sample. Report source mix, positive/negative mix, duplicates and unknown behaviors rather than extrapolating to all customers.
- **Silent non-returners:** Absence of a repeat mention is **unknown**, not proof of non-return. Interview recruitment will deliberately include people who did not complete another booking within 90 days.
- **Evidence hierarchy:** Clearly distinguish a direct customer statement, a reasonable inference, a hypothesis, and unavailable/uncorroborated information.
- **Source and permission rules:** Use only pages and public materials permitted to access. No logged-in Urban Company data, app scraping, or personal booking documents.

## Research and ethical guardrails

- No discounts, coupons, memberships, price changes or professional compensation/management changes.
- The MVP will not book services, message professionals or Urban Company, or take actions on user accounts.
- No respondent invoices, screenshots, addresses, phone numbers or personal documents collected.
- Do not fabricate interview participants, interview quotes, research outcomes or AI performance metrics.
- The final deck must be **10 slides or fewer** and have **no fellow name**.

## Deliverables

| Deliverable | Status |
|---|---|
| Publicly testable AI Discovery Engine | Not yet built |
| 10-slide PDF deck | Not yet built |
| Publicly deployed AI-native MVP | Not yet built |
| Public-view AI Evidence Log | Not yet built |
| 5–6 interviews and at least 3 user tests | Not yet conducted |

**Course deadline:** 13 December 2026, 3:59 PM IST.

## Next steps

Build a traceable source register, collect a permissible sample of public feedback, and create a reproducible baseline labelling pipeline **before choosing an opportunity**.

This is an independent educational project and is not affiliated with Urban Company.
