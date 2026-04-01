# Lose Condition

As the king's advisor you must fulfill your duties to the kingdom and its citizenry. Failing to do so raises distrust. Performing questionable, secretive, or overtly ambitious acts increases suspicion among those close to the king.

## Two Parallel Failure Tracks

1. Distrust (Public / Administrative) – Missed obligations to officials, guilds, populace.
2. Suspicion (Court / Inner Circle) – Perceived disloyalty or plotting by the king, spymaster, guards.

You lose if either:
- Suspicion reaches 100% (king moves against you / arrest / execution scene).

(Administrative Distrust now inflicts escalating Punishments instead of outright loss; these punishments indirectly jeopardize victory by draining resources / time / credibility.)

## Core Metrics & Player Feedback

### Distrust (Strikes: 0–3 -> Punishment Threshold)
- Representation: Explicit 3-slot indicator (e.g., three royal seals). Slots fill as Strikes accrue; upon filling the 3rd slot a Punishment Event triggers instead of game over.
- Post-Punishment Reset: After resolving a punishment, Strikes reduce to 1 (lingering stigma) so the player cannot chain-reset to 0 and must still stabilize. (Optional variant: reset to 0 on Easy difficulty.)
- Sources: Missed deadlines, failing mandatory reports, ignoring crises, public scandals.
- Feedback: Immediate notice: "Strike (2/3): Treasury shortfall ignored." At 3rd: "Administrative Punishment Imposed: Treasury Dock."
- Decay: Strikes do not decay passively. Specific Rehabilitation Actions (e.g., Overdeliver on Census, Sponsor Civic Audit) can clear 1 Strike (cost Influence; +4–6 Suspicion) with a cooldown.
- Escalation Memory: Each Punishment increases a hidden Severity Tier (Minor, Moderate, Major, Dire) that weights future punishment outcome rolls.

### Administrative Punishments (Triggered On 3rd Distrust Strike)
- Selection Method: Weighted random by current Severity Tier; player sees 2 rolled options and chooses one (agency under pressure) unless Dire Tier (forced).
- Severity Scaling: Each punishment raises Severity Tier by 1 (cap at Dire); performing a Rehabilitation Action lowers Tier by 1 (min Minor) but adds +5 Suspicion (people wonder at sudden diligence).
- Example Punishments:
  - Minor (Tier 1): Pay Fine (lose 5 gold), Stipend Cut (-2 income for 2 turns), Extra Reports (reserve 1 Time slot next 2 days or gain +1 Strike immediately).
  - Moderate (Tier 2): Public Reprimand (-1 Influence, +2–4 Suspicion due to eyes on you), Forced Overtime (lose 2 flexible Time units next cycle), Asset Audit (one Support Asset disabled 3 days unless you spend gold to expedite).
  - Major (Tier 3): Budget Seizure (-8 gold; if insufficient, auto-loan adding recurring -1 gold upkeep), Mandated Transparency (Suspicion decay paused 3 days; any covert action during this adds +50% Suspicion), Personnel Reassignment (lose one specialized aide until you host a Loyalty Banquet).
  - Dire (Tier 4): Emergency Oversight Council (all administrative task deadlines shorten by 1 day for a week), Loyalty Oath Tour (must spend 3 Time in public ceremonies or gain +2 Strikes), Royal Inquiry (converts next gained Strike into +10 immediate Suspicion instead of normal effect).
- Strategic Impact: Punishments reshape scheduling windows, pushing risk toward Suspicion (extra scrutiny) or future Distrust (compressed deadlines), reinforcing interdependence.

### Suspicion (0–100%)
- Representation: Primarily hidden; only qualitative tiers shown unless you invest in an Intel action. Tiers: Calm (0–20), Watchful (21–40), Unease (41–60), Scrutiny (61–80), Crisis (81–90), Imminent (91–99), Trigger (100).
- Sources: Secret meetings, illicit resource rerouting, contradictory alibis, failed cover stories, being present in restricted zones off-hours.
- Feedback: Ambient dialogue shifts, guarded wording from NPCs, additional minor audits. Optional Insight action (cost) reveals exact % for a day.
- Decay: Small passive decay only below 40. Active reduction via Loyalty Displays (public donations, aiding king's agenda) which often delay other tasks (risking Distrust) or burn Influence.

## Progression & Lead-Up Examples

Below, each encounter shows: Setup -> Player Choices -> Immediate Effects -> Escalation Signals -> Mitigation Opportunities -> Failure Outcome.

### 1. Royal Treasurer Funding Request (Distrust Track)
- Setup (Day 5): Treasurer: "We require 5 gold for militia wages by dusk tomorrow."
- Choices:
  A) Pay Now (spend 5 gold) – Safe, no gain.
  B) Negotiate Delay (skill check) – Success: +24h extension; Failure: +1 Strike.
  C) Reallocate From Festival Budget (secret) – Cover check: Success: Pay with no gold cost but +6–10 Suspicion; Failure: +1 Strike & +10 Suspicion.
  D) Stall (ignore) – After deadline passes: +1 Strike.
- Lead-Up Dynamics: If this is your 2nd Strike overall, UI subtly pulses slot 3 outline when time < 8h remaining. If already at 2 Strikes, risk tooltip: "Third Strike triggers Punishment Roll."
- Escalation Signals: Clerk murmurs about "unpaid warrants" (UI hint blinking yellow on meter slot 1/2 depending stage).
- Mitigation: Commission Emergency Levy (cost Influence, +5 Suspicion) before nightly ledger to satisfy requirement retroactively (removes pending Strike if not yet logged). Rehabilitation Action (Overfund Militia) available only if no Punishment this chapter; clears 1 Strike but adds +4 Suspicion.
- Punishment Interaction: If this becomes 3rd Strike, sample Minor Punishment choices appear: (A) Pay Fine (-5 gold) or (B) Extra Reports (reserve 1 Time slot next 2 days). Player picks one; Strikes reset to 1; Severity Tier increases if Extra Reports chosen (because perception of systemic failure).
- Failure Outcome (Indirect): Chosen punishment constrains resources, possibly causing future missed deadlines -> recurring cycle.

### 2. Guard Captain's Theft Investigation (Distrust + Suspicion)
- Setup: Armory theft reported; you have 2 in-game days to present a culprit.
- Choices:
  A) Conduct Proper Inquiry (allocate Time blocks) – Consumes 2 time units; success rate scales with Investigator asset.
  B) Frame Petty Thief (fast) – +12–18 Suspicion if truth later uncovered (delayed check), immediate avoidance of Strike.
  C) Ignore (focus on plotting) – On deadline: +1 Distrust Strike.
  D) Secretly Recover Goods via Underworld Contact – Success: No Strike, +8 Suspicion (contact observed); Failure: +1 Strike & +15 Suspicion.
- Lead-Up Additions: If currently at 2 Strikes when deadline nears, Captain's tone changes earlier; you gain a prompted "Quiet Settlement" option (spend gold +3 Suspicion to avert the impending Strike) only if Severity Tier <= Moderate.
- Escalation Signals: Captain requests interim report (midpoint). If you have nothing: UI tooltip warns: "Strike risk rising (50%)."
- Mitigation: Partial Progress Report grants 24h extension (one per chapter) at cost +4 Suspicion (appears like excuse).
- Punishment Hook: If the third Strike triggers here, Moderate Punishment examples could include Asset Audit or Forced Overtime, both making future investigative tasks harder (feedback loop).

### 3. Midnight Archive Visit (Suspicion Track)
- Setup: Need classified ledger to unlock powerful leverage (win progress).
- Choices:
  A) Daytime Formal Request – Low Suspicion (+2) but delays ledger 2 days (risking another duty's deadline -> potential Distrust).
  B) Night Break-In – Base +10 Suspicion; stealth check can reduce to +4 or escalate to +18 if caught.
  C) Bribe Archivist – +6 Suspicion, -3 gold, immediate access.
  D) Wait for Festival Distraction – Requires planning (schedule alignment), 0 Suspicion cost but consumes 3 time units setup.
- Escalation Signals: After any two nocturnal movements within 3 nights, Spymaster issues a "Routine Audit" (dialogue shift, tier possibly advances to Unease).
- Mitigation: Public Charity Event (cost gold) lowers Suspicion tier one step if <= Scrutiny.
- Failure Outcome (Suspicion 100 during audit): Immediate arrest sequence -> lose.

### 4. Court Gossip Spiral (Slow Suspicion Accumulation)
- Setup: After performing 3 covert actions in a chapter, gossip event seeds.
- Passive Effect: Each additional covert action in same chapter adds +3 Suspicion (instead of +1 baseline) until you perform a Publicly Loyal Act.
- Choices to Break Spiral:
  A) Sponsor Tourney – -8 Suspicion, +1 Favor (win resource), consumes 2 time units (risking duty deadlines).
  B) Hold Open Court – -5 Suspicion, chance of emergent side-quests (new potential Distrust obligations if ignored).
  C) Ignore – Spiral persists; ambient lines: "Have you noticed the advisor's late hours?"
- Failure Contribution: Spiral can silently push you from Watchful to Scrutiny without a single dramatic event.

### 5. Final Warning Bridge (Suspicion 91–99)
- Trigger: Enter Imminent tier.
- Event: King assigns personal guard "for your protection" (mechanic: +5% cost to any covert action; guard can be diverted at a price).
- Player Out: Perform a Grand Loyal Act (major resource sink) lowering Suspicion by 15 and locking covert actions for 1 day OR attempt to Eliminate Guard (high-risk covert op: success -10 Suspicion & remove penalty, failure +10 -> 100).
- Loss: Any further +1 Suspicion source while still >= 95 triggers confrontation.

## Cross-System Synergies

- Punishment Escalation: Administrative Punishments add medium-term friction instead of binary loss, extending narrative tension while still jeopardizing win progress by draining the same resources needed for Influence / Trigger Event setup.
- Resource Conversion Loops: Spending Influence to perform Rehabilitation drives Suspicion. Accepting fines preserves Time (helping deadlines) but slows economic buildup for win triggers.
- Time Scarcity: Actions to reduce one track usually consume time that makes other obligations tighter (raising other track risk indirectly).
- Resource Duality: Influence spent to pardon a Strike adds Suspicion (court wonders why king is indulging you). Loyal spectacles reduce Suspicion but create new public expectations (new timed quests -> future Distrust pressure).
- Skill / Asset Paths: Investing in Stealth reduces Suspicion gains but leaves you weaker at Public Administration (increasing chance of missed duties -> Distrust). Investing in Bureaucracy does the reverse.

## Balancing Guidelines

- Target average campaign: 1–2 Punishments (Severity ending at Moderate/Major) plus Suspicion peak of 60–80 before victory.
- Ensure Punishment frequency: Roughly every 12–18 in-game days under careless play; skilled play may avoid second Punishment entirely.
- Provide at least one mid-game safety valve for each track (Pardon, Public Spectacle) but make them mutually taxing.
- Ensure no single optimal loop: Each mitigation should push player toward situations that feed the other track after 2–3 uses.

## UI / Communication Summary

- Distrust: 3-slot meter; when at 2 filled, hover shows: "Next Strike -> Punishment Roll (Current Tier: Moderate)." On trigger, modal with two punishment cards (unless Dire) highlighting projected downstream risks (icons: Time Lock, Resource Drain, Suspicion Amplifier).
- Suspicion: Tier label + contextual flavor; optional action to reveal numeric.
- Event Log: Each addition annotated with (Distrust +1) or (Suspicion +10) for post-mortem clarity.
- Preview Labels: Hovering choices shows projected ranges (e.g., "+6–10 Suspicion" with variance icon).

## Open Questions (Need Win Condition Spec)

- Should repeated Dire-tier Punishments eventually force an alternate failure (e.g., Administrative Removal) if Suspicion stays low? Suggested: 3 Dire Punishments -> forced resignation cutscene (secondary fail path) to keep stakes high.
- Do Punishments pause certain win-trigger timers (e.g., Coup Preparation days) or simply slow input resource flow?

