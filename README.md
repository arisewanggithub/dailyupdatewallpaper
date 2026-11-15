# Daily Update Wallpaper website

Public website and privacy policy for Daily Update Wallpaper for Windows
(Microsoft Store product `9NZVVM6WW02H`). This repository contains only the
static website, not application source code.

- Temporary website: https://arisewanggithub.github.io/dailyupdatewallpaper/
- Temporary privacy policy: https://arisewanggithub.github.io/dailyupdatewallpaper/privacypolicy/dailyupdatewallpaper.html
- Microsoft Store: https://apps.microsoft.com/detail/9NZVVM6WW02H

GitHub Pages serves the root of `main`. The site uses plain HTML and CSS with
relative links, no build step, no analytics, and no external fonts or scripts.
The privacy policy retains the path from the retired Azure Blob Storage URL.
The retired policy text was not available in the current app source snapshot.
The replacement policy describes the reviewed wallpaper, local-storage, and
Microsoft Application Insights diagnostic behavior; it does not claim that the
app collects no data or promise unverified telemetry retention or opt-out rules.

## Custom domain handoff

The owner will configure the custom domain and its DNS records. No custom
domain is configured as part of the initial setup.

After the owner finishes domain setup:

1. Verify that the homepage and privacy policy load over HTTPS.
2. Update the website URLs in this README and the repository homepage setting.
3. Update the privacy policy URL in Microsoft Partner Center to
   `https://<custom-domain>/privacypolicy/dailyupdatewallpaper.html`.

Do not update Partner Center until the custom-domain privacy URL is verified.
