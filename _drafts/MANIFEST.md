# Drafts manifest: 10 beginner how-to guides (written 2026-10-09)

Not committed or published. Every file has `needs_fact_check: true` and stays in `_drafts/` until
an editor clears the remaining **[VERIFY]** items. Every affiliate URL is `AFFILIATE_LINK_PLACEHOLDER`.
That renders as plain text or "Link coming soon", so the build has no broken links.
"Verified" means the value was checked against the cited source page on 2026-10-09. The source is
listed in the post's `specs:` and `sources:` and in an HTML `<!-- SPEC SOURCES -->` comment in the body.
"Verified" does NOT mean the post has passed final editorial fact-check.

The existing `how-to-change-oil-1991-toyota-corolla.md` was edited on 2026-10-09 (photos, prices, and Manskills Mechanic's must-fix corrections; see below).

| # | File | Title | Category | Verified specs | Still [VERIFY] |
|---|------|-------|----------|----------------|----------------|
| 1 | `how-to-jump-start-a-car.md` | How to Jump Start a Car With Jumper Cables (Step-by-Step) | car-maintenance | Connect order, disconnect order, 6-gauge 16-ft cables, 3–5 min charge, 20–30 min drive (AAA) | Cost; hybrid/EV jump rules (per vehicle) |
| 2 | `how-to-check-and-add-engine-oil.md` | How to Check and Add Engine Oil (Step-by-Step for Beginners) | car-maintenance | Wait a few minutes after shutdown, check monthly, oil color guidance (AAA Club Alliance) | Amount between ADD and FULL (often ~1 qt, varies); oil grade (owner's manual); overfill-effects source; cost |
| 3 | `how-to-check-tire-pressure-and-rotate-tires.md` | How to Check Tire Pressure and Rotate Your Tires at Home | car-maintenance | Placard location, "cold" definition (3 h / <1 mi), monthly checks, 2/32 in + penny test (NHTSA, USTMA); 5,000–7,000 mi rotation, rotation patterns (Bridgestone) | Lug nut torque and socket size (owner's manual); lug re-torque interval; TPMS relearn; cost |
| 4 | `how-to-replace-windshield-wiper-blades.md` | How to Replace Windshield Wiper Blades (Hook-Arm Step-by-Step) | car-maintenance | About 6-month replacement, replace in pairs, check the rear blade (Consumer Reports; page is archival, last updated 2016) | Blade lengths (per vehicle); cost |
| 5 | `how-to-unclog-a-bathroom-sink.md` | How to Unclog a Bathroom Sink Without Chemicals | home-repair | 1-1/4 in lavatory trap, 1-1/2 in kitchen (IRC 2024 P3201.7 via Jaspector summary) | Slip-nut tightening guidance; snake cable size; cost |
| 6 | `how-to-patch-a-hole-in-drywall.md` | How to Patch a Hole in Drywall (Nail Holes to Doorknob Holes) | home-repair | Hole-size methods: nail holes; 1/2–1-1/2 in mesh w/ 1 in overlap; 1-1/2–6 in metal patch, 3 coats, 12 in feather; >6 in 1x3 backers, 1-1/4 in screws (This Old House) | Drywall thickness; coat dry time (per product); EPA lead-paint link; cost |
| 7 | `how-to-change-lawn-mower-oil.md` | How to Change Lawn Mower Oil (Walk-Behind Mower) | small-fixes | SAE 30 above 40°F, 10W-30 / synthetic 5W-30, SF–SJ+ detergent oil, once per season or 25 h, ~5 h break-in change, air-filter side up (Briggs & Stratton) | Oil capacity (15–20 fl oz from a third-party chart only); drain plug drive size per model; cost |
| 8 | `how-to-find-a-stud-and-hang-a-heavy-tv-or-picture.md` | How to Find a Stud and Hang a Heavy TV or Picture Safely | home-repair | 16 in typical stud spacing (rarely >24 in), 1-1/2 x 3-1/2 in actual 2x4, 1/16 in test hole (HGTV) | Lag bolt size/penetration (mount instructions); anchor weight ratings (package); CPSC tip-over link; cost. Family Handyman stud-finder page read 2026-10-09 and kept as a source. |
| 9 | `how-to-sharpen-a-lawn-mower-blade.md` | How to Sharpen a Lawn Mower Blade (and Balance It) | small-fixes | Air filter/carb side up, 5/8 in bolt or cone balancer, no nail (Craftsman/Sears manual); sharpen outer 3–4 in, keep bevel (blade sharpener PDF) | Blade bolt torque and socket size (operator's manual); sharpening frequency; replacement blade part no.; cost |
| 10 | `how-to-winterize-an-outdoor-faucet.md` | How to Winterize an Outdoor Faucet (Hose Bib) So Pipes Don't Burst | home-repair | Red Cross core steps (drain hoses, close inside valve, open and leave open outside bib); bleeder cap and frost-free hydrant handling (Boshart, Prima Plumbing) | Temperature threshold (no primary source found; the often-quoted "20°F" was left out); frost-free identification tips; cost. Red Cross hose-bib steps confirmed word-for-word by Manskills Mechanic (direct fetch, 2026-10-09). |

## Mechanic review nits applied (2026-10-09)
The recommended non-blocking nits from `FACTCHECK-REPORT.md` were applied to all 10 drafts: jump-start crank
time and battery lean warning; oil overfill FAQ; hot-tire and 50–100 mi lug re-torque; AUTO wipers OFF;
remove stopper before plunging and add safety glasses; 10–12 in knife, mud pan, and drywall thickness; mower air-filter
check and 25–50 h interval; TV plate into at least two studs, no anchors, full-motion leverage; blade gloves,
wrench direction, and adapter/key check; spring faucet order. Mechanic-supplied values that still lack a citable
primary source keep their `[VERIFY]` tag: the overfill effects, lug re-torque interval, and drywall thickness. `needs_fact_check` was not changed.

## Applies to every file
- `cost:` now has a two-retailer price range with a "prices checked Oct 9, 2026" note in 6 guides plus the Corolla. Faucet, drywall, tires, and blade are still `[VERIFY]`, as are the jump-pack, drum-auger, TV-mount, and Corolla-filter parts of the other cost lines. No prices were invented.
- Hero `image:` and `image_alt:` are set in all 11 drafts. Licensed photos are in `assets/images/<slug>/` (see `PHOTO-LOG.md`).
- `last_updated: 2026-10-09`, `author: manskills` (byline "Manskills DIY"), `featured: false`.
- Build check: `jekyll build --drafts` succeeds on a scratch copy outside the repo (the repo's Gemfile
  did not resolve locally). All 10 render, no `PLACEHOLDER` hrefs are emitted, and unverified rows
  show the "Not yet verified" badge.

## Possible next topics (from Jordan's list, not written)
Spare tire change, cabin air filter, basic multimeter use, drill/driver basics, padlock/hasp
install, seasonal tire storage, LED shop light wiring safety, garage floor epoxy overview.

## Photos, prices and verification pass (2026-10-09, second pass)
- Backup of `_drafts/` before editing: `/workspace/backup-drafts-1427/` (outside the repo).
- **Images:** 51 licensed images (PD, CC0, CC BY 2.0–4.0, CC BY-SA 3.0–4.0), about 8.9 MB, in `assets/images/<slug>/`.
  Each has a hero in front matter, body images with alt text and a visible credit line, and paths via `relative_url`.
  48 shot-list entries for original photos are in Liquid comment blocks and `PHOTO-LOG.md`.
- **Newly verified (fetched today):** EPA lead link (drywall); CPSC Anchor It! link (stud/TV); drywall
  thickness per IRC R302.6 (this corrected the old "garage walls are 5/8 in" claim); blade sharpening frequency (B&S manual example).
- **Prices:** ranges from Do it Best plus Meijer/Newegg for jump cables, motor oil (check-oil + Corolla), wipers,
  hair clog tool, mower oil, and stud finder. Source URLs are in each draft's HTML comment. Big-box sites block automated fetches.
  See `INDEPENDENCE-PLAN.md` (b).
- **Corolla (Manskills Mechanic must-fix):** jacking points (front crossmember, pinch-weld stands, rear chocks,
  under-covers), viscosity 10W-30/10W-40 >0°F and 5W-30 <~50°F with API SP wording, capacity with vs. without filter,
  filter fitment (YZZN1 for all, YZZF1 coupe alternative, confirm by VIN), drain plug 90341-12012 / gasket 90430-12031 /
  25 ft-lb, 3/4-turn filter install, FAQ interval 7,500 mi/12 mo and 3,750 mi/6 mo, All-Trac note, step 13
  "pour ~3 qt then top up", garage.wiki and motospecsource dropped. Specs are marked verified citing the Toyota factory
  repair manual **per the Mechanic's reading**; not independently re-fetched in this pass. `featured: false`,
  `needs_fact_check: true`.
- Plan for the remaining items: `INDEPENDENCE-PLAN.md`. Photo licenses: `PHOTO-LOG.md`.
