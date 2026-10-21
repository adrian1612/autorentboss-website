# AutoRentBoss website

Static, accessible website and public privacy policy for **AutoRentBoss** (Android car-rental management app).

## Files

- `index.html` — public landing page
- `privacy.html` — app privacy policy reflecting the October 11, 2026 implementation
- `styles.css` — responsive navy/teal design; no JavaScript, trackers, web fonts, or external build dependencies

## Publish with GitHub Pages

The repository is public but GitHub Pages has **not** been enabled as of this commit.

1. In repository **Settings → Pages**, under **Build and deployment**, select **Deploy from a branch**.
2. Choose branch `main`, folder `/(root)`, and save.
3. Wait for GitHub Pages to report deployment completed, then open:
   - Homepage: `https://adrian1612.github.io/autorentboss-website/`
   - Privacy Policy: `https://adrian1612.github.io/autorentboss-website/privacy.html`
4. Verify the privacy page opens in a private/incognito browser without GitHub sign-in before placing it in **Google Play Console → App content → Privacy policy**.
5. Also add a Privacy Policy entry within the Android application itself; Google Play requires an in-app privacy policy link or text.

**These URLs are prospective until Pages is enabled and an actual deployment succeeds.** Do not submit an unavailable URL to Google Play.

## Pre-release owner checklist

- [ ] Provide a private **developer support/privacy email** and replace the temporary contact-via-Play-listing instructions in `privacy.html`; a public GitHub issue is unsuitable for sharing personal data.
- [ ] Reconcile the developer identity and contact information with the actual Google Play store listing.
- [ ] Review Android `allowBackup="true"` and the sensitive renter documents it could include; decide and test the platform backup/extraction rules before Play release.
- [ ] Publish/configure the AdMob UMP consent message and ensure privacy options work.
- [ ] Complete Google Play Data safety and Ads declarations consistent with the shipped SDK version and actual functionality.
- [ ] Update the policy before introducing live subscriptions, cloud verification, new analytics, or additional data sharing.
- [ ] Confirm retention and business-operator data deletion workflows are accurately described.

Current AutoRentBoss source reviewed: `adrian1612/AutoRentBoss` `master` at `ffb92997a74c31b74dee49f002a4cc98276adb6a`.

**No GitHub Actions were manually triggered.** This website requires no dependencies or build system.


## Approved cinematic homepage (October 2026)

The homepage now follows the operator-approved photographic concept, using a realistic sedan hero and photographic vehicle/contract feature panels. The hero and feature images are externally hosted on Unsplash; mobile and desktop layouts must be checked after Pages publishes.

- Hero: Ilya Godze — https://unsplash.com/photos/black-luxury-sedan-parked-on-a-wet-street-at-night-9xhwtVIM0dE
- Vehicle-key photo: Nathan Dumlao — https://unsplash.com/photos/black-and-silver-keys-on-black-textile-wN7Dtu0saNs
- Signing photo: Jakub Żerdzicki — https://unsplash.com/photos/man-signing-a-document-with-a-pen-QI6NLgN5XnM
- Blurred mobile mockup background: Fernando Hernandez — https://unsplash.com/photos/a-black-car-parked-in-a-garage-DmvrGxLF4F8

All these photographs are marked free to use under the Unsplash License. They are decorative and do not depict AutoRentBoss customers. The phone mockup is an illustration, **not** a verified screenshot of the Android app. `approved.css` extends the existing static site's styles without affecting the privacy policy.

No fictitious app statistics, nonexistent Play Store links, user testimonials or online booking features have been added.
