# Torn PDA installation

This guide installs the Touching Grass PDA Elimination Target Filter from Greasy Fork using Torn PDA's **Remote load/update** feature. This is the preferred method because Torn PDA can fetch the script and track future updates.

The filter uses no Torn API key. It filters only roster rows already loaded by Torn PDA.

## Enable user scripts

1. Open Torn PDA.
2. Open **Settings**.
3. Open **Advanced Browser Settings**.
4. Enable **User Scripts**.
5. Open **Manage Scripts**.

## Install from Greasy Fork using Remote URL

1. In **Manage Scripts**, tap the **plus sign** at the top.
2. Find **Remote load/update** and tap **Configure**.
3. Paste this address into the **Remote URL** field:

   `https://update.greasyfork.org/scripts/595270/Touching%20Grass%20PDA%20Elimination%20Target%20Filter.user.js`

4. Tap **Fetch**.
5. After Torn PDA retrieves the script, tap **Load**.
6. Confirm **Touching Grass PDA Elimination Target Filter** appears in Manage Scripts and is enabled.
7. Open the script settings and set **Injection time** to **End** if it is not already selected.
8. Reload Torn.

Using the Remote URL is more reliable than trying to browse to Greasy Fork inside Torn PDA. It also allows Torn PDA to recognize future script updates.

## Alternative direct Greasy Fork method

On Torn PDA versions that support Greasy Fork interception:

1. Open the [Greasy Fork listing](https://greasyfork.org/en/scripts/595270-touching-grass-pda-elimination-target-filter) through Torn PDA.
2. Tap **Install this script**.
3. If Greasy Fork asks, tap **I have a userscript manager, let me install it**.
4. Complete the Fetch and Load prompts in Torn PDA.

If the install button does nothing or the listing cannot be opened in Torn PDA, use the **Remote URL** method above.

## Use the filter

1. Open Torn's Elimination page.
2. Open an opposing team's individual roster.
3. Wait for Torn to display roster rows. The **Touching Grass Targets** panel should appear above them.
4. Enter your total battle stats, such as `350m`, `1.2b`, or `350000000`.
5. Tap **Apply**.

Players estimated at 90% of your entered total or higher are hidden. Tap **Show all** to reveal every currently loaded row.

## If the script does not appear

- Confirm **User Scripts** is enabled.
- Confirm the script is enabled in **Manage Scripts**.
- Confirm the entire Remote URL was pasted, including the ending **.user.js**.
- Open the script settings and set **Injection time** to **End**.
- Reload Torn after loading the script.
- Open an individual opposing-team roster rather than only the main Elimination standings page.
- If another script changes the roster layout, temporarily disable it and reload.

## Important limitations

- The script does not load missing roster pages.
- FFScouter figures are estimates from a fixed snapshot and can become outdated.
- Torn performs the final availability check when an attack is opened.
- The PDA and desktop versions are separate because their page layouts differ.

## Privacy and request behavior

The PDA script makes no Torn API calls, background requests, multi-page roster requests, or external-service requests. It reads and filters only roster rows already displayed by Torn PDA.

## References

- [Torn community guide to installing scripts in Torn PDA](https://www.torn.com/forums.php?p=threads&t=16347522)
- [Torn PDA userscript documentation](https://github.com/Manuito83/torn-pda/blob/master/userscripts/README.md)
