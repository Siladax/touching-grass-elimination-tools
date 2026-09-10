# Torn PDA installation

This guide installs the passive Touching Grass PDA Elimination Target Filter. It filters only the roster rows already loaded by Torn PDA and does not require a Torn API key.

## Recommended installation from Greasy Fork

1. Open [the PDA script on Greasy Fork](https://greasyfork.org/en/scripts/595270-touching-grass-pda-elimination-target-filter) inside the Torn PDA browser.
2. Tap **Install this script**.
3. If prompted, confirm that you have a userscript manager.
4. Review the script and tap **Install**.
5. In Torn PDA, open **Settings**.
6. Open **Advanced Browser Settings** and enable **User Scripts**.
7. Open **Manage Scripts** and confirm the Touching Grass PDA script is enabled.
8. Reload Torn and open an opposing Elimination team roster.

## Manual file installation

If direct Greasy Fork installation is unavailable:

1. Download [the PDA userscript from GitHub](https://github.com/Siladax/touching-grass-elimination-tools/raw/main/pda/Touching-Grass-PDA-Elimination-Target-Filter.user.js).
2. In Torn PDA, open **Settings**, then **Advanced Browser Settings**, and enable **User Scripts**.
3. Open **Manage Scripts**.
4. Tap the cog at the top.
5. Choose **Import from file**.
6. Select the downloaded userscript.
7. Leave the script selected and tap **Import**.
8. Confirm the script is enabled, then reload Torn.

## Using the filter

1. Open an opposing Elimination team roster.
2. Enter your total battle stats, such as `350m`, `1.2b`, or `350000000`.
3. Tap **Apply**.

Players estimated at 90% of your entered total or higher are hidden. **Show all** reveals all currently loaded rows.

## Important limitations

- The script does not load missing roster pages.
- FFScouter figures are estimates from a fixed snapshot and can become outdated.
- Torn performs the final availability check when an attack is opened.
- The PDA and desktop versions are separate because the page layouts differ.

## Privacy and request behavior

The PDA script makes no Torn API calls, background requests, multi-page roster requests, or external-service requests. It reads and filters only roster rows already displayed by Torn PDA.
