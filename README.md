# LendUp Global

**Status: DEFUNCT — no API surface. Do not enrich.**

LendUp Global, Inc. was a San Francisco consumer-lending fintech backed by a16z, operating through
LendUp Loans, LLC (formerly Flurish, Inc.). LendUp Loans, LLC **ceased loan operations in January 2022**.

There is no live developer portal, documentation host, public API, or maintained code repository for
this entity. The enrichment pipeline produced no artifacts, and that is the correct result.

## Do not attach lendup.com

The `lendup.com` domain is live but is operated by **LendUp LLC** (8 The Green STE A, Dover, DE 19901),
an unrelated loan-matching lead-generation business. That site states on its own about page:

> This entity has no ownership, corporate, or operational relationship to the former LendUp Loans, LLC
> (formerly Flurish, Inc.), LendUp Global, Inc., or their former executives.

Wiring that domain — or any artifact probed from it — into this profile would misattribute a different
company's surfaces. `apis.yml` carries an `x-do-not-attach` entry to prevent this on future rounds.

Backed by: a16z (historical)

Verified: 2026-07-19
