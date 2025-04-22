
Prompt 2: V4

Objective: First systematically identify all potentially available players for a specified next upcoming NBA game, incorporating detailed and timely injury context and the impact of absences; then use that confirmed player pool and refined injury/absence context to rigorously re-evaluate and finalize the overall game prediction derived from Prompt 1; and finally predict the MIN/MAX statistical range (Points, Rebounds, Assists, Threes) for confirmed available players, specifically adjusting for injury impacts, role changes, advanced metrics, recent form, individual matchups, rest, and the finalized game context, aiming for a realistically achievable MIN floor (~20th-25th percentile outcome) and a plausible MAX ceiling, while acknowledging data limitations and variance.

Prerequisites:

Requires Game Prediction Context: This prompt must be run after completing the "NBA Game Prediction" prompt (Prompt 1). It relies heavily on the initial outputs (Predicted Winner, Spread, O/U, Score) and the conceptual scratchpad data gathered during that process.

System Date: 2025

Core Principles:

Systematic Player Identification & Contextual Analysis: Follow the steps below sequentially.

Conceptual Scratchpad is Crucial: All player, injury, team context, and game context information gathered must be stored conceptually on the scratchpad for iterative use and reference.

Strict Data-First & Recency Focus: Perform necessary dynamic searches for each sub-step before analysis. Prioritize the most recent information, especially for injuries/availability.

Prioritize Reliable & Timely Sources: Use sources such as official team announcements, ESPN, NBA.com, Yahoo! Sports, NBC Sports, Woj/Shams tweets (via reputable aggregators like Hoopshype/Bleacher Report), Underdog NBA, or established beat writers, especially closer to game time. Note source recency/reliability if uncertain.

Reliable Player Stats Sources: Use sources such as Basketball-Reference, NBA.com/stats, Dunks and Threes, Cleaning the Glass, ESPN, Bball-Index, or similar reputable stats sites.

Iterative Loop: Use targeted searches if data is missing or context needs refinement.

Acknowledge Limitations: Be prepared to note if specific data (e.g., certain advanced metrics, definitive injury updates) is unavailable.

Continuation of Steps: When continuing analysis, use the previously generated output, including any revisions, to ensure required data is present and context is maintained.

Player Identification & Prediction Steps:

Phase A: Establish Comprehensive Player Pool & Initial Context

Confirm Full Team Rosters, Transfers & Preliminary Absence Impact:

Search & Store (Scratchpad): Find the most current official/reliable full roster list for both teams (including Two-Way contracts).

Search & Store (Scratchpad): Identify and list significant player transfers/signings/waivers (current season, focus on recent).

(ENHANCED) Search & Store (Scratchpad): If significant players are initially suspected or confirmed OUT or highly questionable (based on preliminary info or Step 4 findings), perform targeted searches for "Team X statistics/performance without [Absent Player Name]" or "Player Y stats when Player Z is out". Store key findings (e.g., impact on team Offensive/Defensive Rating, Pace, specific remaining player usage changes [USG%], efficiency changes [TS%], win/loss record) on scratchpad. Note the sample size if available. This provides crucial preliminary context for Step 6.

(Analysis & Scratchpad Update): Cross-reference lists. Create Initial Master Roster List on scratchpad. Note arrivals/departures and preliminary absence impact context.

Map Rosters to Depth Charts & Verify Availability:

Search: Find the most reliable and recent full depth chart(s) for both teams.

Verify & Analyze (Using Scratchpad & Targeted Search): For each player on the Master Roster List (from Step 1):

Consult retrieved depth chart(s) for typical position/role.

Cross-reference with existing scratchpad info (injuries, status from Prompt 1, G-League/Two-Way).

(ENHANCED) Critical Availability Check: If depth chart placement seems inconsistent with known status, or if availability information is missing, outdated, or uncertain (especially GTD), perform targeted, recent dynamic searches using priority sources (See Core Principles) to confirm the player's current, specific availability (e.g., "Is [Player Name] OUT tonight?", "[Player Name] injury update [Date]", "[Player Name] playing tonight?", "[Player Name] G-League status today?"). Prioritize official team reports or highly reputable sources closest to game time.

(Scratchpad Update): Map verified depth chart position/role. Crucially, update/confirm current availability status based on cross-referencing and latest targeted searches (e.g., 'Starter - Active', 'Bench - Active', 'OUT - Knee Injury [Source/Time]', 'GTD - Ankle [Source/Time]', 'G-League Assignment - Unavailable', 'IR - Season'). Note the source/time of the latest status update if obtained recently.

Integrate Projected Game Roles (Lineups & Bench):

Retrieve Context: Access projected starting lineups and anticipated bench rotation insights from Prompt 1 scratchpad / Step 2 availability check.

Verify/Refine (Mandatory if significant time passed or status changes): Perform quick targeted searches for the very latest projected lineup/rotation news, especially if Step 2 revealed unexpected availability changes or if significant time has passed since Prompt 1. Check reputable sources/beat writers.

(Analysis & Scratchpad Update): Correlate projected starters/key bench with scratchpad players confirmed available in Step 2. Refine the 'Role' information (e.g., 'Projected Starter', 'Key Bench - ~25min', 'Deep Bench - High DNP Risk') for this specific game. Tentatively note potential role/minute shifts based on absences confirmed so far.

Final Injury Filtering & Detailed Diagnosis:

Search & Store (Scratchpad - ENHANCED): Perform targeted dynamic searches for the absolute latest official injury status and reported injury severity, specific diagnosis (e.g., 'Grade 1 Ankle Sprain', 'Mild Knee Soreness', 'Non-COVID Illness', 'Shoulder Strain'), and practice participation status (Full, Limited, None) for every player currently listed on the scratchpad, focusing on GTDs, recent returnees, or anyone with lingering issues. Use priority sources and note recency/official status. Differentiate clearly between vague reports ('soreness') and specific diagnoses ('sprain', 'strain'). If a specific diagnosis/severity isn't found after searching reliable sources, note 'Undisclosed' or 'Not Specified'.

(Analysis & Scratchpad Update): Update the 'Status' for each player (Active, OUT, GTD - Expects to Play, GTD - Questionable, GTD - Doubtful, G-League/Two-Way - Unavailable) and add/refine an 'Injury Detail' field, noting the specific diagnosis, severity, practice status, and source/time of report.

Define Final Player Pool for Prediction:

(Analysis): Review scratchpad. Final Player Pool = Players marked Active, GTD - Expects to Play, or potentially GTD - Questionable if latest info/practice status suggests a likely role (even if limited). Exclude OUT, GTD - Doubtful, Unavailable confirmed in Step 2/4.

(Scratchpad Check): Confirm this final list is clearly defined, along with associated detailed injury information for relevant players.

Phase B: Finalize Game Context & Predict Player Stats

Re-evaluate & Finalize Game Prediction Context (CRITICAL ENHANCEMENT):

Retrieve Context: Access initial game prediction (Winner, Spread, Total, Score) and supporting analysis from Prompt 1 scratchpad. Retrieve preliminary absence impact data (Step 1) and confirmed player pool/injury details (Phase A).

(ENHANCED) Compare & Analyze Rigorously: Explicitly compare the confirmed Final Player Pool, key absences, and specific injury situations (diagnosis/severity/practice status from Step 4) against Prompt 1 assumptions. Assess if discrepancies fundamentally alter:

Game Flow & Pace: Impact of missing playmakers, transition players, or key defenders.

Team Offensive/Defensive Efficiency: Reference Step 1 data on team performance w/o player(s). How significantly is efficiency likely affected in this specific matchup?

Key Matchups: Who guards whom now? Does a star face tougher defense/schemes? Does a role player gain opportunity?

Likely Tactical Adjustments: Disproportionate load on stars? Changed offensive focus? Crucially, for playoff games, assume rotations tighten significantly (often 7-8 players), unless injuries force otherwise. Factor this reduced depth reliance. How might opponent adjust defensively?

Blowout Potential: Has the likelihood of a non-competitive game increased significantly based on confirmed absences/matchups? How does this impact projected minutes (especially late-game)?

Update or Maintain Prediction: Based on the rigorous impact analysis above, make a definitive judgment:

Maintain: If confirmed context aligns closely with Prompt 1 assumptions and analysis confirms minimal shift. State this explicitly.

Update: If confirmed context significantly shifts expected game script. Update the game prediction (Winner, Spread Outcome, Total Outcome, Projected Score). Clearly state reasons, linking directly to confirmed absences/injuries, Step 1 impact data, and specific analysis points above (e.g., "Updating Total prediction to Under 218.5: Lillard confirmed OUT significantly impacts Bucks OffRtg [ref Step 1 data], Pacers likely to slow pace focusing defense on Giannis, tightening playoff rotations limit bench scoring.").

(Scratchpad Update): Store the Finalized Game Prediction (Winner, Spread Outcome, Total Outcome, Projected Score) and key reasoning/contextual shifts on the scratchpad. This finalized context is the mandatory basis for individual player predictions.

Retrieve Detailed Player Game Logs & Advanced Metrics (for Final Player Pool):

Search & Store/Process (ENHANCED Flexibility): For each player in the Final Player Pool:

Perform targeted searches for game logs (last 5-10 official games).

Extract/process key stats (Minutes, Pts, Reb, Ast, 3PM, FG%, etc.) and relevant available advanced metrics (e.g., Usage Rate [USG%], True Shooting Percentage [TS%], Player Efficiency Rating [PER], available Defensive Rating/metrics, potentially RAPTOR/EPM/LEBRON if readily accessible from reliable sources like Bball-Index, DunksAndThrees, etc.) for the same period. Link to player on scratchpad. If specific advanced metrics are unavailable from reliable sources via search, rely on available alternatives and note this limitation.

(Analysis): Confirm logs/stats/metrics gathered for all relevant players.

Analyze Data & Predict MIN/MAX Stats (Using Finalized Game Context & Enhanced Logic):

(Analysis - ENHANCED): For each player in the Final Player Pool, using logs/metrics (Step 7 - weight recent 3-5 games), established role (Step 3), final status & detailed injury diagnosis/severity (Step 4), and crucially, the Finalized Game Prediction context (Step 6):

Baseline Performance & Role Adjustment: Compare recent vs. broader trends using available advanced metrics (USG%, TS%, PER, etc.) to understand efficiency, role, impact. Evaluate consistency/variance (identify high-variance players based on stat fluctuations/metric volatility). Assess matchup impact using updated Step 6 analysis (consider team schemes and specific defender effectiveness if data available). Analyze anticipated role/usage change due to absences (Step 1/6 data) – consider impact on efficiency (increased usage often lowers TS%). For playoff games, be highly skeptical of projecting significant minutes/stats outside core 7-8 players; explicitly note high DNP-CD risk.

Rest Impact Assessment: Briefly note rest schedule (days off) and potential impact (slight MIN/MAX adjustment if significant disparity).

Injury Impact Adjustment (Apply if GTD/Returning/Playing Through Injury - ENHANCED Guidance):

Retrieve specific 'Injury Detail' (diagnosis, severity, practice status) from Step 4.

Assess Injury-Skill Correlation: How does the specific injury likely impact primary vs. secondary skills?

Severity Weighting & Adjustment Examples:

Minor (e.g., 'Soreness', 'Questionable' but practiced fully): Minimal impact, perhaps slightly wider range or tempered MAX. Note low weight given.

Moderate (e.g., 'Grade 1 Sprain', 'Strain', Limited Practice): Tangible MIN reduction for affected stats (e.g., ankle -> points/reb), potentially lower MAX, wider range. Note expected skill compensation (e.g., more spot-up shooting).

Significant (e.g., 'Grade 2+ Sprain/Strain', 'Fracture', 'Illness' causing missed practice): Significant MIN/MAX reduction across board, especially affected stats. Consider potential minutes cap.

If 'Undisclosed' or 'Not Specified': Note uncertainty, slightly widen range, apply moderate adjustment if practice was limited/missed.

Set Final MIN/MAX (Applying Enhanced Philosophy): Define floor (MIN) and ceiling (MAX) incorporating all factors.

MIN Setting Philosophy (REVISED & REAFFIRMED): Aim for a robust, realistically achievable floor (~70-75% confidence / ~20th-25th percentile outcome within projected script/role). MUST account for: potential injury limitations (per severity), risk of reduced minutes (blowout risk from Step 6, foul trouble, playoff rotation tightening/DNP-CD risk), historical low-end performance, difficult matchup (team/individual), negative teammate impact, potential poor efficiency (recent TS%/PER). Represents a plausible floor considering risks, not just below-average. Value player should likely meet/exceed if playing anticipated role/minutes.

MAX Setting Philosophy: Realistic upside within finalized game context. Tempered by injury, blowout risk, tough matchup/defense, efficiency limits. For players gaining usage, MAX can rise but capped by realistic potential & efficiency drop risk. For players facing tougher defense/less support due to absences, MAX lowered significantly.

Range Width (ENHANCED): Reflects player variance (consistency/metric volatility - explicitly note if high-variance), injury uncertainty, role uncertainty. Wider ranges for higher variance/uncertainty.

(Scratchpad Update): Store MIN/MAX and core justifications, ensuring they reflect enhanced analysis points (metrics, injury severity specifics, DNP risk, etc.).

Output: Present predictions in two separate tables, one for each team, including only players from the Final Player Pool (Step 5).

Table Structure:

Player Name	Team	Role (Game Specific)	Status (Final)	Injury Detail (Diagnosis/Severity/Practice Status if Relevant)	MIN-MAX Points	MIN-MAX Rebounds	MIN-MAX Assists	MIN-MAX Threes	Analysis Justification (Must reference: finalized game context [incl. blowout risk], role/usage change [ref Step 1/6], playoff rotation/DNP risk, recent form/metrics [specify e.g., TS%, USG%], variance level, matchup, rest, injury specifics [diagnosis/severity/impact per Step 8 guide], MIN/MAX philosophy application. Note data limitations e.g., "Specific defender stats N/A")
[Player A]	[Tm]	Projected Starter	Active	N/A	18+ to 29	5+ to 9	3+ to 6	1+ to 4	Healthy, normal role. Finalized context (close game) supports normal mins. Strong recent form (TS% >60% last 3). Faces average team defense. MIN set at realistic floor (~25th percentile) considering usage/history; MAX reflects recent peak efficiency. Low variance player.
[Player B]	[Tm]	Projected Starter	GTD (Expects to Play)	Grade 1 Ankle Sprain (Limited Practice)	10+ to 18	2+ to 5	1+ to 3	1+ to 3	Injury Impact (Moderate): Gr1 Ankle likely limits drives/burst. Expect focus on spot-up shooting. MIN Pts/Reb lowered due to limitation/severity & potential slight mins cap (~70% conf. floor); MAX Pts/Threes allows efficient shooting but capped; MAX Reb/Ast lowered more. Moderate variance. Finalized context (Under) supports potentially lower output.
[Player C]	[Tm]	Key Bench (~20min)	Active	Shoulder Soreness (Returned last game, Full Practice)	7+ to 15	3+ to 6	0+ to 2	1+ to 2	Injury Impact (Minor): Soreness noted, but Full Practice = less weight. Good rest (3 days). MIN/MAX range reflects bench role variance. Finalized context (Blowout risk LOW) supports likely rotation mins.
[Player D]	[Tm]	Projected Starter	Active	N/A (Teammate Star OUT)	14+ to 25	4+ to 8	2+ to 5	1+ to 3	Role Change: Expected increased USG% (~+5% based on Step 1 data) due to [Star]'s absence, but faces primary D focus (tougher matchup vs [Defender Name/Team Scheme] noted in Step 6). MIN reflects floor w/ increased role & pressure; MAX raised by usage but capped by defensive attention & historical efficiency dips w/ high USG%. Moderate-High variance.
[Player E]	[Tm]	Deep Bench (9th/10th man)	Active	N/A	0+ to 6	0+ to 3	0+ to 1	0+ to 1	Playoff Rotation Risk (HIGH): Significant DNP-CD risk as likely outside core 7-8 rotation (Ref Step 6/8 playoff logic). MINs set very low reflecting potential no/minimal mins. MAX assumes brief garbage time or multiple foul trouble scenario. Low confidence in any stats.
...	...	...	...	...	...	...	...	...	(Repeat only for players confirmed available and likely to play, ensuring justification covers enhanced analysis points including playoff DNP risk, specific metrics used/unavailable, and explicit injury impact rationale where relevant)
