# Torn PDA installation

This guide installs the passive Touching Grass PDA Elimination Target Filter. It filters only roster rows already loaded by Torn PDA and does not require a Torn API key.

**Do not try to open Greasy Fork from inside Torn PDA.** Torn PDA does not provide a working path to the Greasy Fork installer. Download the script with Safari or Chrome first, then import the saved file into Torn PDA.

## Download the script

1. Outside Torn PDA, open this direct download in Safari or Chrome:
   [Download the Touching Grass PDA userscript](https://github.com/Siladax/touching-grass-elimination-tools/raw/main/pda/Touching-Grass-PDA-Elimination-Target-Filter.user.js)
2. If the script opens as a page of text, use the browser's **Share** or download control and choose **Save to Files**.
3. Keep the filename ending in **.user.js**. Do not copy and paste the code.
4. Remember the folder where you saved it, usually **Downloads**.

The PDA version is also published on [Greasy Fork](https://greasyfork.org/en/scripts/595270-touching-grass-pda-elimination-target-filter), but its **Install this script** button is not the installation method used by Torn PDA.

## Enable scripts in Torn PDA

1. Open Torn PDA.
2. Open **Settings**.
3. Open **Advanced Browser Settings**.
4. Enable **User Scripts**.

## Import the downloaded file

1. In Torn PDA, open **Manage Scripts**.
2. Tap the **cog** at the top.
3. Choose **Import from file**.
4. Browse to the folder where the script was saved.
5. Select **Touching-Grass-PDA-Elimination-Target-Filter.user.js**.
6. On the Import Options screen, leave the Touching Grass script selected.
7. Tap **Import**.
8. Confirm the script appears in Manage Scripts and is enabled.
9. Reload Torn.

## Use the filter

1. Open Torn's Elimination page.
2. Open an opposing team's individual roster page.
3. Wait for Torn to display the roster rows. The **Touching Grass Targets** panel should appear above them.
4. Enter your total battle stats, such as `350m`, `1.2b`, or `350000000`.
5. Tap **Apply**.

Players estimated at 90% of your entered total or higher are hidden. Tap **Show all** to reveal every currently loaded row.

## If the script does not appear

- Confirm **User Scripts** is enabled in Advanced Browser Settings.
- Confirm the script is switched on in Manage Scripts.
- Confirm the downloaded filename ends in **.user.js**, not **.txt**.
- Reload Torn after importing.
- Open an individual opposing-team roster rather than only the main Elimination standings page.
- If another script changes the roster layout, temporarily disable it and reload.

## Important limitations

- The script does not load missing roster pages.
- FFScouter figures are estimates from a fixed snapshot and can become outdated.
- Torn performs the final availability check when an attack is opened.
- The PDA and desktop versions are separate because their page layouts differ.

## Privacy and request behavior

The PDA script makes no Torn API calls, background requests, multi-page roster requests, or external-service requests. It reads and filters only roster rows already displayed by Torn PDA.
