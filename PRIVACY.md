# Privacy Policy — Snake

**Last updated:** May 3, 2026

## Contact

Questions about this policy:

**Email:** rmndevapps@gmail.com

## Who we are

**Snake** (“the app”) is a **retro-style Snake game** for **iPhone, iPad, and Mac** (where distributed). You steer the snake on a grid, collect food, avoid collisions (including optional brick obstacles), and try for a high score. **Core play does not require an internet connection.**

This policy describes how information is handled when you use the app.

## Information we do not collect

- We **do not** require an account or sign-in to use the app’s main features.
- We **do not** ask for your name, email address, phone number, or mailing address inside the app for those features.
- We **do not** sell your personal information.
- The app is **not** designed to upload your scores, settings, or gameplay events to our servers; **we do not operate a backend** that receives that data for the version described here.
- The app does **not** request access to the camera, microphone, photo library, contacts, or precise location for the features described here.
- The current version does **not** include an in-app **share sheet** or other flow that sends your score or stats to apps or services you pick.

If this changes in a future version, we will update this policy and, where required, the App Store **App Privacy** details for the app.

## Information stored on your device

The app stores data **locally on your device** using Apple’s standard app storage (**UserDefaults**).

### Settings

Gameplay and presentation preferences are stored as structured settings (JSON under `snake.gameSettings.v1`), including:

- **Language** — English or Russian; until you change it in Settings, the app uses a **built-in default** for the UI  
- **Gameplay** — e.g. teleport-through-walls, speed-up as the snake grows, brick obstacles and apple interval, board cell density, snake speed  
- **Feedback** — sound effects on/off, vibration on/off  
- **Background music** — off or one of the bundled loop tracks  

### Local high scores

Up to **10 numeric high scores** (integers only) are stored locally (JSON under `snake.highScores.v1`). They are **not** tied to an account or a name you enter in the app.

### Active game session

While you are playing (and briefly in related on-screen flows), **game state** (for example snake position, direction, score, and timers) exists **in memory**. It is **not written to UserDefaults** as a persistent log and is **not** synced to our servers in the version described here. Leaving the game screen or terminating the app clears that session from memory according to normal system behavior.

Bundled graphics and audio ship inside the app; they are not personalized tracking data.

This data stays on your device in the app sandbox. **We cannot access it remotely.** Deleting the app normally removes local settings and stored scores (subject to how your device handles app data).

## Sharing and third parties

Because the version described here does **not** upload gameplay data to us and does **not** embed a user-triggered share flow for scores, **we do not receive** your game content through those channels.

Apple provides **iOS**, **iPadOS**, **macOS**, and the **App Store**; their terms and privacy practices apply separately.

The current codebase does not embed third-party analytics or advertising SDKs for the behavior described here. If that changes, we will update this policy and App Store **App Privacy**.

## Analytics and crash reporting

The app is intended to work **without** third-party analytics SDKs, cloud sync of your scores, or a developer-operated backend for session data in the version described here.

If we add optional analytics, crash reporting, or in-app purchases later, we will update this policy and **App Privacy** to describe what is collected or processed, why, and your choices.

## Children’s privacy

The app is a general-purpose arcade game. We do **not** knowingly collect personal information from children through the app as described above (no account, no deliberate collection of contact details in-app). If you believe a child has shared personal data with us via email, contact us and we will address it.

## Your rights (EEA, UK, and similar regions)

Depending on where you live, you may have rights regarding personal data. **Most information described here stays on your device**, not on our systems. For requests about information we hold (for example, an email you sent us), contact **rmndevapps@gmail.com**. You may also complain to your local data protection authority.

## California residents (CCPA / CPRA)

We do not “sell” or “share” personal information as those terms are commonly defined in California privacy law for the processing described in this policy. If you contact us with a verifiable California request, we will respond according to applicable law.

## International users

If you use the app from outside the country where the developer is based, support-related information may be processed where you use the device or where we respond to email.

## Changes

We may update this policy from time to time. The **Last updated** date at the top will change when we do. Material changes may also be reflected in App Store release notes or in-app notices where appropriate.

## Contact us again

**Email:** rmndevapps@gmail.com

---

**Effective date:** May 3, 2026
