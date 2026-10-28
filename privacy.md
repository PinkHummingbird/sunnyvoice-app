# SunnyVoice — Privacy Policy

[SunnyVoice home](./) · [Terms of Use](terms) · [Support](support)

_Last updated: 28 October 2026_

**Contact:** support email coming soon

SunnyVoice is a voice journal for iPhone. You talk, it writes down what you said and reflects on it. What you say in a journal is about as private as anything gets, so SunnyVoice is built so that **we never receive it and cannot read it.**

## Summary

- **No account. No sign-up.** There is no SunnyVoice account, and there never will be.
- **No servers of ours.** SunnyVoice has no backend. We hold no copy of anything you say, write or record.
- **Everything is worked out on your iPhone.** Transcription, the safety check and the reflections all run on the device, and keep working in airplane mode once the speech model is on your iPhone.
- **Your journal syncs only to your own private iCloud**, through Apple. Only someone signed in with your Apple ID can read it — not us.
- **Your words are encrypted on your iPhone before they go to iCloud.** See [What goes to your iCloud](#what-goes-to-your-icloud).
- **No tracking, no ads, no analytics, no crash reporters**, and no third-party service of any kind. The app talks only to Apple.
- **App Privacy label: Data Not Collected.** Data in your own private iCloud is not collected by us: we have no way to read it.

## What happens on your iPhone

- **Recording.** SunnyVoice uses the microphone only while you are recording an entry. iOS asks your permission first, and shows the recording indicator whenever the microphone is on.
- **Transcription.** Your recording is turned into text on your iPhone by Apple's on-device speech recognition. The first time, iOS may download Apple's speech model for your language from Apple; that download carries nothing you said. For now SunnyVoice transcribes English (US) only.
- **Reflections.** Each reflection is made on your iPhone, either by Apple's on-device language model (on iPhones that support Apple Intelligence) or by SunnyVoice's own rule-based engine. Neither sends your words anywhere. The instructions the on-device model receives are published in the app under Settings › About › How SunnyVoice works.
- **How you spoke.** Pace and pauses are measured from the recording on your iPhone.
- **The safety check.** Before any reflection is shown, SunnyVoice checks your words on your iPhone for phrases about being in danger or in deep distress, and shows a support card instead, with helplines for your region where SunnyVoice has them (currently the US, Canada, the UK, Ireland, Australia and New Zealand) and otherwise your local emergency number. Nothing about this check is reported to anyone.
- **What helps you.** If you rate the small steps (Helped · Not really · Skip), SunnyVoice counts on your iPhone which kinds of steps seemed to help you. Those ratings are part of your journal and sync like the rest of it.

The journal is stored in the app's database on your iPhone. If your iPhone backs itself up to iCloud or to a computer, iOS includes the app's journal database (entries, transcripts, reflections) in that backup, as it does for every app. Recordings kept only on this iPhone (with "Sync recordings" off, or without iCloud sync) are left out of those backups. That backup is between you and Apple; we never receive it.

## What goes to your iCloud

SunnyVoice keeps your journal in sync across your devices through Apple's iCloud. It is on by default when you are signed in to iCloud, and you can turn it off in Settings › iCloud.

- **Where it goes:** the **private** database of your own iCloud account, in SunnyVoice's container, through Apple's CloudKit. Only someone signed in with your Apple ID can read it. We, the developer, have no access to your private iCloud data. SunnyVoice never uses iCloud's public or shared databases.
- **Your words are encrypted on your iPhone before upload:** transcripts, your edits, titles, themes, tags and reflections.
- **Stored without that extra encryption:** moods (including one you pick yourself), scores, dates, durations, favorites, safety flags, which guided prompt an entry answered, whether and when you completed a small step, your ratings of small steps, and whether an entry is in the trash or waiting to be reflected on again. They still have iCloud's standard protection in transit and at rest.
- **Recordings** sync to your iCloud unless you turn off "Sync recordings". They have iCloud's standard protection, not the extra encryption your words get. About 240 KB per minute of recording counts against your iCloud storage. You can also choose to delete recordings after transcription, in Settings › Recording.
- **Some settings and small markers** sync through iCloud's key-value storage, so your devices behave the same: for example reminder times, reflection style, recording retention, "Sync recordings", haptics, "How you spoke" and "Color entries by mood"; whether the note shown with your first reflection was seen; how many times and when the Pro offer appeared by itself; and up to which entry the small-step check-in was handled. None of them contains your words.
- **Advanced Data Protection:** if you turn it on for your Apple ID, your words (the encrypted fields above) are end-to-end encrypted, and only your trusted devices hold the keys. The fields stored without that extra encryption keep iCloud's standard protection even with Advanced Data Protection on. Without it, Apple holds keys to your encrypted words too, so that it can help you recover your data. See [Apple's iCloud data security overview](https://support.apple.com/en-us/102651).
- **iCloud Drive copies (Pro, off until you turn them on):** "Mirror to iCloud Drive" writes your entries as plain Markdown files into a SunnyVoice folder in your iCloud Drive, so you can open them in Files. They are ordinary files: the extra encryption and the app lock do not apply to them. Turning the mirror off, or Pro ending, stops the files updating but does not remove them; delete them in Files, or use "Delete all iCloud data…". While the mirror is on, deleting an entry removes its file.
- **Turning sync off** keeps the copy already in your iCloud. **"Delete all iCloud data…"** in Settings removes everything SunnyVoice keeps in your iCloud — entries, recordings, iCloud Drive copies and synced settings. One small marker (a random ID and a date, no journal content) stays in iCloud's key-value storage, so your other devices know to pause and ask you instead of uploading again.

Apple's handling of iCloud data is described in [Apple's Privacy Policy](https://www.apple.com/legal/privacy/).

## What appears outside the app

Widgets, the Lock Screen, notifications and Siri can be seen by anyone who can see your iPhone, so they never show your words — no transcripts, titles, reflections or small steps. iPhone Search is the one exception, and only if you turn it on: it shows an entry's title and date (see below).

- **Widgets** show your streak and which of the last 7 days had an entry. They show moods only if you turn on "Show moods on widgets".
- **While you record,** the Lock Screen and Dynamic Island show a timer, a level meter and a Stop button — never what you are saying.
- **Reminders, the next-day check-in on small steps and the weekly summary** are off until you turn them on. iOS asks your permission first. Your iPhone schedules them itself; their text is the same every time, never your words.
- **Siri** can tell you how many entries you made this week and your streak, only after you unlock your iPhone.
- **"Show entries in iPhone Search"** is off unless you turn it on. Then the titles and dates of entries can appear in iPhone Search, on your iPhone only. An entry that got a support card is never added.

## App lock

"Lock with Face ID" and "Hide in app switcher" are free and off until you turn them on. iOS does the checking with Face ID, Touch ID or your passcode; SunnyVoice only learns yes or no, and never sees your face, your fingerprint or your passcode.

While app lock is on, a strongly blurred, warm-tinted cover hides SunnyVoice in the app switcher (solid if Reduce Transparency is on); widgets show only your streak and the Record button; your entries are taken out of iPhone Search; Siri says only "Open SunnyVoice to see your week."; and the Live Activity shows the timer and a flat level meter. When the lock engages it closes an entry you have open. App lock does not cover the iCloud Drive copies in Files.

## Purchases

SunnyVoice Pro is bought through the App Store. **Apple handles the payment; we never see your payment details**, your name or your Apple ID. Your iPhone checks your purchase itself from Apple's signed record of it; there is no SunnyVoice server to check it with.

## Diagnostics

SunnyVoice contains no crash reporter and sends no usage data. If you have turned on **Share With App Developers** in your iPhone's Settings › Privacy & Security › Analytics & Improvements, Apple may share crash logs and usage statistics with us, under Apple's terms. They contain no journal content. You can turn that off at any time.

## Export

With Pro, you can export your whole journal as Markdown, JSON or PDF through the share sheet. Without Pro, you can share any single entry as text from its page. You choose where the file goes. Once it leaves the app it is yours to look after, and it is governed by wherever you send it.

## Deleting your data

- **An entry:** when you delete one, you can undo it for 30 seconds. After that it disappears from the app on all your devices, and it is permanently removed the next time SunnyVoice runs its clean-up (after a change arrives from another of your devices, or when sync is switched on or off).
- **All entries:** Settings › Privacy & data › "Delete all entries…" removes every entry and recording from this iPhone and, with iCloud sync on, from your other devices too.
- **Everything in iCloud:** Settings › iCloud › "Delete all iCloud data…". This iPhone's entries stay unless you delete them too.
- **Everything on the iPhone:** deleting the app deletes everything it stored on the device. If you want your iCloud copy gone as well, use "Delete all iCloud data…" first, or later go to your iPhone's Settings › your name › iCloud › Manage Storage.

Because we hold no data about you, there is nothing for us to access, correct or delete on your behalf. Everything is under your control in the app, and in your Apple ID settings.

## What we do not do

- We do not collect analytics, usage data or advertising identifiers.
- We do not use advertising or third-party tracking.
- We do not sell or share your data with anyone — we do not have it.
- We do not run any server, and we do not require or offer an account. iCloud is your own Apple account, not ours.
- We do not include any third-party analytics, advertising or crash-reporting software.

## This website

This website is hosted by GitHub Pages. To deliver the pages, GitHub's servers see what any web server sees — your IP address and browser details — under [GitHub's privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). This website sets no cookies, has no forms and counts no visits.

## Not a medical or crisis service

SunnyVoice offers reflections and small suggestions to help you think things through. They're created automatically on your iPhone and haven't been written or reviewed by a mental-health professional, so treat them as ideas to consider, not advice. SunnyVoice isn't therapy, a diagnosis or a crisis service. If you're struggling, please reach out to someone you trust or a professional — and if you're in danger, contact your local emergency number.

## Children

SunnyVoice is not directed at children. It does not knowingly collect data from anyone, because it does not collect data at all.

## Changes

If this policy changes, the date at the top changes with it and the revised policy is posted at this address. If SunnyVoice ever starts handling data differently, this page will say so before the app does.

## Contact

Questions about privacy: support email coming soon
