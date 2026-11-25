# Discovery engine: evidence and labelling protocol (draft)

This is a **research instrument**, not findings. The source register lists 14 **candidate public URLs**; it does **not** mean 14 reviews or conversations have been labelled or analysed. Check each site's access conditions before collecting any user-authored text.

## Unit of analysis

One public review/comment/post = one **item**, with its original URL or durable identifier, date if visible, public text, source type, and date accessed. Separate public company disclosures as **context** rather than customer testimonial items.

## Proposed labels

| Label | Values / interpretation |
| --- | --- |
| source_type | play_store, trustpilot, mouthshut, reddit, other |
| service_category | cleaning, AC, plumbing, electrical, carpenter, salon, other, unknown, InstaHelp (exclude from anchor analysis) |
| city | named city, multi_city, unknown; never infer from subreddit alone |
| experience_outcome | positive, mixed, negative, unknown |
| post_service_need | follow_up, maintenance_schedule, next_category, assurance, support, other, not_stated |
| need_trigger | time_based, visible_issue, breakdown, event, recommendation, other, not_stated |
| next_service_path | Urban_Company, local_provider, friend_or_family, WhatsApp, unresolved, not_stated |
| repeat_statement | explicit_repeat, explicit_no_repeat, contemplating, no_statement |
| 90_day_status | confirmed_within_90d, confirmed_no_repeat_after_90d, cannot_determine |
| issue_or_opportunity | short hypothesis label; **do not presuppose cause** |
| evidence_grade | direct_statement, inferred, speculation, context_only |
| city/category_confidence | explicit, inferred, unknown |
| relevant_to_core_anchor | yes, no, unknown |
| quote_support | short excerpt or exact location; preserve the source link |
| coder_notes | conflicting evidence, ambiguities, exclusions |

Do not use **no_statement** as proof of non-repeat. Negative reviews are not a random sample.

## Quality and validation plan

1. Build a **hand-labelled golden set of ~20 distinct customer items** spanning source types, positive/negative experiences, categories and repeat statements, including ambiguity.
2. Run the same labels through the engine **without exposing gold labels**.
3. Report exact-match accuracy by field, confusion examples, uncertainty rates, and a small disagreement table. For sparse labels, report both counts and denominators.
4. Record **2–3 concrete rejections or corrections** with source evidence, before/after AI output, and reasoning.
5. Compare opportunity areas on source-diverse signals, direct evidence, user value, product influence, counterevidence, and research gaps — **not** on complaint volume alone.
6. Carry the top hypotheses into 5–6 consent-based interviews, deliberately including both 90-day repeaters and mature non-repeaters across more than one core category.

## Metric and method caveats

The assignment's actual 90-day metric requires completed-booking cohort data. Public commentary cannot supply this denominator. The discovery engine generates **opportunity hypotheses**, not a statistically representative estimate of churn or repeat booking share.

### Data collection guardrails

- Check platform terms and permissions before extracting content at scale. Prefer manual sampling or an approved API/export.
- Do not scrape logged-in pages, the Urban Company app, or restricted content.
- Preserve only public comments needed for analysis; avoid personal contact details and handles where unnecessary.
- Separate InstaHelp discussion from core-category anchor evidence; other categories may count as later qualifying repeat completions per the assignment.
- Public posts from 2025–2026 do not validate 2026 cohort outcomes without dates of completed bookings.
