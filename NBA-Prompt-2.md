**Prompt V3**

Prompt 2

Objective: First systematically identify all potentially available players for a specified next upcoming NBA game, incorporating injury details; then use that confirmed player pool and injury context to re-evaluate and finalize the overall game prediction derived from Prompt 1; and finally predict the MIN/MAX statistical range (Points, Rebounds, Assists, Threes) for confirmed available players, specifically adjusting for injury impacts on skill focus based on the finalized game context.

Prerequisites:

Requires Game Prediction Context: This prompt must be run after completing the "NBA Game Prediction" prompt (Prompt 1). It relies heavily on the initial outputs (Predicted Winner, Spread, O/U, Score) and the conceptual scratchpad data gathered during that process.

Core Principles:

Systematic Player Identification: Follow the steps below sequentially.

Conceptual Scratchpad is Crucial: All player, injury, and game context information gathered must be stored conceptually on the scratchpad.

Strict Data-First: Perform necessary dynamic searches for each sub-step before proceeding with analysis or the next step and if required, use data from the scratchpad as input for prompt chaining dynamic searches.

Use Reliable News Sources: Use sources such as ESPN/NBA/Yahoo! Sports/NBC Sports/NewsNow/Hoopshype/Basketball Insiders/Hoops Rumors.

Use Reliable Player Stats Sources: Use sources such as ESPN/Basketball-Reference/Dunks and Threes/FiveThirtyEight’s RAPTOR/NBA Savant/Bball-Index/3StepsBasket/NBAstuffer/nba.com/lineups.com/fixturedownload.com.

Iterative Loop: Use targeted searches if data is missing.

System Date: 2025

Player Identification & Prediction Steps:

Phase A: Establish Comprehensive Player Pool

Confirm Full Team Rosters & Recent Transfers:

Search & Store (Scratchpad): Find the most current official/reliable full roster list for both teams.

Search & Store (Scratchpad): Identify and list significant player transfers/signings/waivers (current season, focus on recent).

(Analysis & Scratchpad Update: Cross-reference lists. Create Initial Master Roster List on scratchpad. Note arrivals/departures.)

Map Rosters to Depth Charts & Verify Availability: (Updated Step)

Search: Find the most reliable and recent full depth chart(s) for both teams.

Verify & Analyze (Using Scratchpad & Targeted Search): For each player on the Master Roster List (from Step 1):

Consult the retrieved depth chart(s) for their typical position/role.

Cross-reference with existing information on the scratchpad (e.g., previously noted injuries, status from Prompt 1 if applicable, G-League assignments).

If the depth chart placement seems inconsistent with known status (e.g., an injured player listed high on the depth chart), or if availability/status information is missing or potentially outdated on the scratchpad for that player, perform targeted dynamic searches using the tool to confirm the player's current, specific availability (e.g., "Is [Player Name] OUT tonight?", "[Player Name] injury update", "[Player Name] G-League status today?").

(Scratchpad Update: Map the player's verified depth chart position/role onto the scratchpad. Crucially, update/confirm their current availability status based on the cross-referencing and targeted searches (e.g., 'Starter - Active', 'Bench - Active', 'OUT - Knee Injury', 'G-League Assignment - Unavailable', 'IR - Season'). This step ensures the depth chart mapping accurately reflects who is actually expected to be available or unavailable before moving to detailed injury filtering.)

Integrate Projected Game Roles (Lineups & Bench):

Retrieve Context: Access projected starting lineups and anticipated bench rotation insights stored on the scratchpad during Prompt 1 and refined in Step 2's availability check.

Verify/Refine (Optional): Perform quick targeted searches for the very latest projected lineup/rotation news, especially if Step 2 revealed unexpected availability changes.

(Analysis & Scratchpad Update: Correlate projected starters/key bench with scratchpad players confirmed as available in Step 2. Refine the 'Role' information on the scratchpad for this specific game. Consider how potential injury limitations (identified in Step 4) might affect a player's projected minutes or specific role even if listed as starter/key bench.)

Final Injury Filtering & Diagnosis:

Search & Store (Scratchpad): Perform targeted dynamic searches for the absolute latest official injury status and reported injury details/diagnosis (e.g., 'Ankle Sprain', 'Knee Soreness', 'Illness', 'Shoulder Strain') for every player currently listed on the scratchpad (from Master Roster), paying close attention to those identified as potentially playing but possibly hampered.

(Analysis & Scratchpad Update: Update the 'Status' for each player (Active, Out, GTD variations, G-League/Two-Way - Unavailable) and add an 'Injury Detail' field on the scratchpad, noting the specific diagnosis if available, especially for GTD or recently returned players.)

Define Final Player Pool for Prediction:

(Analysis: Review scratchpad. Final Player Pool = Players marked Active, GTD - Likely In, or potentially GTD - Questionable if likely to play some role based on latest info. Exclude Out, GTD - Likely Out, Unavailable confirmed in Step 2/4.)

(Scratchpad Check: Confirm this final list is clearly defined, along with associated injury details for relevant players.)

Phase B: Finalize Game Context & Predict Player Stats

Re-evaluate & Finalize Game Prediction Context:

Retrieve Context: Access the initial game prediction (Predicted Winner, Spread Outcome, Total Outcome, Projected Score) and supporting analysis from the Prompt 1 scratchpad.

Compare & Analyze: Explicitly compare the confirmed Final Player Pool, key absences, and specific injury situations (identified in Steps 4 & 5) against the player availability assumptions made during the initial Prompt 1 analysis. Assess if any significant discrepancies (e.g., a key scorer playing through an ankle injury, a primary defender being out confirmed in Step 2/4) fundamentally alter the expected game dynamics, key matchups, team strengths/weaknesses, potential tactical adjustments (like focusing offense through an uninjured player), or projected pace compared to the initial assessment.

Update or Maintain Prediction: Based on the impact analysis, make a definitive judgment:

If confirmed player availability and injury context align closely with Prompt 1 assumptions and don't significantly change the outlook, maintain the original game prediction.

If confirmed availability/injury situations significantly shift the expected game script, update the game prediction (Winner, Spread Outcome, Total Outcome, Projected Score).

(Scratchpad Update: Store the Finalized Game Prediction (Winner, Spread Outcome, Total Outcome, Projected Score) on the scratchpad. This finalized context, including considerations for how injuries might affect team tactics, is now the basis for individual player predictions.)

Retrieve Detailed Player Game Logs (for Final Player Pool):

Search & Store/Process: For each player in the Final Player Pool (identified in Step 5):

Perform targeted searches for game logs (last 5-10 official games).

Extract/process key stats (Minutes, Pts, Reb, Ast, 3PM, FG%, etc.), linking to the player on the scratchpad.

(Analysis: Confirm logs/stats gathered for all relevant players.)

Analyze Logs & Predict MIN/MAX Stats (Using Finalized Game Context & Injury Diagnosis):

(Analysis: For each player in the Final Player Pool, using their logs (Step 7), established game role (Step 3), final status & injury diagnosis (Step 4), and crucially, the Finalized Game Prediction context from Step 6 (including score, spread/total outcome implications, pace, matchup details, team tactical adjustments based on confirmed absences/injuries):

Standard Evaluation: Compare recent vs. broader performance trends. Evaluate consistency/variance within role and likely minutes (informed by finalized game script - e.g., blowout risk adjusted based on Step 6). Assess matchup impact using confirmed player availability. Consider efficiency variance.

Injury Impact Adjustment (Apply if GTD/Returning from Injury):

Retrieve the specific 'Injury Detail' from the scratchpad.

Identify the player's primary skill/role (e.g., scoring, playmaking, rebounding, defense).

Assess Injury-Skill Correlation: Analyze how the specific injury type likely impacts their primary vs. secondary skills.

Example: Ankle/foot injury might hinder driving/finishing and defensive agility (affecting Pts from drives, Ast from penetration, potentially Reb, Def stats), but less so spot-up shooting (Threes, some Pts). Player might rely more on jump shots.

Example: Hand/wrist/shoulder injury likely impacts shooting efficiency (Pts, Threes, FG%), passing accuracy/velocity (Ast), and potentially rebounding grip (Reb).

Example: Illness often leads to reduced stamina, potentially impacting all stats via lower minutes and effectiveness.

Apply Skill Focus Prediction: Assume the player/team will strategically try to leverage the player's primary skill where possible, even if overall effectiveness is reduced, while contributions in areas directly hampered by the injury will likely decrease more significantly.

Adjust MIN/MAX for the primary skill: Lower the range compared to a healthy baseline, but potentially less drastically than secondary skills. The range should reflect the attempt to focus here, acknowledging increased variance and potentially lower efficiency.

Adjust MIN/MAX for secondary skills: Lower these ranges more significantly, reflecting the physical limitation or tactical de-emphasis. The MIN should represent a scenario where the injury clearly restricts this aspect of their game.

Set Final MIN/MAX: Define the floor (MIN) and ceiling (MAX) potential within the finalized game context, incorporating standard evaluation factors and the specific injury impact adjustments where applicable. The MIN reflects potential limitations (injury, reduced minutes, poor efficiency), while the MAX reflects playing through it effectively, albeit likely skewed towards their primary skill if injured.

Output: Present predictions in two separate tables, one for each team, including only players from the Final Player Pool (Step 5). Use the following structure for each table:
| Player Name | Team | Role (Game Specific) | Status (Final) | Injury Detail (If Relevant) | MIN-MAX Points | MIN-MAX Rebounds | MIN-MAX Assists | MIN-MAX Threes | Analysis Justification (Must reference finalized game context, role, logs, status, and explicitly mention injury diagnosis/impact on skill focus if applicable) |
| :---------- | :--- | :------------------- | :------------- | :-------------------------- | :------------- | :--------------- | :-------------- | :------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Player A] | [Tm] | Starter | Active | N/A | 18+ to 30 | 5+ to 10 | 3+ to 7 | 2+ to 5 | Healthy. Based on logs, matchup advantage, role as primary scorer, and finalized game context predicting a close, high-scoring game. |
| [Player B] | [Tm] | Starter | GTD (Likely In) | Ankle Sprain | 12+ to 22 | 2+ to 5 | 1+ to 4 | 2+ to 4 | Injury Impact: Ankle sprain likely limits drives/playmaking. Expect focus on perimeter shooting (primary skill). Reduced MIN/MAX for Reb/Ast due to limited mobility/penetration. Finalized game context suggests opponent may target his defense. MIN reflects limited effectiveness; MAX reflects efficient shooting night despite limitations. |
| [Player C] | [Tm] | Key Bench | Active | Shoulder Soreness (Recent Return) | 6+ to 13 | 3+ to 6 | 0+ to 2 | 0+ to 1 | Injury Impact: Shoulder likely affects shooting consistency (primary offensive skill). MIN/MAX Pts/Threes lowered significantly. Reb/Ast less affected but capped by bench role/minutes. Justified by recent return logs showing lower shooting volume/efficiency and finalized game context. |
| ... (Repeat only for players confirmed available and likely to play) ... | | | | | | | | | |

