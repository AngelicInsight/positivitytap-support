# Privacy Policy for Positivity Tap

**Last updated:** February 23, 2026

## Overview

Positivity Tap ("the App") is developed by AngelicInsight. We are committed to protecting your privacy. This privacy policy explains our practices regarding data collection and usage.

## Data Collection

Positivity Tap collects minimal data necessary to provide game features:

### Locally Stored Data
The following data is stored **only on your device** and never transmitted:
- High scores and game progress
- Sound, haptic, and appearance preferences
- Your chosen display name (for Group Sessions)

### Game Center (Apple)
If you choose to sign in to Game Center, the App uses Apple's Game Center service to provide global and weekly leaderboards. When you submit a score:
- Your **score** is sent to Apple's Game Center servers
- Your **Game Center display name** may be visible to other players on leaderboards
- Game Center is managed entirely by Apple. Please refer to [Apple's Privacy Policy](https://www.apple.com/privacy/) for details on how Apple handles Game Center data.

Game Center sign-in is optional. The app functions fully without it.

### Group Sessions (Firebase)
If you choose to join or create a Group Session, the following data is sent to our Firebase Realtime Database (hosted by Google):
- Your **chosen display name** (entered by you — not your real name unless you choose to use it)
- Your **game scores**, level, combo count, and star rating
- **Session metadata**: session code, session name, creation timestamp
- **Session admin PIN** (if you create a session)

This data is used solely to power the real-time Group Session leaderboard feature. We do **not** collect:
- Email addresses, phone numbers, or Apple IDs
- Device identifiers or IP addresses for tracking
- Location data
- Any data from children beyond what is listed above

Group Session data is automatically deleted after 30 days.

## Third-Party Services

| Service | Purpose | Data Shared | Privacy Policy |
|---------|---------|-------------|----------------|
| Apple Game Center | Global leaderboards | Scores, Game Center display name | [Apple Privacy](https://www.apple.com/privacy/) |
| Google Firebase Realtime Database | Group Session leaderboards | Display name, scores, session data | [Google Privacy](https://policies.google.com/privacy) |

No advertising networks, analytics platforms, or other third-party services are used.

## Children's Privacy

Positivity Tap is designed to be safe for users of all ages, including educational/classroom settings. We do not knowingly collect personal information from children under 13. The display names used in Group Sessions are freely chosen by the user and do not need to be real names. No account creation or login is required.

If a parent or guardian believes their child has provided personal information through the App, please contact us and we will promptly delete it.

## Data Retention

- **Local data**: Stored on your device until you uninstall the App.
- **Group Session data**: Automatically deleted from Firebase after 30 days.
- **Game Center data**: Managed by Apple per their retention policies.

## Your Rights

Since we do not collect identifying information, we cannot associate stored data with specific individuals. If you wish to remove your Group Session scores, you can ask the session host to end the session, or the data will be automatically deleted after 30 days.

## Changes to This Policy

If we make changes to this privacy policy, we will update the "Last updated" date above.

## Contact

If you have any questions about this privacy policy, please open an issue at:
https://github.com/AngelicInsight/positivitytap-support/issues

---

**Summary:** We collect minimal data for leaderboards (Game Center scores + Group Session names/scores via Firebase). No ads, no tracking, no analytics. Group Session data auto-deletes after 30 days.
