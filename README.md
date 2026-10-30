# Rise Tracker

A browser-based checklist for Rise Kujikawa's battle dialogue in **Persona 4 Golden** (PC/Steam), built around the *Hardcore Risette Fan* achievement.

**Site:** https://shinkiz0805.github.io/Rise-Tracker/

## What it does

- Reads recorded dialogue flags from a local P4G save file.
- Shows recorded and missing lines, with filters for party members and battle situations.
- Includes suggested triggers for each line, with labels for uncertain conditions.
- Optionally compares two saves from the same playthrough to find newly recorded lines.
- Exports the filtered list to CSV.

No Cheat Engine installation or account is required.

## How to use

1. Open the site in a desktop browser.
2. Find your P4G save in Steam's `userdata` folder. A typical path is:
   ```text
   Steam\userdata\YOUR_STEAM_ID\1113000\remote\data0001.bin
   ```
   The filename changes with the save slot (`data0002.bin`, etc.).
3. Choose a **copy** of the file under **Current save**.
4. Use the **Missing** tab and the character or situation filters to narrow down the list.
5. To compare progress, optionally load an **older save from the same playthrough**.

Save files are read in the browser. The site does not modify or upload them.

## Compatibility

- Tested with **217,937-byte `.bin` files** from the PC/Steam version of Persona 4 Golden.
- Console saves and other file formats have not been validated.
- The map contains **625 dialogue flags**, including special and internal entries. Not all mapped entries are confirmed to count toward the achievement.
- The game's one-byte counter wraps after 255; the tracker counts mapped flags instead.
- The line names are fetched from the public `rise.tsv` file in the [p4g-ct](https://github.com/zarroboogs/p4g-ct) project. You can also import that file manually if the request fails.
- Some suggested triggers are inferred from the dialogue rather than documented in the game. Check the confidence labels, especially for boss-specific lines.

## Sources

- [zarroboogs/p4g-ct](https://github.com/zarroboogs/p4g-ct) — dialogue flag locations and line identifiers.
- [Hardcore Risette Fan guide on GameFAQs](https://gamefaqs.gamespot.com/xbox-series-x/370653-persona-4-golden/faqs/81937/hardcore-risette-fan) — battle conditions and achievement notes.

This is an unofficial fan project and is not affiliated with Atlus or SEGA.
