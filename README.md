# Daily Update Wallpaper website

Public website and privacy policy for Daily Update Wallpaper for Windows
(Microsoft Store product `9NZVVM6WW02H`). This repository contains only the
static website, not application source code.

- Website: https://dailyupdatewallpaper.redrain.ccwu.cc/
- Privacy policy: https://dailyupdatewallpaper.redrain.ccwu.cc/privacypolicy/dailyupdatewallpaper.html
- Sitemap: https://dailyupdatewallpaper.redrain.ccwu.cc/sitemap.xml
- Microsoft Store: https://apps.microsoft.com/detail/9NZVVM6WW02H

GitHub Pages serves the root of `main`. The site uses plain HTML and CSS with
relative links, no build step, no analytics, and no external fonts or scripts.
The privacy policy retains the path from the retired Azure Blob Storage URL.
The retired policy text was not available in the current app source snapshot.
The replacement policy describes the reviewed wallpaper, local-storage, and
Microsoft Application Insights diagnostic behavior; it does not claim that the
app collects no data or promise unverified telemetry retention or opt-out rules.

## Custom domain and search discovery

The owner configured `dailyupdatewallpaper.redrain.ccwu.cc` as the GitHub Pages
custom domain. HTTPS is enforced. Keep `CNAME`, page canonical links, sitemap
URLs, the robots sitemap declaration, and the repository homepage setting
consistent if the domain changes.

The sitemap lists the homepage and privacy policy. When adding or renaming a
public page, update the sitemap and its canonical link to the final HTTPS URL.

Submit `https://dailyupdatewallpaper.redrain.ccwu.cc/sitemap.xml` in Google
Search Console under the existing `redrain.ccwu.cc` domain property. Submission
does not guarantee that Google will fetch the sitemap or index its pages.

Use the custom-domain privacy policy URL in Microsoft Partner Center only after
verifying that it loads successfully over HTTPS.
