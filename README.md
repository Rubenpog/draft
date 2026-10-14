# Soccer Draft

A ten-team draft for a list of soccer players, run from a spreadsheet. The program is a single file, `index.html`: open it in any recent browser (Chrome, Edge, Firefox, Safari). Nothing needs to be installed. (`soccer-draft.html` only forwards to `index.html`, for links made before the file was renamed.)

## Start page

The program opens on two choices.

- **Continue** returns to a draft already started:
  - **Last draft** is the draft saved in this browser. **Continue this draft** opens it where it was left.
  - **Saved draft file** opens a file made with **Export teams (.xlsx)**, from this or another computer. Click **Open a saved draft** or drop the file on the page. Files exported by the first version of the program also open.
- **New draft** prepares a new draft (see below).

If a draft is in progress, starting a new one or opening a saved file asks first: **Save draft (.xlsx)** saves the current draft as a file, **Don’t save** goes on without saving, **Cancel** stops. The draft in progress is replaced only when the new one starts.

## New draft

1. **Spreadsheet.** The page offers the built-in list, `Rosa_per_ruolo.xlsx` (418 players, 13 roles). To use another list, click **Load a different spreadsheet** or drop the file on the page. Excel (.xlsx) and CSV files are accepted. The sheet needs the columns **Name**, **Role** and **Overall** (Score also works), one player per row. Rows with a missing value are left out and listed.
2. **Team names.** Name the ten teams. An empty field keeps the default name (Team 1, Team 2 …). **Clear names** empties every field.
3. Click **Start draft**.

## Draft

- Choose a role. The players with that role are listed from the highest overall down.
- Click a player, then the team to assign them to. The assignment is recorded at once.
- An assigned player turns darker, shows the team name, and cannot be selected again.
- **Undo** in the message at the bottom reverses the last action.

## Teams

The teams are listed on the left (at the top on a phone) and can be opened at any moment. A team page shows its players divided by role, each role ordered by overall. **Remove** takes a player out of the team and makes them available again on the draft board. **Rename** changes the team name.

## Saving

The draft is saved automatically in the browser where it is made. To keep a copy, or to continue on another computer, use **Export teams (.xlsx)**. The file has one sheet per team and a sheet with the players still unassigned. It also holds the whole draft in a hidden sheet, so **Continue › Saved draft file** can open it again exactly as it was.

Clicking **Soccer Draft** at the top of the draft returns to the start page.

## Settings

The settings button (top right on every page) opens a small menu. The choices are kept in the browser.

- **Appearance:** Auto (follows the device), Light or Dark.
- **Text size:** Standard or Large. Large is easier to read on a TV or a projector.
- **Hide assigned players:** shows only the players still available on the draft board.
