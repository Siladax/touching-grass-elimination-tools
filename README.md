# Touching Grass Elimination Tools

Target-filtering userscripts for Torn City's Elimination event. The desktop and Torn PDA editions are separate because their page layouts differ.

## Desktop browser

- [Install from Greasy Fork](https://greasyfork.org/en/scripts/595263-touching-grass-live-elimination-targets)
- [View the desktop source](desktop/Touching-Grass-Live-Elimination-Targets.user.js)
- Current repository version: **2.3.10**

Use Tampermonkey in Chrome and ensure Chrome's extension setting **Allow User Scripts** is enabled.

## Torn PDA

- [Read the Torn PDA Greasy Fork installation guide](docs/PDA-INSTALLATION.md)
- [View the Greasy Fork listing](https://greasyfork.org/en/scripts/595270-touching-grass-pda-elimination-target-filter)
- [View the PDA source](pda/Touching-Grass-PDA-Elimination-Target-Filter.user.js)
- Current repository version: **4.1.0**

For reliable installation, add the Greasy Fork `.user.js` address through Torn PDA's **Manage Scripts → plus sign → Remote load/update → Configure** screen, then tap **Fetch** and **Load**. This keeps the script connected to Greasy Fork for updates.

The PDA version is passive: it filters only the roster rows Torn PDA has already loaded and requires no Torn API key.

## Compliance

The current published scripts do not automate Torn API requests or loop through roster pages. The PDA edition makes no network requests. The desktop edition observes data Torn already retrieves and does not create automated/background Torn requests.

## Support

Use [GitHub Issues](https://github.com/Siladax/touching-grass-elimination-tools/issues) to report a problem or suggest an improvement.

These are community userscripts and are not affiliated with or endorsed by Torn, Torn PDA, or FFScouter.
