---
# ── HOW-TO POST TEMPLATE ─────────────────────────────────────────────────────────
# Copy to _drafts/<slug>.md. When every spec is verified, move to _posts/YYYY-MM-DD-<slug>.md.
# Long-tail title pattern: "How to <job> on a <year> <make> <model> (<engine/variant>)"
layout: howto
title: "How to <JOB> on a <YEAR MAKE MODEL> (Step-by-Step)"
description: "One sentence for search results: what, which model, and that it's step-by-step."
categories: [car-maintenance]        # car-maintenance | home-repair | small-fixes  (ONE only)
tags: [make, model, job]
author: manskills                    # key in _data/authors.yml
# reviewed_by: jdoe                  # only if a real reviewer with real credentials checked it
last_updated: 2026-10-08             # shown as "Updated ..." in the byline
image: /assets/images/<slug>/hero.jpg  # your own photo
featured: false

# At-a-glance box
difficulty: "Beginner"               # Beginner | Intermediate | Advanced
time: "45–60 minutes"
cost: "[VERIFY: typical parts cost]"
applies_to: "<years/models/engines this guide covers>"

# Fact-check gate (keep post in _drafts/ while true)
needs_fact_check: true
has_affiliate_links: true            # shows the disclosure box above the first paid link

specs_note: "Specs differ by engine. Find yours on the emissions label under the hood."
specs:
  - label: "<Spec name>"
    value: "<value with units>"
    status: verify                   # verify | verified
    source: "<Source name>"
    source_url: "<https://...>"
    applies_to: "<engine/variant>"

tools:
  - name: "<Tool>"
    url: "AFFILIATE_LINK_PLACEHOLDER"  # renders as plain text until a real link is added
    retailer: "Amazon"
    note: "<optional note>"
materials:
  - name: "<Part / fluid>"
    note: "<optional note, e.g. [VERIFY: part number]>"

safety:
  - "**<Hazard>.** <What to do about it.>"

products:                            # optional product boxes after the steps
  - name: "<Product>"
    why: "<One honest sentence on why it helps for THIS job.>"
    url: "AFFILIATE_LINK_PLACEHOLDER"
    retailer: "Amazon"
    label: "Our pick"                # optional
    # NO price field on purpose (Amazon Associates policy; see report)

faq:
  - q: "<Question people actually search>"
    a: "<Short answer.>"

sources:
  - title: "<Owner's manual / FSM / OEM catalog page>"
    url: "<https://...>"
---

**Nobody taught me this.** One or two sentences: what the job is, why doing it yourself is worth it.

## Step-by-step

1. **<Short imperative step>.** Details. Mention a tool with
   {% include aff-link.html text="<tool name>" url="AFFILIATE_LINK_PLACEHOLDER" retailer="Amazon" %} if useful.
2. **<Next step>.** …

## Common mistakes

- …
