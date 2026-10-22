# A Portfolio Project

This is a portfolio website for kennedy Wambua (Homemix)

## App privacy policies

- Policy directory: https://homemix.github.io/privacy/
- BlinkTrap privacy policy (for Play Console): https://homemix.github.io/privacy/blinktrap.html

The directory is linked from the portfolio footer. Each app has its own permanent
HTML policy URL. The privacy pages use `assets/css/privacy.css`, local assets, and
system fonts, without JavaScript, analytics, or tracking cookies.

To add another app, create a policy HTML file in `privacy/` and add a linked card
to `privacy/index.html`. Keep existing policy URLs stable for published apps.

### Publishing BlinkTrap's policy

These URLs assume this repository is served at its default GitHub Pages hostname.
Local files do not publish themselves: deploy the changes through the repository's
GitHub Pages publishing source, then open the policy URL while signed out to
confirm it is publicly accessible over HTTPS without a login or geographic restriction.
Use the live HTML URL, not the concept PDF or a GitHub source-file URL, in Play Console.

Before submitting the app:

1. Verify the released Android app, its permissions, backup configuration, and all
   dependencies match the policy. Its content follows the confirmed offline
   first-release scope in `docs/BlinkTrap_Game_Concept_and_Requirements.pdf`;
   the Android app source is not in this repository and has not been audited here.
2. Ensure `thewolfdevs@gmail.com` is monitored for privacy enquiries and the stated
   support-data handling is followed. Review the effective date and update the
   policy whenever data practices change.
3. Add the live policy link inside BlinkTrap (for example, in Settings) in its
   separate Flutter project, and enter it in Play Console's privacy-policy field.
4. Complete Data safety, target-audience, content-rating, and ads declarations
   accurately. BlinkTrap is intended for all ages, including children: review
   applicable Google Play Families requirements and children's privacy laws.
   Hosting a policy alone does not establish app compliance or guarantee approval.

Google Play reference: [User Data policy](https://support.google.com/googleplay/android-developer/answer/10144311?hl=en).