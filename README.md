# Soccer Draft

A ten-team draft for a list of soccer players, run from a spreadsheet. The program is a single file, `soccer-draft.html`: open it in any recent browser (Chrome, Edge, Firefox, Safari). Nothing needs to be installed.

## Start

1. **Spreadsheet.** The program opens with the built-in list, `Rosa_per_ruolo.xlsx` (418 players, 13 roles). To use another list, click **Load a different spreadsheet** or drop the file on the page. Excel (.xlsx) and CSV files are accepted. The sheet needs the columns **Name**, **Role** and **Overall** (Score also works), one player per row. Rows with a missing value are left out and listed.
2. **Team names.** Name the ten teams. An empty field keeps the default name (Team 1, Team 2 …).
3. Click **Start draft**.

## Draft

- Choose a role. The players with that role are listed from the highest overall down.
- Click a player, then the team to assign them to. The assignment is recorded at once.
- An assigned player turns darker, shows the team name, and cannot be selected again.
- **Undo** in the message at the bottom reverses the last action.

## Teams

The teams are listed on the left (at the top on a phone) and can be opened at any moment. A team page shows its players divided by role, each role ordered by overall. **Remove** takes a player out of the team and makes them available again on the draft board. **Rename** changes the team name.

## Saving

The draft is saved automatically in the browser. When the program is opened again, **Resume draft** returns to it. The draft stays in the browser where it was made, so use the same browser (and keep the file in the same folder) to resume it.

**Export teams (.xlsx)** downloads a spreadsheet with every team, one sheet per team, and the players still unassigned.

**New draft** goes back to the start screen. The current draft is replaced only after you confirm.
