**Prompt V3**

Prompt 1: NBA Game Prediction (Team/Game Focus)

Objective: Predict the overall team/game outcome of a specified next upcoming NBA game. This prompt uses a data-driven approach focused on team-level factors, incorporating only brief, essential player availability information (lineups, injuries) to establish a foundational view. Deeper individual player analysis is handled separately (in Prompt 2).

Core Principles:

Conceptual Scratchpad: All retrieved data is stored conceptually for analysis. This scratchpad contains team-level data, basic personnel lists (depth charts, injuries), projected lineups, betting information, and analysis notes relevant only to the team/game prediction. Store the timestamp of key data retrieval points (e.g., injury checks, odds checks).

Strict Data-First: Perform necessary dynamic searches for each sub-step before proceeding with analysis or the next step. Use data from the scratchpad as input for prompt chaining if required.

Use Reliable News Sources: ESPN, NBA.com, Yahoo! Sports, NBC Sports, NewsNow, Hoopshype, Basketball Insiders, Hoops Rumors, etc.

Use Reliable Stats Sources: ESPN, Basketball-Reference, NBA.com, TeamRankings, Statmuse, Covers, official team sites, reputable odds providers, etc. (Focus on team stats where possible).

Iterative Data Retrieval Loop: If data required for a step is not found initially, formulate targeted searches and loop until the data is reasonably found or confirmed unavailable. Do not proceed until data gathering for the current step is complete.

Dynamic Updates: Update the scratchpad if newer, more accurate data (e.g., late injury news) is found.

Continuation of Steps: When continuing analysis, use the previously generated output, including any revisions, to ensure required data is present and context is maintained.

System Date: 2025

Game Prediction Analysis Steps:

Foundation Data Retrieval (Scratchpad Population):

Search & Store: Team Standings & Season Stats (RANK, TEAM, CONF, DIVISION, GP, PPG, oPPG, pDIFF, PACE, oEFF, dEFF, eDIFF, SoS, rSoS, SAR, CONS, A4F, W, L, WIN%, eWIN%, pWIN%, ACH, STRK for both teams).

Search & Store: Basic Personnel Information (List of Player Transfers - recent season, Full Player Depth Chart list, initial Player Injury List list).

Search & Store: Baseline Betting Data (ATS Records - All, Straight Up Records - All, SU Units, Over/Under Trends - All for both teams).

Search & Store: Initial Odds (Moneyline, main Handicap Betting Spread, main Total Points O/U).

(Analysis for this step: Confirm foundational team data, player lists, and initial odds are stored on the scratchpad. No player analysis here.)

Lineup & Injury Update Data Retrieval (Essential Availability):

Search & Store: Projected or confirmed starting Player Line-up for both teams.

Search & Store: The absolute latest updates to the Player Injury List for both teams (focus: OUT, Doubtful, Questionable statuses for players on the depth chart). Update the scratchpad with the latest injury status list.

(Analysis for this step: Once lineups and the latest injury data are on scratchpad, simply identify the projected starters and list key players confirmed OUT or highly questionable. This provides a brief overview of player availability to inform team-level analysis only. Avoid detailed player impact analysis. Store the projected lineups and key available/unavailable players list on the scratchpad.)

Recent Form & Detailed Team Stats Data Retrieval:

Search & Store: Recent Results (Last 10 official games: Score, ATS result, O/U result for both teams).

Search & Store: Detailed Team Stats (Averages over last 5-10 games: Points, FGM, FGA, FG%, 3PM, 3PA, 3P%, FTM, FTA, FT%, Possessions, Rebounds (Total, Off, Def), Assists, Turnovers, Steals, Blocks, Personal Fouls).

Search & Store: Detailed Recent Betting Trends (ATS Records - All, ATS Records - 1st Half, ATS Records - 2nd Half for Home team at home / Away team away; Over/Under Trends - Away (for Away team), Over/Under Trends - Home (for Home team)).

(Analysis for this step: Once data is on scratchpad, analyze team-level trends, reasons for variance, sustainability, and compare betting trends to overall team performance. Store analysis notes.)

Pace & Team Matchup Data Retrieval:

Search & Store: Recent Team PACE stats (last 5-10 games) for both teams.

Search & Store (if needed): Specific team-level matchup data points (e.g., "Team B defensive rating vs Pick & Roll last 5 games", "Team A points allowed in paint last 5 games") if deemed necessary for key strategic matchups identified from scratchpad data. Store on scratchpad.

(Analysis for this step: Once data is on scratchpad, project the likely overall game pace based on team tendencies. Analyze key team-level strategic matchups (e.g., Team A's offensive style vs. Team B's defensive scheme, rebounding battle, transition opportunities) using gathered stats and the brief player availability context from Step 2 (e.g., noting if a team might be weaker defensively overall due to key absences). Store analysis notes on these team strategic elements.)

Detailed Odds Data Retrieval:

Search & Store: Current, specific betting odds: Handicap Betting (various lines), Total Points (various lines), updated Moneyline.

(Analysis for this step: Once odds are on scratchpad, compare implied probabilities with your independent analysis of the overall game synthesized from all previously gathered team-focused scratchpad data and brief availability context. Identify agreement or disagreement between your assessment and the market.)

Synthesize & Predict (Game):

(Analysis for this step: Using ALL data gathered and analysis stored on the scratchpad through steps 1-5 (ensuring injuries/odds are based on latest checks), synthesize the findings focusing strictly on overall team dynamics, team trends, team strategic matchups, and game flow. Consider the high-level impact of player availability (from Step 2 list) on the team's overall capability, but avoid detailed player-vs-player analysis. Weigh conflicting team-level data points. Make the final overall game predictions.)

Output:

Predicted Winning Team:

Predicted Spread Outcome (vs. main line):

Predicted Total Points Outcome (vs. main O/U line):

Projected Final Score:

Overtime Plausibility Note: (e.g., Low, Medium, High likelihood based on closeness of projection and team tendencies)

Justification: Briefly explain the key team-level factors and significant player availability impacts (e.g., "Team A missing primary ball-handler impacting overall offense") from the scratchpad driving the predictions. Focus on team trends, pace, team strategic advantages/disadvantages, and odds value.
