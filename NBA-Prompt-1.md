**Prompt 1: NBA Game Prediction**

**Objective:** To predict the overall **team/game outcome** of a specified upcoming NBA game using a data-driven approach, establishing a foundational view before deeper player analysis (handled in Prompt 2).

**Core Principles:**

*   **Conceptual Scratchpad:** All retrieved data is stored conceptually for analysis. This scratchpad contains team-level data, lineups, injuries, and betting information relevant to the game prediction.
*   **Strict Data-First:** Perform necessary dynamic searches for each sub-step before proceeding with analysis or the next step and if required, use data from the scratchpad as input for prompt chaining dynamic searches.
*   **Use Reliable News Sources:** Use sources such as ESPN/NBA/Yahoo! Sports/NBC Sports/NewsNow/Hoopshype/Basketball Insiders/Hoops Rumors.
*   **Use Reliable Player Stats Sources:** Use sources such as ESPN/Basketball-Reference/Dunks and Threes/FiveThirtyEight’s RAPTOR/NBA Savant/Bball-Index/3StepsBasket/NBAstuffer/nba.com/lineups.com/fixturedownload.com.
*   **Iterative Data Retrieval Loop:** If data required for a step is not found initially, formulate targeted searches and loop the search process using prompt chaining methods from stored data as input if required until the data is reasonably found or confirmed unavailable. Do not proceed to the analysis portion of a step or to the next step until the data gathering for the current step is complete. Use reliable sources (official NBA/team sites, ESPN, Basketball-Reference, Statmuse, Covers, TeamRankings, reputable odds providers).
*   **Dynamic Updates:** Update the scratchpad if newer, more accurate data (e.g., late injury news) is found during the process.
*   **System Time:** Use the system date and time of +10 UTC for time-sensitive data like odds and injury reports.
*   **Continuation of Steps: Retrieve previsous output and stored scratch pad data to find where the last step was complete  or incomplete, conintuing from that position.

**Game Prediction Analysis Steps:**

1.  **Foundation Data Retrieval (Scratchpad Population):**
    *   Search & Store: Team Standings & Season Stats (RANK, TEAM, CONF, DIVISION, GP, PPG, oPPG, pDIFF, PACE, oEFF, dEFF, eDIFF, SoS, rSoS, SAR, CONS, A4F, W, L, WIN%, eWIN%, pWIN%, ACH, STRK for both teams).
    *   Search & Store: Personnel Information (Player Transfers - recent season, Full Player Depth Chart (Starters & Bench), *initial* Player Injury List).
    *   Search & Store: Baseline Betting Data (ATS Records - All, Straight Up Records - All, SU Units, Over/Under Trends - All for both teams).
    *   Search & Store: Initial Odds (Moneyline, main Handicap Betting Spread, main Total Points O/U).
    *   *(Analysis for this step: Confirm foundational data, including the full depth chart and initial injuries, is stored on the scratchpad.)*

2.  **Lineup, Rotation & Injury Update Data Retrieval:**
    *   Search & Store: Projected or confirmed starting Player Line-up for both teams.
    *   Search & Store: The absolute **latest updates** to the Player Injury List for both teams, focusing on confirmations or changes to GTD statuses for all players on the depth chart. Update the scratchpad with the *latest* injury status.
    *   *(Analysis for this step: Once lineups and the *latest* injury data are on the scratchpad, identify the **projected starters and key available bench players** for each team. Note the main players who are confirmed OUT or questionable based on the latest injury reports. This provides a **basic overview of player availability** for subsequent analysis steps. Store the projected lineups and key available/unavailable players list on the scratchpad.)*

3.  **Recent Form & Detailed Stats Data Retrieval:**
    *   Search & Store: Recent Results (Last 10 official games: Score, ATS result, O/U result for both teams).
    *   Search & Store: Detailed Team Stats (Averages over last 5-10 games: Points, FGM, FGA, FG%, 3PM, 3PA, 3P%, FTM, FTA, FT%, Possessions, Rebounds (Total, Off, Def), Assists, Turnovers, Steals, Blocks, Personal Fouls).
    *   Search & Store: Detailed Recent Betting Trends (ATS Records - All, ATS Records - 1st Half, ATS Records - 2nd Half for Home team at home / Away team away; Over/Under Trends - Away (for Away team), Over/Under Trends - Home (for Home team)).
    *   *(Analysis for this step: Once data is on scratchpad, analyze **team-level trends**, reasons for variance, sustainability, and compare betting trends to overall team performance. Store analysis notes.)*

4.  **Pace & Matchup Data Retrieval:**
    *   Search & Store: Recent PACE stats (last 5-10 games) for both teams.
    *   Search & Store (if needed): Specific *team-level* matchup data points (e.g., "Team B defensive rating vs opponent PnR last 5 games", "Team A points in paint allowed last 5 games") if deemed necessary for key strategic matchups identified from scratchpad data. Store on scratchpad.
    *   *(Analysis for this step: Once data is on scratchpad, project the likely overall game pace based on team tendencies. Analyze key **team-level strategic matchups** (e.g., Team A's offensive style vs. Team B's defensive scheme, rebounding battle, transition opportunities) using the gathered stats and player availability insights from Step 2. Store analysis notes on these strategic elements.)*

5.  **Detailed Odds Data Retrieval:**
    *   Search & Store: Current, specific betting odds: Handicap Betting (various lines), Total Points (various lines), Big Win Little Win, (Pick Your Own Line, handicap, WBLW) calaculate this from your analysis and findings that 'fit' the overall prediction based on the total points, updated Moneyline. Store on scratchpad.
    *   *(Analysis for this step: Once odds are on scratchpad, compare implied probabilities with your **independent analysis of the overall game synthesized** from all previously gathered scratchpad data. Identify agreement or disagreement between your assessment and the market.)*

6.  **Synthesize & Predict (Game):**
    *   *(Analysis for this step: Using ALL data gathered and analysis stored on the scratchpad through steps 1-5, synthesize the findings focusing on the **overall team dynamics and game flow**. Weigh conflicting data points (e.g., strong recent team form vs. tough team matchup, player availability impacts vs. betting line movement). Make the final **overall game predictions**.)*

**Output:**

*   Predicted Winning Team:
*   Predicted Spread Outcome (vs. main line):
*   Predicted Total Points Outcome (vs. main O/U line):
*   Projected Final Score:
*   Overtime Plausibility Note: (e.g., Low, Medium, High likelihood based on closeness of projection and team tendencies)
*   Justification: Briefly explain the key **team-level factors** from the scratchpad (e.g., pace clash, player availability, strategic matchup advantages, team trends, odds value) driving the predictions.

---

(add below the two teams playing and their odds)
EXAMPLE:

Atlanta Hawks @ Orlando Magic

Atlanta Hawks
2.48

Orlando Magic
1.57
