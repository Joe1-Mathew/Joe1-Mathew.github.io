# Humanoid Lab — Public Engineering Portfolio (Rev 02)

This folder is a ready-to-host STATIC website (`index.html` plus `assets/`).

## What's updated
- Current **three-part** right-foot baseline: rubber outsole, 6061-T6 aluminum bracket, and deep-indigo FDM PLA cosmetic/exterior cover.
- Carbon fiber explicitly **removed from the baseline** and retained as an unverified future controlled comparison.
- Separate M4 attachment interfaces: six lower cover-to-aluminum bolted positions and six upper future exterior mounting positions.
- Design for Reliability rationale for lower screws rather than magnets.
- Brass heat-set inserts deferred: hardware has not been obtained for actual installation-bore fit and retention testing.
- SOLIDWORKS acrylic assignment identified as a **temporary material placeholder**, to be changed to process-specific PLA print properties; printed PLA anisotropy is acknowledged.
- Automatic tree / organic supports described as a **slicing plan**, not a completed print.
- Gallery includes a CAD screenshot cropped to show only the current foot, the source SOLIDWORKS screenshot, and a view of the purple exterior shell.

## Public web hosting (GitHub Pages)
1. Create a PUBLIC repository (for example `humanoid-lab`).
2. Upload **index.html and the complete assets/** folder from this package to the repository root.
3. In repository Settings → Pages, select **Deploy from a branch**, then `main` and `/ (root)`, and save.
4. After GitHub publishes the site, the URL generally has the form `https://YOUR_USERNAME.github.io/humanoid-lab/`.

No actual web host was connected or deployed by this package; it is publication-ready, not live.

## Safety and privacy of the site content
The web pages are public if hosted publicly. Notes and journal inputs are stored via **localStorage in the visitor's browser**, are not transmitted by the site's own JavaScript, and **are not public or shared between users**. Their contents do not become part of the site without editing and republishing the HTML yourself. The browser's local storage should not be treated as a secure or synchronized backup. The Export/Import JSON tools remain available.

## Standalone version
`Humanoid_Lab_Public_Standalone.html` (provided separately) embeds the gallery images directly and can be opened from disk in a modern browser without an `assets` folder. It has the same static public-facing copy; it is not a deployed website.

## Engineering limits
No manufacturing, fatigue, joint-retention or locomotion performance result is asserted beyond the prior geometric rule screenshots. Estimates of density are generic, not measured filament parameters. All print/bolt/CFRP validation remains future work.
