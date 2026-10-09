# Independence plan: finishing the drafts without Amazon or paid sources

Prepared 2026-10-09 (America/New_York). Nothing in this plan has been committed, pushed, published,
purchased, or applied for. Repo branch at time of writing: local `staging-drafts` (backup commit by
the parent agent, 27dee44); this pass only changed files in the working tree.

Related files: `_drafts/PHOTO-LOG.md` (image licenses + shot lists), `_drafts/FACTCHECK-REPORT.md`
(Manskills Mechanic review), `_drafts/MANIFEST.md`.

---

## (a) Every remaining [VERIFY] item and how to close it

Legend: **FREE** = a free authoritative source can resolve it (cited) · **JORDAN** = needs Jordan's own
manual, vehicle, or product · **PAID** = needs a paid source · **RETAIL** = needs a second retailer price.

### Resolved in this pass (sources fetched 2026-10-09)
| Guide | Item | Now says | Source |
|---|---|---|---|
| Drywall | EPA lead link | Pre-1978 lead-paint warning + link | https://www.epa.gov/lead/lead-renovation-repair-and-painting-program |
| Drywall | Drywall thickness | "Match your wall; measure the hole edge." Code minimum: ≥1/2 in on garage-side walls shared with the house, 5/8 in Type X under living space over a garage. **Corrects the draft's old claim that garage walls are 5/8 in.** | IRC R302.6 via https://up.codes/s/dwelling-garage-fire-separation |
| Stud/TV | CPSC tip-over link | Link to Anchor It! | https://www.anchorit.gov/ |
| Blade | Sharpening frequency | Cited as one manufacturer example: "two times a year or every 25 hours" | Briggs & Stratton BRUTE 7800743 manual p.17, https://www.manualslib.mx/manual/412300/Briggs-And-Stratton-Brute-7800743.html?page=17 |
| Corolla | Capacity, viscosity/API grade, drain plug + gasket + torque, filter fitment, filter tightening, change interval | Marked verified per Manskills Mechanic (Toyota AE92/AE95 factory repair manual LU-5/LU-7/LU-8/MA-2/MA-3/MA-5/IN-5/IN-27, ToyotaPartsDeal catalog) | https://jdmfsm.info/Auto/Japan/Toyota/Corola/Corolla_1989_All-Trac_Manual.pdf — **read by Mechanic, not re-fetched by me**; the PDF is a third-party-hosted copy of a Toyota manual, so Jordan may prefer to confirm against a paper copy before publishing. |
| 6 cost fields | Price ranges | See (b) | Do it Best + Meijer / Newegg pages |

### Still open
| Guide | Item | Class | How to close |
|---|---|---|---|
| Corolla | Oil-filter price | RETAIL | Price 90915-YZZN1 at 2 retailers (Toyota dealer parts site + one parts store); fitment is now known. |
| Check/add oil | Oil between ADD and FULL | JORDAN (per vehicle) | Keep generic wording + "see your owner's manual"; optionally cite one OEM manual as an example (free manuals at owners.toyota.com / my.chevrolet.com etc.). |
| Check/add oil | Oil grade | JORDAN | Owner's manual / oil filler cap. Leave as "per manual". |
| Check/add oil | Overfill effects source | FREE | Any OEM owner's manual "do not overfill" section (e.g., a Toyota or Honda owner's manual PDF). Not fetched today. |
| Tires | Lug-nut torque, lug socket size | JORDAN | Owner's manual. Do not publish a generic number (Mechanic agrees). |
| Tires | Re-torque interval | FREE (conflicting) | Continental (fetched today) says about 50 km after mounting; a Tire Review article cites 50–100 mi for trucks. Pick one tire-maker source and quote it, or keep "per tire shop". |
| Tires | TPMS relearn | JORDAN | Per vehicle; keep "check owner's manual". |
| Jump start | Hybrid/EV rules | JORDAN | Per vehicle; keep deferral. |
| Wipers | Blade lengths | JORDAN | Per vehicle; blade makers' free fit lookups (Bosch, Rain-X, Trico) can supply examples. |
| Sink | Slip-nut tightening source | FREE | A trap/fitting maker's install sheet (e.g., Oatey, Keeney). Not fetched today. Mechanic: current text is standard practice. |
| Sink | Snake cable size | FREE | RIDGID Kwik-Spin+ listing says 1/4 in cable for lines up to 1-1/2 in, but I only saw it in a search snippet; the RIDGID page 404'd and Home Depot timed out. Re-fetch from ridgid.com. |
| Drywall | Typical thickness of non-garage interior walls | FREE | A gypsum maker's spec sheet (USG/CertainTeed/National Gypsum). Not fetched today. |
| Drywall | Coat dry time | JORDAN/per product | "Follow the label" is correct; optionally quote one product's label. |
| Mower oil | Capacity | JORDAN/per engine | Engine manual (Briggs/Honda free PDFs by model). Only a third-party chart was seen. |
| Mower oil | Drain plug drive size | JORDAN/per engine | Same. |
| Stud/TV | Lag bolt size/penetration | JORDAN/per mount | Mount instructions. |
| Stud/TV | Anchor ratings | JORDAN/per product | Anchor package. |
| Stud/TV | Wire routing near outlets | FREE (optional) | An electrical-safety source (e.g., ESFI) if Jordan wants it cited. |
| Blade | Bolt torque, socket size | JORDAN/per mower | Operator's manual (the BRUTE manual gives 9/16 in, 30 ft-lb for that model only; not used as generic). |
| Blade | Replacement blade part no. | JORDAN | Per mower model. |
| Faucet | Temperature to act by | FREE (not found) | No primary source found; keep "before the first hard freeze". |
| Faucet | Frost-free identification tips | FREE | A hydrant maker's page (Woodford, Prier). Not fetched today. |
| 6 guides | Costs not priced | RETAIL | See (b). |

No item needs a **PAID** source. The only paywall-adjacent item is the Corolla factory manual, which a free hosted copy covers.

---

## (b) Prices without Amazon Associates

**Amazon policy (Associates Program Policies, updated April 14, 2026, fetched today,
https://affiliate-program.amazon.com/help/operating/policies):** "your Site may only show prices and
availability if: (a) we serve the link in which that price and availability data are displayed, or
(b) you obtain Product pricing and availability data via Creators API or PA API". So **never hard-code
Amazon prices** in the posts, even after enrollment. The policy also has new "Agent" terms (agents must
identify themselves and must not get around CAPTCHAs), so Amazon pages should not be scraped by tools.

**Recommendation:** publish a **range from at least two independent retailers** with "prices checked
<Mon YYYY>" next to it, and keep the source URLs in an HTML comment so the next re-check is quick. Don't
show any one retailer's price as "the" price. Re-check every 6 months or when a guide is updated.

**What actually worked from this box today:**
| Retailer | Result |
|---|---|
| Do it Best (doitbest.com) | ✅ Product pages show prices to plain curl. robots.txt disallows `/search/`, so I found product URLs with a web search instead. |
| True Value | ✅ Works, but it's the same company as Do it Best (acquired), so it **doesn't count as a second retailer**. |
| Meijer | ✅ Some search-result pages are server-rendered with prices. Product pages and many searches render client-side (no data). |
| Newegg | ✅ Search pages have prices, but many listings are marketplace sellers. Flagged in notes. |
| Home Depot, Lowe's, AutoZone, Harbor Freight, Ace, NAPA, Northern Tool, Pep Boys, Monoprice, Acme Tools | ❌ 403 to curl. |
| Walmart | ❌ "Robot or human?" CAPTCHA. Not bypassed, by policy. |
| O'Reilly | ❌ Maintenance page. |
| Office Depot, Target | ❌ Prices load client-side only. |
| Headless Chrome (playwright) | ❌ Also blocked by the big-box sites. The browser-use tool errored ("daemon default didn't come up") and was not routed around. |

**Simplest path for Jordan:** spend 10 minutes in a normal browser on homedepot.com / lowes.com /
walmart.com / autozone.com for the open items. Those sites are blocked to tools but fine for a person.
Paste the prices and URLs in, and fill each `cost:` range with the same "prices checked" note.

**Prices filled in this pass (all fetched 2026-10-09):**
| Guide | `cost:` now | Retailers |
|---|---|---|
| Jump start | Cables $11.99–$44.99 (jump pack still [VERIFY]) | Do it Best $34.99/$44.99 (16 ft 6-ga); Meijer $11.99 (12 ft 10-ga), $21.99 (12 ft 8-ga), $43.99 (20 ft 4-ga) |
| Check/add oil | $6.79–$13.49 per quart | Do it Best $8.99/$10.49/$13.49; Meijer $6.79/$9.29/$9.49 |
| Corolla | Oil $6.79–$13.49/qt; filter [VERIFY] | same as above |
| Wipers | $10.99–$26.99 per blade | Do it Best $22.49/$25.49; Meijer $10.99/$15.49/$26.99 |
| Sink | Hair tool $3.79–$7.99 (drum auger [VERIFY]) | Do it Best $6.79/$7.99; Meijer $3.79/$6.99 |
| Mower oil | $10.99–$14.99 per 48 oz SAE 30 | Do it Best $14.99/$14.49; Meijer $10.99 |
| Stud/TV | Stud finder $9.35–$44.99 (TV mount [VERIFY]) | Do it Best $29.99/$44.99; Newegg $9.35/$21.99 (marketplace) |

**Single-retailer only, so left [VERIFY]:** faucet cover (Do it Best $4.99–$5.79), jump pack (Meijer
$118.99), drum auger (Meijer $29.99). **Not priced:** tire gauge / jack stands / torque wrench, spackle /
patch kit, file / blade balancer, TV mount, Corolla filter.

Every exact URL is in each draft's `<!-- SPEC SOURCES -->` / `<!-- PRICE SOURCES -->` comment.

---

## (c) Hosting: GitHub Pages, and the domain

**Current:** https://manskills.github.io/manskillsdiy/ (`_config.yml`: `url: https://manskills.github.io`,
`baseurl: "/manskillsdiy"`).

**GitHub Pages limits (fetched today, https://docs.github.com/en/pages/getting-started-with-github-pages/github-pages-limits):**
source repo recommended under 1 GB; published site no larger than 1 GB; soft bandwidth limit 100 GB/month;
soft limit of 10 builds/hour (unless built with a custom Actions workflow); deploy timeout 10 minutes.
Individual files over 100 MB are blocked by GitHub in general.

**Usage policy matters for this site:** the same page says Pages "is not intended for or allowed to be
used as a free web-hosting service to run your online business, e-commerce site, or any other website
that is primarily directed at either facilitating commercial transactions". A how-to blog with some
affiliate links is primarily content, so it's generally fine. But if the site turns into mostly
product roundups and links, that line gets closer.

Pros: free, HTTPS, custom-domain support, versioned in git, no server to maintain, Jekyll built in.
Cons: old Jekyll 3.10 plugin allow-list on the default builder (fixable with an Actions build); no
server-side redirects or headers; no analytics built in; the commercial-use clause above; limited
image pipeline.

**Recommendation:** stay on GitHub Pages for now. Size is far below limits (all 51 images = 8.9 MB).
Revisit only if (1) traffic approaches the 100 GB/month soft limit, (2) the site becomes mainly
affiliate/commerce, or (3) Jordan wants features Pages can't do. If so, Cloudflare Pages or Netlify can
build the same Jekyll repo with almost no changes.

**DNS check for manskillsdiy.com (2026-10-09, nothing changed):**
- The box's local resolver answers every name with `198.18.0.1` (it even does that for
  manskills.github.io). That's a sandbox/proxy placeholder in a reserved test range, **not real DNS**, so
  I ignored it.
- Real DNS via DNS-over-HTTPS (Google `dns.google` and Cloudflare `cloudflare-dns.com`): **NXDOMAIN** for
  A, AAAA, CNAME, NS, MX, TXT, SOA and for `www.manskillsdiy.com`. The authority section is the `.com`
  root (Verisign), which means the .com registry has no delegation for the name.
- Verisign RDAP (`https://rdap.verisign.com/com/v1/domain/manskillsdiy.com`) returned **HTTP 404**,
  meaning no registration record. (The whois lookup was cut off before it finished.)
- **Conclusion: manskillsdiy.com appears to be unregistered right now.** Nothing points at GitHub. I did
  not register it; that would cost money and requires Jordan.

**If Jordan registers it later:** add a `CNAME` file containing `manskillsdiy.com` and set the custom domain
in repo Settings → Pages. Point apex A records at GitHub's four Pages IPs and `www` CNAME at
`manskills.github.io` (use the current values from GitHub's "Managing a custom domain" doc). Verify the
domain in GitHub to block takeovers, enable "Enforce HTTPS", and then change `_config.yml` to
`url: https://manskillsdiy.com` and `baseurl: ""`. All image paths use `relative_url`, so they keep
working after the baseurl change.

---

## (d) Image hosting: repo vs external

- **Current setup:** 51 JPEGs in `assets/images/<slug>/`, longest side ≤1600 px, recompressed when over 400 KB.
  About 8.9 MB total, roughly 0.8 MB per guide. At that rate, 100 guides would be about 90 MB, still far
  under the 1 GB repo and site recommendations.
- **Recommendation: keep images in the repo.** It's simplest, versioned, and works offline in builds, and
  licenses and attribution live next to the post. Keep the ≤1600 px / ≤400 KB rule. Optionally add
  WebP copies later.
- **When to go external:** if original video or many large photos arrive, or the repo nears about 500 MB.
  Options then: Cloudflare R2/Images or another CDN bucket (costs money; needs Jordan). Avoid hotlinking
  Wikimedia/Flickr originals, because they can change or vanish and attribution gets separated.
- Don't use Git LFS for Pages. Pages doesn't serve LFS objects.
- License hygiene: CC BY-SA images (many of the Commons photos) require a credit on the page, and the
  derivative (the resized copy) carries the same license. The credit lines are already on each image,
  with details in PHOTO-LOG.md.

---

## (e) What Jordan must provide or approve

1. **Approve publishing** each draft (they all keep `needs_fact_check: true` until then).
2. **Original photos** for the 48 shot-list entries (PHOTO-LOG.md), especially the Corolla under-car shots:
   jack-stand points, oil pan vs. transaxle plug, torque wrench on the drain plug.
3. **Corolla:** confirm the Mechanic's factory-manual values against your own manual or the car (engine
   label, filter by VIN). Approve the `featured: false` change (it was set back from true).
4. **Per-vehicle / per-product numbers** you want published as examples (lug torque, wiper sizes, mower oil
   capacity, blade bolt torque). Otherwise the drafts keep deferring to the manual.
5. **10 minutes of manual price checks** in a normal browser for the open cost fields (see (b)), or approval to
   publish with those `cost:` lines removed.
6. **Affiliate decision:** whether and when to apply to Amazon Associates or any other program (I did not
   apply). Until then, links stay `AFFILIATE_LINK_PLACEHOLDER`, and Amazon prices must never be hard-coded.
7. **Domain decision:** register manskillsdiy.com (it appears unregistered) or stay on github.io. Registering
   costs money and is Jordan's call.
8. **Approve the image licensing approach** (CC BY / BY-SA with visible credits). Some sites prefer only
   PD/CC0 to avoid share-alike.
9. **Optional:** add `.post-hero` / `.photo-credit` CSS to `assets/main.scss` (not done; the build renders fine
   without it).
