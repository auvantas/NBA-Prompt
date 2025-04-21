**Prompt V3.1**

Prompt 2

Objective: First systematically identify all potentially available players for a specified next upcoming NBA game, incorporating detailed injury context and the impact of absences; then use that confirmed player pool and refined injury/absence context to re-evaluate and finalize the overall game prediction derived from Prompt 1; and finally predict the MIN/MAX statistical range (Points, Rebounds, Assists, Threes) for confirmed available players, specifically adjusting for injury impacts, role changes, advanced metrics, recent form, individual matchups, rest, and the finalized game context, aiming for a realistically achievable MIN floor and a plausible MAX ceiling.

Prerequisites:

Requires Game Prediction Context: This prompt must be run after completing the "NBA Game Prediction" prompt (Prompt 1). It relies heavily on the initial outputs (Predicted Winner, Spread, O/U, Score) and the conceptual scratchpad data gathered during that process.

Core Principles:

Systematic Player Identification & Contextual Analysis: Follow the steps below sequentially.

Conceptual Scratchpad is Crucial: All player, injury, team context, and game context information gathered must be stored conceptually on the scratchpad.

Strict Data-First: Perform necessary dynamic searches for each sub-step before proceeding with analysis or the next step and if required, use data from the scratchpad as input for prompt chaining dynamic searches.

Use Reliable News Sources: Use sources such as ESPN/NBA/Yahoo! Sports/NBC Sports/NewsNow/Hoopshype/Basketball Insiders/Hoops Rumors.

Use Reliable Player Stats Sources: Use sources such as ESPN/Basketball-Reference/Dunks and Threes/FiveThirtyEight’s RAPTOR/NBA Savant/Bball-Index/3StepsBasket/NBAstuffer/nba.com/lineups.com/fixturedownload.com.

Iterative Loop: Use targeted searches if data is missing or context needs refinement.

System Date: 2025

Player Identification & Prediction Steps:

Phase A: Establish Comprehensive Player Pool & Initial Context

Confirm Full Team Rosters, Transfers & Absence Impact:

Search & Store (Scratchpad): Find the most current official/reliable full roster list for both teams.

Search & Store (Scratchpad): Identify and list significant player transfers/signings/waivers (current season, focus on recent).

(NEW) Search & Store (Scratchpad): If significant players are initially suspected or confirmed OUT or highly questionable for either team (based on preliminary info or Step 4 findings), perform targeted searches for "Team X statistics/performance without [Absent Player Name]" or "Player Y stats when Player Z is out". Store key findings (e.g., impact on team Offensive/Defensive Rating, Pace, specific remaining player usage changes, win/loss record) on scratchpad. This is crucial preliminary context.

(Analysis & Scratchpad Update: Cross-reference lists. Create Initial Master Roster List on scratchpad. Note arrivals/departures and preliminary absence impact context.)

Map Rosters to Depth Charts & Verify Availability:

Search: Find the most reliable and recent full depth chart(s) for both teams.

Verify & Analyze (Using Scratchpad & Targeted Search): For each player on the Master Roster List (from Step 1):

Consult the retrieved depth chart(s) for their typical position/role.

Cross-reference with existing information on the scratchpad (e.g., previously noted injuries, status from Prompt 1 if applicable, G-League assignments).

If the depth chart placement seems inconsistent with known status (e.g., an injured player listed high on the depth chart), or if availability/status information is missing or potentially outdated on the scratchpad for that player, perform targeted dynamic searches using the tool to confirm the player's current, specific availability (e.g., "Is [Player Name] OUT tonight?", "[Player Name] injury update", "[Player Name] G-League status today?").

(Scratchpad Update: Map the player's verified depth chart position/role onto the scratchpad. Crucially, update/confirm their current availability status based on the cross-referencing and targeted searches (e.g., 'Starter - Active', 'Bench - Active', 'OUT - Knee Injury', 'G-League Assignment - Unavailable', 'IR - Season'). This step ensures the depth chart mapping accurately reflects who is actually expected to be available or unavailable before moving to detailed injury filtering.)

Integrate Projected Game Roles (Lineups & Bench):

Retrieve Context: Access projected starting lineups and anticipated bench rotation insights stored on the scratchpad during Prompt 1 and refined in Step 2's availability check.

Verify/Refine (Optional): Perform quick targeted searches for the very latest projected lineup/rotation news, especially if Step 2 revealed unexpected availability changes.

(Analysis & Scratchpad Update: Correlate projected starters/key bench with scratchpad players confirmed as available in Step 2. Refine the 'Role' information on the scratchpad for this specific game. Tentatively note potential role/minute shifts based on absences confirmed so far.)

Final Injury Filtering & Detailed Diagnosis:

Search & Store (Scratchpad): Perform targeted dynamic searches for the absolute latest official injury status and reported injury severity, specific diagnosis (e.g., 'Grade 1 Ankle Sprain', 'Mild Knee Soreness', 'Non-COVID Illness', 'Shoulder Strain') and practice participation status (if available) for every player currently listed on the scratchpad (from Master Roster), paying close attention to those identified as potentially playing but possibly hampered (GTD, recent returnees). Differentiate clearly between vague reports ('soreness') and specific diagnoses ('sprain', 'strain').

(Analysis & Scratchpad Update: Update the 'Status' for each player (Active, Out, GTD variations, G-League/Two-Way - Unavailable) and add/refine an 'Injury Detail' field on the scratchpad, noting the specific diagnosis, severity, and practice status, especially for GTD or recently returned players.)

Define Final Player Pool for Prediction:

(Analysis: Review scratchpad. Final Player Pool = Players marked Active, GTD - Likely In, or potentially GTD - Questionable if likely to play some role based on latest info, practice status, and injury severity. Exclude Out, GTD - Likely Out, Unavailable confirmed in Step 2/4.)

(Scratchpad Check: Confirm this final list is clearly defined, along with associated detailed injury information for relevant players.)

Phase B: Finalize Game Context & Predict Player Stats

Re-evaluate & Finalize Game Prediction Context (CRITICAL ENHANCEMENT):

Retrieve Context: Access the initial game prediction (Predicted Winner, Spread Outcome, Total Outcome, Projected Score) and supporting analysis from the Prompt 1 scratchpad. Also retrieve the preliminary absence impact data gathered in Step 1.

Compare & Analyze Rigorously: Explicitly compare the confirmed Final Player Pool, key absences, and specific injury situations (diagnosis/severity from Step 4) against the player availability assumptions made during Prompt 1. Assess if discrepancies fundamentally alter:

Expected Game Flow & Pace: (Does the absence of a key playmaker slow the game down? Does the absence of a primary transition player affect pace? Does a key defensive absence open up fast breaks?)

Team Offensive/Defensive Efficiency: (Reference data gathered in Step 1 about team performance without the absent player(s). How significantly is the team's overall scoring or stopping power likely affected in this specific matchup?)

Key Matchups: (Who guards whom now? Does a remaining star face a significantly tougher primary defender or defensive schemes designed to stop them? Does a role player have an easier matchup or opportunity?)

Likely Tactical Adjustments: (Will the team rely disproportionately on remaining stars? Will they change offensive focus - e.g., more post-ups, more perimeter shots, different pick-and-roll partners? Will bench rotations/minutes change significantly? How will the opposing team likely adjust defensively? For playoff games, assume rotations will likely tighten significantly (often to 7-8 players). Factor this reduced depth reliance into tactical and minute projections unless specific injury situations clearly force wider rotations.)

Potential for Blowout: (Based on the confirmed absences and updated matchup analysis, does the likelihood of a non-competitive game increase significantly? How does this impact projected minutes, especially for starters late in the game?)

Update or Maintain Prediction: Based on the rigorous impact analysis above, make a definitive judgment:

If confirmed player availability/injury context aligns closely with Prompt 1 assumptions and the detailed analysis confirms minimal shift in expected dynamics, maintain the original game prediction.

If confirmed availability/injury situations significantly shift the expected game script (efficiency, pace, tactical approach, competitiveness), update the game prediction (Winner, Spread Outcome, Total Outcome, Projected Score). Clearly state the reasons for the update, linking directly to the confirmed absences/injuries and the specific points from the analysis above (e.g., "Updating Bucks score lower due to Lillard's confirmed absence impacting team OffRtg by X points per 100 possessions historically, and Pacers likely focusing defense on Giannis/Kuzma").

(Scratchpad Update: Store the Finalized Game Prediction (Winner, Spread Outcome, Total Outcome, Projected Score) and the key reasoning/contextual shifts identified in the analysis on the scratchpad. This finalized context is now the mandatory basis for individual player predictions.)

Retrieve Detailed Player Game Logs & Advanced Metrics (for Final Player Pool):

Search & Store/Process: For each player in the Final Player Pool (identified in Step 5):

Perform targeted searches for game logs (last 5-10 official games).

Extract/process key stats (Minutes, Pts, Reb, Ast, 3PM, FG%, etc.) and relevant advanced metrics (e.g., Usage Rate, True Shooting Percentage [TS%], Player Efficiency Rating [PER], Defensive Rating if available, RAPTOR if readily accessible from reliable sources) for the same period, linking to the player on the scratchpad.

(Analysis: Confirm logs/stats/metrics gathered for all relevant players.)

Analyze Data & Predict MIN/MAX Stats (Using Finalized Game Context & Enhanced Logic):

(Analysis: For each player in the Final Player Pool, using their logs and metrics (Step 7), giving heavier analytical weight to the most recent 3-5 games to capture current form, established game role (Step 3), final status & detailed injury diagnosis/severity (Step 4), and crucially, the Finalized Game Prediction context from Step 6 (including score, spread/total outcome implications, pace, updated matchup details, anticipated team tactical adjustments, and blowout risk):

Baseline Performance & Role Adjustment: Compare recent vs. broader performance trends, leveraging advanced metrics (Usage, TS%, PER, Def Rtg, potentially RAPTOR) to establish a baseline understanding of efficiency, role, and overall impact. Evaluate consistency/variance (note if player is high-variance based on historical stat fluctuations or metrics like PER/TS% volatility). Assess matchup impact using the updated team/strategic matchups identified in Step 6 and, where possible, considering the likely primary individual defender's effectiveness or defensive scheme tendencies. Consider efficiency variance (e.g., TS%). Crucially, analyze the anticipated change in role/usage for the player based on confirmed absences/injuries of teammates (using Step 1/Step 6 analysis). Will they handle the ball more/less? Take more/fewer shots? Become a primary/secondary option? Face more defensive attention? For playoff games, be highly skeptical of projecting significant minutes or stats for players typically outside the core 7-8 man rotation, even if available. Explicitly consider the high risk of DNP-CD (Did Not Play - Coach's Decision) for these players unless injuries force their usage.

Rest Impact Assessment: Consider the player's recent rest schedule (days since last game) and note any significant rest disparity compared to opponents, potentially adjusting MIN/MAX slightly if a notable fatigue/freshness factor is anticipated.

Injury Impact Adjustment (Apply if GTD/Returning/Playing Through Injury):

Retrieve the specific 'Injury Detail' (diagnosis, severity, practice status) from the scratchpad (Step 4).

Identify the player's primary skill/role.

Assess Injury-Skill Correlation: Analyze how the specific injury diagnosis and reported severity likely impacts primary vs. secondary skills. (e.g., Grade 1 Ankle Sprain vs. general 'soreness').

Apply Skill Focus Prediction: Assume the player/team tries to leverage less-impacted skills.

Severity Weighting: Give less weight to vague reports ('soreness', 'questionable' but practiced fully) compared to specific diagnoses ('Grade 2 sprain', 'Strain', 'Fracture', 'Illness' causing missed practices). For minor issues, impact on MIN/MAX might be minimal, perhaps slightly widening the range or tempering the MAX. For significant injuries, impact should be clear, especially on the MIN and potentially MAX of affected stats.

Adjust MIN/MAX for primary skill: Lower the range compared to a healthy baseline based on severity, potentially widening it slightly for variance.

Adjust MIN/MAX for secondary skills: Lower these ranges more significantly if directly impacted by the specific injury type/severity.

Set Final MIN/MAX (Applying Enhanced Philosophy): Define the floor (MIN) and ceiling (MAX) potential incorporating all factors above (baseline performance/metrics, recency, role change, individual matchup, rest, injury impact, game context).

MIN Setting Philosophy (REVISED): Prioritize making the MIN a robust and realistically achievable floor (aiming for ~70-75% confidence or a ~20th-25th percentile outcome within the projected game script and player role). It must account for: potential injury limitations (based on severity/diagnosis), risk of reduced minutes (blowout risk, foul trouble, playoff rotation tightening/DNP-CD risk), historical low-end performance in similar contexts, difficult matchup identified (team or individual defender), potential negative impact of teammate absence (e.g., less playmaking support), potential for poor efficiency (informed by recent TS%/PER). The MIN should represent a plausible floor scenario considering the identified risks, not just a slightly below-average performance. Aim for a value the player is reasonably likely to meet or exceed even accounting for downside factors if they play their anticipated role/minutes.

MAX Setting Philosophy: The MAX reflects realistic upside within the finalized game context. It should be tempered by: injury limitations, potential for blowout limiting minutes, tough matchup/increased defensive focus (including specific defender), historical ceilings, potential efficiency limitations. For players benefiting from absences (increased role), MAX can be pushed higher but grounded in realistic potential & efficiency (Usage increase doesn't always mean linear stat increase if efficiency drops), not just summing vacated stats. Consider positive rest impact or favourable individual matchup for potential MAX boost. For players potentially negatively impacted by absences (e.g., facing primary defense, less support), the MAX should be lowered significantly compared to their healthy baseline.

Range Width: The gap between MIN and MAX should reflect player variance (informed by statistical consistency/metric volatility like TS%/PER fluctuations), injury uncertainty, and role uncertainty. High-variance players, those with uncertain injury impacts, or those with significantly changed roles may have wider ranges.

(Optional) Player Correlation Note: Briefly note if a player's performance might be significantly correlated with a specific teammate's status or performance (e.g., higher assist potential if primary scorer is out).

(Scratchpad Update: Store the MIN/MAX predictions and the core justification elements for each player, ensuring justifications reflect the enhanced analysis points.)

Output: Present predictions in two separate tables, one for each team, including only players from the Final Player Pool (Step 5). Use the following structure for each table:

Player Name	Team	Role (Game Specific)	Status (Final)	Injury Detail (Diagnosis/Severity/Status if Relevant)	MIN-MAX Points	MIN-MAX Rebounds	MIN-MAX Assists	MIN-MAX Threes	Analysis Justification (Must reference finalized game context [incl. impact of absences/blowout risk], anticipated role/usage change, playoff rotation/DNP risk assessment if applicable, recent form/metrics (TS%, Usage), variance, specific matchup notes, status, rest, and explicitly mention injury diagnosis/severity/impact on skill focus/range setting philosophy if applicable)
[Player A]	[Tm]	Starter	Active	N/A	18+ to 29	5+ to 9	3+ to 6	1+ to 4	Healthy, normal role. Strong recent form (high TS% last 3 games). Finalized game context (close game) supports normal mins. Faces average defender. MIN set at realistic floor (~20th percentile outcome) based on recent lows & usage; MAX reflects upside but slightly tempered vs. peaks due to playoff intensity.
[Player B]	[Tm]	Starter	GTD (Likely In)	Grade 1 Ankle Sprain (Practiced Limited)	10+ to 18	2+ to 5	1+ to 3	1+ to 3	Injury Impact: Gr1 Ankle Sprain likely limits drives/agility. Expect focus on spot-up shooting, lower usage. MIN Pts/Reb/Ast lowered due to limitation/severity & potential mins cap (~70% conf. floor); MAX Pts/Threes allows for efficient shooting but capped by injury/mobility; MAX Reb/Ast lowered more sig. Lower expected TS%.
[Player C]	[Tm]	Key Bench	Active	Shoulder Soreness (Returned last game, Full Practice)	7+ to 15	3+ to 6	0+ to 2	1+ to 2	Injury Impact: Minor soreness, practiced fully, less weight given. Good rest (3 days off). MIN/MAX slightly wider range for Pts/Threes due to bench role variance, but MIN kept realistic. MAX reasonable based on role/logs/metrics.
[Player D]	[Tm]	Starter	Active	N/A (Teammate Star Out)	14+ to 25	4+ to 8	2+ to 5	1+ to 3	Role Change: Expected increased usage/shots due to [Star Player]'s absence (Ref Step 1/6 data), but will face primary defensive focus (tougher matchup vs [Defender Name] noted in Step 6). MIN reflects floor even with increased role & pressure; MAX raised due to usage but capped by expected defensive pressure & historical efficiency dips.
[Player E]	[Tm]	Deep Bench	Active	N/A	0+ to 6	0+ to 3	0+ to 1	0+ to 1	Playoff Rotation Risk: High DNP-CD risk as likely 9th/10th man (Ref Step 6/8 playoff logic). MINs set very low (0-2 range) reflecting potential for minimal or no minutes. MAX assumes brief garbage time or injury-forced appearance.
...	...	...	...	...	...	...	...	...	(Repeat only for players confirmed available and likely to play, ensuring justification covers enhanced analysis points including playoff DNP risk where relevant)
