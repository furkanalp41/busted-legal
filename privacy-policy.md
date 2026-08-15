# BUSTED! — Privacy Policy

_Effective date: August 1, 2026_

## 1. Introduction

Welcome to BUSTED! — a party game where the only thing we want to catch is who wrote what, not your personal data. This Privacy Policy explains how Furkan Alp Günay (zenSoftware) ("we," "us," or "our") collects, uses, and protects information when you use the BUSTED! mobile app (the "App") on iOS and Android. It applies to everyone who hosts or joins a room. By using the App, you agree to the practices described in this Policy. If you don't agree, please don't use the App.

## 2. Information We Collect

BUSTED! has no accounts, so there's no persistent "profile" of you sitting on a server. Here's what actually gets created or transmitted while you play:

**Information you choose to provide**

- **Nickname and color.** When you join or host a room, you pick a free-text display nickname (up to 14 characters) and a color swatch. These are visible only to the other players currently in your room, for as long as that room exists.
- **Gameplay content.** The short free-text answers you write in response to prompts, and the votes you cast, are sent to our game server so it can run the round, show answers anonymously to your room, and tally votes.

**Information generated to run the game**

- **Room and reconnect identifiers.** When you join a room, our server issues a randomly generated `playerId` and a reconnect `token`. These are stored locally on your device and let you rejoin the same room if your connection drops, within a short (30-second) grace window. They are not linked to your name, email, or any other identifying information.
- **Room state.** While a room is active, the server temporarily holds the list of players, nicknames, colors, answers, votes, and scores in server memory so the game can run. See Section 5 for how long this lasts.

**Technical connection data**

- **IP address.** BUSTED! runs on a live, real-time connection (Socket.IO/WebSocket), the same way any online multiplayer game works. As a normal and unavoidable part of maintaining that connection, your device's IP address is visible to our game server. We do not log, store, profile, or otherwise use your IP address beyond what's needed to keep your live connection to the room working.

**Information stored only on your device**

The following stays on your device (in local app storage) and is never sent to us except as ordinary traffic of an active room you've chosen to join or host:

- Your last-used nickname and color, saved for convenience next time.
- Whether you've completed onboarding.
- Your sound, haptics, dark mode, and language preferences.
- A short local list of nicknames/colors of people you've recently played with ("recent suspects").
- Your active room's reconnect token, described above.

We do not maintain accounts, and we do not build persistent, cross-session profiles of you on our servers.

## 3. Information We Do Not Collect

We built BUSTED! to need as little from you as possible. Beyond what Section 4 describes for advertising, we do **not** collect:

- Your real name, email address, or phone number — there's no registration, login, or account of any kind.
- Data from third-party analytics or tracking SDKs — we don't use any, beyond the advertising SDK described in Section 4.
- Your precise or approximate location.
- Your contacts or address book.
- Payment or billing information — the App has no purchases or subscriptions.
- Push notification tokens — the App does not send push notifications.

## 4. Advertising

BUSTED! shows ads (via Google AdMob) between rounds and at the end of a game to keep the App free. This means:

- **Google AdMob** operates as an independent third party and may collect information such as your advertising identifier (IDFA on iOS, or the Android equivalent), general device information, and ad interaction data, to select and measure ads. Google's own privacy policy governs its handling of that data: [policies.google.com/privacy](https://policies.google.com/privacy).
- **App Tracking Transparency (iOS).** The first time the App shows its tracking prompt, you can allow or deny tracking. If you deny it (or haven't been asked yet), you'll still see ads, but they'll be less personalized rather than tied to your device across other apps.
- We request only **non-personalized ads** at the SDK level regardless of your ATT choice, and do not otherwise combine ad data with your in-game nickname, room activity, or any other information described in Section 2.
- Ads are not shown to determine or influence gameplay outcomes, scoring, or matchmaking — they appear only at natural breaks between rounds and at the end of a game.

## 5. How We Use Information, and How Long We Keep It

We use the information described in Section 2 for one purpose: **running your live game session.** Nicknames and colors are shown to your room so everyone knows who's who; answers and votes power the round; scores populate the scoreboard. We do not use gameplay information for advertising, profiling, or any purpose unrelated to that session.

Retention is short by design:

- **Server-side room data** (players, nicknames, answers, votes, scores) lives only in server memory for as long as the room is active. Rooms left idle are automatically deleted after about one hour. There is no database — once a room closes or is garbage-collected, its contents are gone. We do not keep round-by-round history, past games, or an archive of what anyone wrote.
- **On-device preferences** (nickname/color defaults, onboarding flag, settings, recent suspects, reconnect token) stay on your device until you clear the App's storage or delete the App.
- **One limited exception:** if a player submits an in-round report (Section 6), the reported content and relevant context are written to our server logs so we can review it. We keep that log entry only as long as reasonably needed to review the report and address any violation — it is not a public or persistent report queue, and it is not used for any other purpose.

## 6. User-Generated Content & Moderation

The answers players write are meant to be silly and revealing in the moment, not permanent records. To keep rooms playable and reasonably safe, we use a few lightweight safeguards:

- **Automated filtering.** Before an answer is shown to the room, it passes through a server-side filter that blocks a list of especially offensive terms.
- **In-round reporting.** Any player can report an answer while it's being revealed. Reporting sends a note to our server logs for us to review, as described in Section 5 — it is not a public or persistent report queue visible to other players.
- **Host controls.** The player hosting a room can remove ("kick") a disruptive player from that room at any time.

We reserve the right to remove content from an active session and to suspend or restrict access to the App for anyone who abuses it. Because we don't persistently store gameplay content, there is no ongoing archive of past answers for us to moderate after the fact — moderation happens live, during the session in which the content appears.

## 7. Children's Privacy

BUSTED! is not directed at children under 13, and we do not knowingly collect personal information from children under 13.

The App also includes one optional question pack ("SPICY") with flirty, suggestive 18+ content. SPICY is off by default and can only be turned on by a room's host. Because any room you join could have SPICY enabled, the App requires everyone to confirm — through an in-app age and terms gate, before playing at all — that they are 17 or older, or meet their local age of digital consent for such content if higher.

Because BUSTED! has no accounts and does not persistently store gameplay content beyond the life of a room, there is generally no ongoing account or profile to delete if a child has used the App. If you're a parent or guardian and believe your child has provided information through the App, please contact us at furkanalpgunay41@gmail.com so we can look into it and take appropriate action. You can also immediately remove any locally stored data by deleting the App from the device.

## 8. Data Sharing

We do not sell your information. Gameplay data (Section 2) goes only to our own game server, solely to run your live session. The one exception is advertising: as described in Section 4, Google AdMob independently collects limited device/ad-interaction data to serve and measure ads — we do not hand your nickname, room activity, or any other gameplay data to AdMob or any other advertiser.

We may disclose information if required by law, or if we believe in good faith that disclosure is necessary to comply with a legal obligation, protect the safety of users, or investigate misuse of the App.

## 9. Security

We take reasonable technical and organizational measures to protect information while it's in transit to and from our game server. That said, no method of electronic transmission or storage is 100% secure, and we cannot guarantee absolute security. Given how little we retain, and for how briefly, the practical exposure is intentionally limited.

## 10. Your Choices & Rights

Because BUSTED! has no accounts, most of the usual "request my data" or "delete my account" mechanics don't apply the way they would on other apps — there simply isn't a persistent server-side profile tied to you to request. Specifically:

- You can leave any room at any time, ending your participation in that session.
- You can clear the App's local storage or uninstall the App to remove everything stored on your device, including your saved nickname, color, preferences, and any reconnect token.
- If you have a question about what limited server-side data (such as a report log entry) might exist, or any other request related to your information, contact us at furkanalpgunay41@gmail.com.

Depending on where you live, you may have additional rights under local privacy law. Because we do not maintain accounts or persistent profiles, many such rights are already satisfied by the fact that nothing persists past your session — but you're always welcome to reach out with questions.

## 11. International Users

BUSTED! may be played by people around the world, and gameplay data may be transmitted to and processed on servers located outside your home country as part of running your live session. This Policy, and our handling of information, is governed by the laws of the Republic of Türkiye, without regard to conflict-of-law principles.

## 12. Changes to This Policy

We may update this Privacy Policy from time to time, for example to reflect changes to the App or applicable law. If we make material changes, we will update the effective date at the top of this document. Continuing to use the App after changes take effect means you accept the updated Policy.

## 13. Contact Us

Questions, concerns, or a parental/takedown request? Reach us at furkanalpgunay41@gmail.com.
