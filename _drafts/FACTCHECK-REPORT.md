# Fact-check report — Manskills DIY batch 1
Date: 2026-10-09
Reviewer: Manskills Mechanic

## Summary
- 10 PASS / 0 FAIL out of 10
- Overall: Technically sound batch. No dangerous advice, no invented torque/capacity numbers (vehicle- and model-specific values correctly defer to the manual), and steps are in a safe order. Everything below is non-blocking polish. The few nits marked **(recommended)** are worth doing before publish because they close small safety or sequence gaps. Remaining `[VERIFY]` cost/link placeholders are editorial items, not technical errors.

Scope notes:
- Corolla oil-change draft skipped as instructed. Affiliate URLs ignored.
- Spot-checks done today: Bridgestone tire-rotation page (5,000–7,000 mi, "cross to drive" modified cross, four-tire cross for 4WD, directional front-to-rear only, no temp spare) matches the draft. Briggs & Stratton oil-change FAQ (first change after 5 h, check oil before each use, don't pour the whole bottle, sandwich-bag trick, warm the engine first) matches the draft. Briggs now says the change interval depends on the engine model and points to the operator's manual. American Red Cross frozen-pipes page: **direct fetch succeeded today**, and the hose-bib steps quoted in the winterize draft are confirmed word for word. The MANIFEST "re-check before publishing" note on that source can be cleared.
- All other judgments are standard shop/trade practice applied to the draft text.

## Per guide

### how-to-jump-start-a-car.md
- Verdict: PASS
- Issues:
- Corrections:
- Optional nits:
  - **(recommended)** Step 9 says "Don't crank for long stretches," which is vague. Make it "Crank no more than about 5–10 seconds at a time, then rest a minute or two" so the starter doesn't overheat.
  - Safety: add "Don't lean over either battery while connecting or cranking." It goes naturally with the hydrogen warning.
  - Step 2 / applies_to: add "Confirm both vehicles are 12-volt systems" (this matters for some older and heavy-duty trucks and equipment).
  - Step 3: if the terminals need brushing, do it before any clamp goes on, and wear gloves. Battery corrosion is acidic. Step order already supports this; the wording just needs to say it.
  - Hybrid/EV `[VERIFY]` is correctly left to the owner's manual.

### how-to-check-and-add-engine-oil.md
- Verdict: PASS
- Issues:
- Corrections:
- Optional nits:
  - Overfill FAQ `[VERIFY]`: the general mechanic consensus (and Briggs' small-engine FAQ says the same) is that overfilling is as harmful as running low. Excess oil can be churned by the crankshaft and foam, and can push past seals. Suggested wording: "If it's more than about half a quart over FULL, have the excess drained." Any manufacturer manual can serve as the source.
  - Step 10 "start with about half a quart" is good practice. Optionally add "if the level is at ADD, most engines need roughly one quart to reach FULL, but go by the dipstick." This keeps the value marked as vehicle-specific.
  - Some manufacturers (e.g., certain BMW, Mercedes, newer GM/Honda) want the engine at full operating temperature with a specific wait. The draft already says "follow your manual," which is fine.
  - Common mistakes: add "using the wrong oil grade" alongside the wrong-cap item.

### how-to-check-tire-pressure-and-rotate-tires.md
- Verdict: PASS
- Issues:
- Corrections:
- Optional nits:
  - **(recommended)** FAQ "check pressure after driving": add "Never let air out of hot tires to bring them down to the placard number. They will be underinflated once they cool." This is NHTSA/USTMA guidance. The current text isn't wrong, but this is the classic mistake.
  - **(recommended)** Lug-nut re-torque `[VERIFY]`: standard tire-shop practice is to re-check torque after the first 50–100 miles. Replace "after a short drive" with that, or keep deferring to the owner's manual or the tire shop.
  - Part 2 step 5 (two stands, one side): add "Jack only at the manufacturer's front and rear lift points on that side, never in the middle of the rocker, and chock both wheels on the side that stays down."
  - Rotation-pattern spec: confirmed against Bridgestone today. Optionally put "cross to drive" in the body text and add a simple diagram. Right now the body only says "look it up."
  - Before mounting each wheel, wipe rust and dirt off the hub face and wheel mounting face. Don't oil the lug threads unless the manual says to (lubed threads over-torque).
  - Tools: add work gloves. Optionally add a wire brush for hub faces.
  - Lug socket size and torque are correctly left to the manual. Do not add a generic number.

### how-to-replace-windshield-wiper-blades.md
- Verdict: PASS
- Issues:
- Corrections:
- Optional nits:
  - **(recommended)** Safety/step 2: add "If your car has rain-sensing (AUTO) wipers, switch them fully OFF, not AUTO, and turn the ignition off. Auto wipers can sweep unexpectedly when the glass gets wet."
  - Step 4: service position on many cars requires the ignition off, then a wiper-stalk tap within a few seconds. "Check the manual" already covers this.
  - The Consumer Reports source is archival (2016). The 6-month and pairs guidance is still standard, but consider adding a current OEM or blade-maker source.
  - Step 9: adding "lower the arm by hand all the way to the glass; never let go mid-air" would reinforce the existing advice.

### how-to-unclog-a-bathroom-sink.md
- Verdict: PASS
- Issues:
- Corrections:
- Optional nits:
  - **(recommended)** Step 6 (plunge): plunge with the pop-up stopper removed or fully open, or the stopper blocks the drain and you mostly push water around it. Either reorder (plunge before reinstalling the stopper in step 5) or add "remove the stopper first."
  - Tools: safety glasses are in Safety but missing from the tools list. Add them.
  - Step 7: tell readers to wrap pliers jaws with a rag or tape on chrome traps. Also warn that old chrome/brass traps can be corroded paper-thin and may crumble, so they should be ready to replace the trap.
  - Slip-nut `[VERIFY]`: "hand-tight plus about a quarter turn with pliers if it weeps" is standard trade practice for plastic slip joints. The current text is fine.
  - Snake `[VERIFY]`: 1/4 in cable is the standard hand-auger size for 1-1/4 to 2 in drains. The choice is correct.

### how-to-patch-a-hole-in-drywall.md
- Verdict: PASS
- Issues:
- Corrections:
- Optional nits:
  - Drywall thickness `[VERIFY]`: 1/2 in is standard for interior walls, 5/8 in for ceilings and fire-rated walls (e.g., garage/house separation), and some older homes use 3/8 in. Keep "measure at the hole edge."
  - Large holes step 2: specify that backer boards should run about 2 in past the top and bottom of the opening. Tell readers to hold the board by a screw driven partway into its middle (a temporary handle) so it can't fall into the wall cavity. If a stud is exposed at an edge, screw to it.
  - Tools: add a 10–12 in taping knife (you can't feather to about 12 in with a 6 in knife) and a mud pan.
  - Lead `[VERIFY]`: the pre-1978 statement is correct (EPA). Link EPA's lead-safe renovation (RRP) page before publish.
  - Medium holes step 2: "pushing it through the mesh" is right. Also tell readers not to press hard on a metal patch.

### how-to-change-lawn-mower-oil.md
- Verdict: PASS
- Issues:
- Corrections:
- Optional nits:
  - **(recommended)** Add a step after draining: "Check the air filter. If oil got on it during tipping, replace it (paper) or clean it (foam) before starting." Otherwise the engine smokes heavily or won't start, and step 11 only half-covers this.
  - Change interval: Briggs' current oil-change FAQ says the interval depends on the engine model (see manual), with the first change after 5 h on new engines. Many current Briggs walk-behind manuals say every 50 h or once per season. "Once per season or 25 hours" is conservative and safe. Optionally reword to "once per season or every 25–50 hours per your engine manual, sooner in dusty or hot conditions."
  - Capacity: 15–20 fl oz is a realistic range for walk-behind engines (e.g., many Briggs 450–675 series about 15–18 oz; Honda GCV160 about 0.4 L / 13.5 oz). Optionally widen to "about 13–20 fl oz." The "fill to the dipstick" instruction is the important part, and it's there.
  - Step 2 vs step 4: if the reader plans to run the tank nearly empty, that should happen during the warm-up run. A small wording tweak fixes this.
  - Tools: add safety glasses (oil can splash when tipping).
  - The 3/8 in square-drive drain plug note is accurate for many Briggs engines.

### how-to-find-a-stud-and-hang-a-heavy-tv-or-picture.md
- Verdict: PASS
- Issues:
- Corrections:
- Optional nits:
  - **(recommended)** TV section, structural load: state explicitly "Lag the wall plate into at least two studs (most mounts require this), into the center of each stud." Also say "If the plate's slots don't line up with your studs, don't put one side into drywall anchors. Use a mount with a wider plate or have it mounted to a properly fastened backer board." Add "Full-motion/articulating arms put far more leverage on the bolts than flat mounts. Stay within the mount's rating for weight and extension." The draft covers the basics (rated mount, studs not anchors), but these three lines are what actually prevent a TV coming off the wall.
  - Step 4 (pilot holes): if the pilot bit punches into empty space past the drywall, don't drive the lag there. Move to the stud center. This is already implied by the find-a-stud step 5; repeat it here.
  - Step 5: "snug, don't over-torque" is right. Optionally add "stop when the washer seats firmly and the plate can't move. Overdriving strips the wood and weakens the hold."
  - Applies_to: metal studs are correctly excluded. Optionally add "if the pilot hole hits metal, stop; you need toggle-type fasteners rated for metal studs and the mount maker's approval."
  - Family Handyman source: the MANIFEST says it hasn't been read. Either read it or drop it from `sources:`.
  - CPSC tip-over `[VERIFY]`: link CPSC's Anchor It! page.

### how-to-sharpen-a-lawn-mower-blade.md
- Verdict: PASS
- Issues:
- Corrections:
- Optional nits:
  - **(recommended)** Step 6: tell readers to wear heavy gloves while gripping or levering the blade, and to always pull the wrench away from the cutting edge so a slip doesn't drive a hand into the blade.
  - Step 6: mention the blade adapter/key (on many mowers a small key or shear pin locates the blade). Inspect it and replace it if it's sheared or deformed, because a damaged key lets the blade slip.
  - Step 11 balance: "take metal off the heavy end, not the cutting edge" is fine. The Craftsman manual phrasing is "sharpen the heavy end until balanced." Either works; keep it consistent with the cited source.
  - Torque and socket `[VERIFY]`: correctly deferred to the manual. Many walk-behinds fall in the 35–50 ft-lb range, but do not publish a generic number.
  - Sharpening frequency `[VERIFY]`: "once or twice a season, or about every 20–25 hours of mowing, sooner with sandy soil or after hitting rocks" is common practice. Mark it as general guidance.
  - Tools: add a face shield (or at least safety glasses) when using a bench grinder. Glasses are listed; for grinder work, recommend a face shield.

### how-to-winterize-an-outdoor-faucet.md
- Verdict: PASS
- Issues:
- Corrections:
- Optional nits:
  - **(recommended)** Step 11 (spring): add "close the outdoor faucet first (or crack it only slightly to purge air), then open the indoor valve slowly." As written, the outside faucet was left open over winter, so turning the indoor valve on sprays water outside. That's not dangerous, but it's a sequence gap.
  - Red Cross source: **confirmed by direct fetch on 2026-10-09.** The exact text is "Close inside valves supplying outdoor hose bibs. Open the outside hose bibs to allow water to drain. Keep the outside valve open..." Clear the MANIFEST re-check note. Note also that Red Cross's antifreeze line refers to pool/sprinkler lines. The draft's "No antifreeze in drinking-water lines" is still correct practice.
  - FAQ open vs. closed: consider recommending one default. "Leave it open" (Red Cross) is the safer beginner default, because an indoor valve that weeps will drip out rather than refill and freeze.
  - Frost-free identification `[VERIFY]`: practical tips are that the handle sits on a body that extends 4–12+ in through the wall, the valve seat is inside the heated space, and frost-free hydrants should pitch slightly down toward the outside so they drain.
  - Temperature threshold: leaving out "20°F" is the right call. "Before the first hard freeze" is sufficient.

## Corolla 1991 oil change (reviewed 2026-10-09)
File: `how-to-change-oil-1991-toyota-corolla.md` (4A-FE base / 4A-GE GT-S)

- Verdict: **FAIL (minor; fixable in one edit pass).** Every number Kiwi claimed checks out against the Toyota factory repair manual. The problems are an incomplete viscosity spec, missing vehicle-specific jacking points, an unclear capacity explanation, and oversimplified filter fitment. This is a vehicle-specific, `featured: true` guide, so those all have to be right before publish.

### Primary source used
Toyota factory repair manual for the AE92/AE95 Corolla (covers 4A-FE, 4A-GE and the AE95 All-Trac 4WD). It's the PDF hosted at `https://jdmfsm.info/Auto/Japan/Toyota/Corola/Corolla_1989_All-Trac_Manual.pdf` (filename says 1989; same AE92 generation as the 1991 US car). Pages read on 2026-10-09:
- **LU-7/LU-8** (Replacement of Engine Oil and Oil Filter): drain plug torque, filter procedure, capacities.
- **LU-5** (Recommended Viscosity chart).
- **EM** engine-install refill steps and **MA-2/MA-3/MA-5** (4A-FE and 4A-GE capacity restated, maintenance schedules).
- **IN-5/IN-27** (Vehicle Lift and Support Locations).

Cross-check: the Operation CHARM 1991 Corolla Wagon 4A-FE spec page shows "Capacity with filter 3.4, SG or better, 10W30 or 10W40". I saw that **in a search-index snippet only** because the direct fetch timed out (504), so treat it as corroboration, not a primary citation. Parts data came from ToyotaPartsDeal catalog pages fetched today.

### Issues
1. **Viscosity is incomplete.** The factory chart (LU-5) shows **10W-30 and 10W-40 for temperatures above 0°F (−18°C)** and **5W-30 below about 50°F (10°C)**. The draft drops 10W-30, and its "sources" are AMSOIL, engineoildb and motospecsource rather than Toyota. The API grade is also missing. Toyota specified **API SG, multigrade, fuel-efficient**. SG is long obsolete, so readers need modern wording.
2. **Capacity discrepancy isn't explained, and the sources are third-party.** The FSM confirms Kiwi's numbers. The "~3 qt / 3.0 L" figures are **without-filter** values (3.0 L = 3.1–3.2 US qt for the 4A-FE), and garage.wiki's table is for non-US Liftback/Compact variants (it lists 1C diesels, for example), so it's not applicable. The guide should state with-filter vs. without-filter and cite the FSM.
3. **Jacking is vague for a vehicle-specific guide (safety).** Step 3 says "Jack at the front lift point." The FSM (IN-27) gives the AE92 front **floor-jack point as the center of the engine mounting center member** (front crossmember), with **safety stands at the rocker pinch-weld support points**. The FSM (IN-5) also requires chocking the wheels at the opposite end and never working under a car on a jack alone. A beginner who guesses "lift point" can end up jacking on the oil pan.
4. **Filter fitment is oversimplified.** The Toyota catalog lists **90915-03001 → superseded by 90915-YZZN1** for all 1987–93 AE92 *and* AE95 codes, coupes included (AE92L-ACMVFA etc.). **90915-YZZF1 (supersedes 90915-03004)** is listed only for the **AE92 coupe codes (AE92L-AC…)**, not sedans, wagons or AE95. The draft implies YZZN1 is 4A-FE-only and YZZF1 is the 4A-GE filter. In fact YZZN1 fits both engines, and YZZF1 is a coupe-only alternative. Per the catalog, YZZN1 also supersedes 90915-10001 and 90915-10003. 90915-YZZD1 doesn't appear in any 1991 Corolla fitment I found; don't list it.
5. **Engine under covers aren't mentioned.** The FSM references RH and LH engine under covers on these cars. If they're fitted, they may need to come off for drain plug or filter access.
6. **All `specs:` rows are still `status: verify`** with secondary sources, even though primary values now exist. That's an editorial gate, but it blocks publish.

### Corrections (concrete edits for Kiwi)
1. **specs → Oil viscosity.** Replace the value with:
   "API SG or later multigrade (any current API SP / ILSAC-licensed oil meets this). SAE 10W-30 or 10W-40 if temperatures stay above 0°F (−18°C); SAE 5W-30 if temperatures will be below about 50°F (10°C) before the next change."
   Set `status: verified`, source "Toyota AE92 repair manual, LU-5 viscosity chart." Drop the motospecsource/AMSOIL attribution, or move it to secondary.
2. **specs → Oil capacity.** Replace with:
   "Drain and refill WITH filter: 4A-FE 3.2 L (3.4 US qt); 4A-GE 3.7 L (3.9 US qt). Without filter: 4A-FE 3.0 L (3.2 qt); 4A-GE 3.4 L (3.6 qt). Always finish on the dipstick ('F' mark)."
   Set `status: verified`, source "Toyota AE92 repair manual LU-7/LU-8, MA-5." Remove garage.wiki (wrong market) and the motospecsource "3 qt" from the source line. Add one line in the body: "The ~3-quart figures you'll see online are the without-filter number."
   Step 13: change to "Pour in about 3 quarts, cap it, then top up after the leak check" so readers don't overfill a 3.4 qt engine.
3. **Step 3 (jacking).** Replace with:
   "Chock both rear wheels. Put the floor jack under the center of the front engine crossmember (Toyota's front jack point), never on the oil pan. Lift, then set jack stands under the front pinch-weld support points on each side, just behind the front wheels. Lower onto the stands and shake-test before going under. Or drive onto ramps and chock the rear wheels."
   Add a note: "Some cars have plastic engine under covers; remove them if they block the drain plug or filter, and reinstall after."
4. **specs → Oil filter.** Replace with:
   "Toyota 90915-YZZN1 (supersedes original 90915-03001); Toyota's catalog lists it for all 1991 Corolla sedans, wagons, coupes (including GT-S 4A-GE) and All-Trac. Coupes also list 90915-YZZF1 (supersedes 90915-03004). Confirm by VIN at the parts counter."
   Set `status: verified`, source the ToyotaPartsDeal 1991 Corolla oil-filter page and the 90915-YZZF1 fitment page.
5. **specs → Drain plug / torque.** Set `status: verified`:
   - "Torque 25 ft-lb (34 N·m, 350 kg-cm): Toyota AE92 repair manual LU-7."
   - "Plug 90341-12012 (supersedes 90341-12026), M12×1.25, 14 mm head: Toyota catalog fitment includes all AE92/AE95; head size per Auveco cross-reference."
   - Add a materials line: "**New drain plug gasket: Toyota 90430-12031** (supersedes 90430-12027, listed 'for oil pan drain plug' on all 1991 AE92/AE95). Replace every change, as the FSM specifies 'install the drain plug with a new gasket.'"
   - Keep "6-point socket" as advice. The FSM doesn't specify it.
6. **FAQ interval.** Replace the `[VERIFY]` with:
   "Toyota's original schedule: every 7,500 miles or 12 months under normal use (Schedule B), every 3,750 miles or 6 months for severe use like short trips in freezing weather, towing, dusty roads or lots of idling (Schedule A). On a 35-year-old engine, the severe schedule is the safer default."
   Source: FSM MA-2/MA-3.

### Optional nits (non-blocking)
- Step 11: cite the factory spec. "Spin on until the gasket touches, then ¾ turn more" (FSM LU-7). It agrees with "the turn printed on the filter."
- Step 10 is correct (FSM: clean the mount surface, oil the new gasket). Optionally add "check the new filter's gasket is seated in its groove."
- Steps 14–15: the sequence matches the FSM (start, check for leaks, recheck level). Optionally add "check the level with the car back on level ground, about 5 minutes after shutdown."
- Safety: optionally add the FSM's used-oil skin warning ("prolonged contact can cause dermatitis; used oil contains contaminants. Wear oil-proof gloves and wash with soap"). Gloves are already listed. Disposal wording is fine and already includes the filter.
- applies_to / FAQ: mention that the 1991 **All-Trac (AE95, 4WD) wagon** uses the same 4A-FE, plug, filter and procedure, but its rear jack point is the rear axle housing (IN-27). That only matters if someone lifts the rear. The SR5 coupe is a 4A-FE.
- Dry-fill numbers (after an engine rebuild only, don't publish as change capacity): 4A-FE 3.7 L (4.1 L with oil cooler), 4A-GE 4.1 L.
- `featured: true` while `needs_fact_check: true`: flip to false until corrections land.
- Step 5 shot list (oil pan vs. transaxle plug) is good. Keep it.

### Spec table
| Spec | Kiwi's claim | Verified value | Source |
|---|---|---|---|
| Capacity w/ filter, 4A-FE | 3.4 qt (3.2 L) | **3.2 L = 3.4 US qt** ✔ (LU page prints 3.3 qt; rounding) | Toyota AE92 RM LU-7, MA-5, EM refill step; CHARM 1991 snippet (3.4) |
| Capacity w/ filter, 4A-GE | 3.9 qt (3.7 L) | **3.7 L = 3.9 US qt** ✔ | Toyota AE92 RM LU-7, MA-5, EM refill step |
| "~3 qt / 3.0 L" figures | discrepancy | **Without-filter** value (4A-FE 3.0 L / 3.1–3.2 qt; 4A-GE 3.4 L / 3.6 qt). garage.wiki = non-US variants | Toyota AE92 RM LU-7 |
| Viscosity | 10W-40 >0°F; 5W-30 <50°F | **10W-30 or 10W-40 above 0°F; 5W-30 below ~50°F** ✖ (10W-30 missing) | Toyota AE92 RM LU-5 chart |
| Oil grade | not stated | **API SG multigrade, fuel-efficient** (use current API SP or later) | Toyota AE92 RM LU-7, MA-5 |
| Drain plug | 90341-12012, 14 mm 6-pt | **90341-12012** (supersedes -12026), M12×1.25, 14 mm head ✔. "6-pt" is advice only | ToyotaPartsDeal drain plug fitment; Auveco/Fastener Zone cross-ref |
| Drain plug torque | 25 ft-lb | **25 ft-lb / 34 N·m / 350 kg-cm** ✔ | Toyota AE92 RM LU-7 |
| Drain plug gasket | "new crush washer" (no P/N) | **90430-12031** (supersedes 90430-12027); new every change | ToyotaPartsDeal 1991 Corolla drain-plug-washer page; Toyota RM LU-7 |
| Oil filter, 4A-FE | 90915-YZZN1 | **90915-YZZN1** (ex-90915-03001) ✔ | ToyotaPartsDeal 1991 Corolla sedan/wagon oil-filter page |
| Oil filter, 4A-GE | 90915-YZZF1 | **YZZN1 also listed for GT-S coupe codes**; YZZF1 (ex-90915-03004) listed for AE92 coupe codes only. Partly ✔; reword | ToyotaPartsDeal 90915-03001 and 90915-YZZF1 fitment pages |
| Filter tightening | "extra turn printed on filter" | **Gasket contact + ¾ turn** (compatible) | Toyota AE92 RM LU-7 |
| Jack / support points | "front lift point" | **Front jack: center of engine mounting center member; stands: pinch-weld support points; chock opposite wheels** ✖ (too vague) | Toyota AE92 RM IN-5, IN-27 |
| Change interval | [VERIFY] | **7,500 mi / 12 mo (Schedule B); 3,750 mi / 6 mo (Schedule A, severe)** | Toyota AE92 RM MA-2/MA-3 (4A-FE schedule) |
