# Digestly Privacy Policy

_Last updated: 31 July 2026_

Digestly is a food, symptom, and exposure diary for families. Privacy is the product: **your data belongs to you, stays with you, and is never seen by us or anyone else.**

## What Digestly collects

Nothing, by us. Digestly has **no servers, no user accounts, no analytics, no tracking, and no third-party SDKs**. We — the developers — receive no data from the app at all.

Digestly makes exactly one kind of network request, and only when you ask it to: scanning a barcode looks that barcode up in a public food database. It sends the barcode and nothing else. Details are in "Barcode scanning, specifically" below.

## Where your data lives

- Everything you log (profiles, meals, symptoms, exposures, notes, photos, and anything you add to an emergency card) is stored **on your device**, inside the app's private storage.
- If you enable **iCloud sync** (optional, on by default when signed in), your data is also stored in **your personal iCloud account** using Apple's CloudKit, encrypted in transit and at rest by Apple. We have no access to it. You can turn sync off at any time in Settings.

### Photos, specifically

Photos you attach to a symptom — a rash, for example — or to a meal are treated like the rest of your log: on your device, and in your own iCloud if sync is on. They are not stored separately or handled specially, and we never see them.

Being straight with you about one detail: iCloud data is encrypted, but unless you have **Advanced Data Protection** switched on in your iPhone's iCloud settings, the encryption keys are held by Apple rather than only by you. That means Apple could in principle be compelled to hand over iCloud contents, including these photos. This is true of everything in iCloud, not just Digestly — but photos of a child's skin deserve a plain warning rather than a footnote. If that matters to you, either turn on Advanced Data Protection, or turn Digestly's iCloud sync off and keep your log on the device only.

### Reading a meal photo, specifically

If you attach a photo to a meal, Digestly can offer to read it and suggest which foods are in it, so there is less for you to type. On iPhones that support it, that reading is done by **Apple Intelligence, on your own device**.

- **The photo does not leave your iPhone.** It is not uploaded, not sent to us, and not sent to Apple's servers. Apple's on-device model has a cloud counterpart that apps can use instead — Private Cloud Compute — and Digestly deliberately does not use it, so there is no version of this feature that sends your picture anywhere.
- **Nothing extra is stored.** The only copy of the photo is the one you attached to the meal yourself. Reading it creates no request, no cache and no identifier of any kind.
- **The suggestions start unticked, and stay suggestions.** Nothing reaches your diary until you tick it and tap Add. What comes back is a guess from a picture, sometimes a wrong one, which is exactly why you confirm it rather than the app filling the meal in for you.
- **It is asked to name only what it can see.** Digestly instructs the model not to guess at ingredients hidden inside a cooked dish, so the app does not put foods into your diary that nobody could see on the plate.
- **If your iPhone can't do it, the button isn't there.** On an older iPhone or an older iOS version, or with Apple Intelligence switched off, the feature is simply absent rather than present and failing. Typing ingredients by hand works exactly as it always has.

### The emergency card, specifically

Digestly can hold an **emergency card** for each person: the allergy action plan your doctor gave you (a PDF or a photo of the paper form), the phone numbers you want to hand in a hurry, your clinician's details, and the expiry dates of adrenaline auto-injectors.

- **Stored exactly as you provide it.** Digestly saves the document as-is. It does not read the file, extract text from it, summarise it, or send it anywhere. Nothing in the app interprets what your doctor wrote, and nothing in the app adds medical instructions of its own.
- **Same place as the rest of your log** — on your device, and in your own iCloud if sync is on. The Advanced Data Protection caveat above applies to these documents too, and applies more sharply: an action plan usually carries a child's name and their diagnoses on the same page. If that concerns you, turn on Advanced Data Protection or turn sync off.
- **Phone numbers are typed by you.** Digestly never reads your address book. It has no access to your Contacts, and asks for none.
- **Expiry reminders are local.** If you switch on a reminder for an auto-injector, it is scheduled by your own iPhone as a local notification. Nothing is sent to us or to anyone else. If you have "Discreet reminders" switched on in Settings, the reminder omits the person's name, the brand and the location, so a lock screen shows only that an auto-injector is expiring.
- **Deleted with everything else.** Removing a person removes their emergency card, and "Erase all data" removes all of it, documents included.

## What leaves your device

Only what **you** choose to share:

- **Doctor reports (PDF)** and **CSV exports** are generated on your device and leave it only through the iOS share sheet, to a destination you pick.
- iCloud sync, if enabled, moves data only between your own devices via your own iCloud account.
- **A barcode**, and only when you scan one — see below.
- **A symptom you log on an Apple Watch**, which travels to your own iPhone and no further — see below.

### Barcode scanning, specifically

If you scan the barcode on a packet, Digestly asks the public [Open Food Facts](https://world.openfoodfacts.org) database what that product is, so it can offer you the ingredient list instead of making you type it.

This is the **only** request Digestly ever makes to anyone. Precisely what is sent:

- **The barcode digits, and nothing else.** No profile, no name, no age, nothing you have logged, no device or installation identifier, no advertising identifier, no location, and no timestamp beyond the unavoidable fact that the request happens when you make it.
- **The same request for everybody.** Digestly asks for the product's details in all five of its languages every time and picks the right one on your device. It could have asked only for yours, which would have been a smaller request — and would have told Open Food Facts which language you read. It does not.
- **A version line identifying the app** (`Digestly/1.0`) and the developer's own contact address, which Open Food Facts requires of every app that uses it. This is our contact detail, not yours.
- **No cookies.** The connection is made fresh each time and stores nothing, so nobody can set an identifier that survives from one scan to the next.

Other things worth stating plainly:

- **Nothing about you is sent, so nothing about you can be stored at the other end.** Open Food Facts can see that somebody looked up a barcode, from an IP address, as they can for any website. They cannot see who, and they cannot connect two scans to the same person through anything Digestly sends.
- **Results are cached on your device** so scanning the same product again needs no request at all.
- **No photograph is taken or kept.** The camera reads the barcode live and the image is never saved.
- **Scanning is entirely optional and never required.** You can type ingredients by hand exactly as before, and everything works with no network at all.
- **The camera is only used while the scanner is open**, and only if you allow it. Decline, and Digestly offers a field to type the barcode digits instead.

We receive nothing from any of this. We have no server involved in it and no way to see that it happened.

### The Apple Watch app, specifically

If you use the Apple Watch app, you can log a symptom from your wrist without taking your phone out. What moves does so **directly between your own two devices**, over the link your iPhone and your watch already have with each other. No server of ours is involved, and no third party's either — this is not a network request and nothing about it reaches the internet.

It also works **whether or not you use iCloud sync**, and that is deliberate: a symptom logged on the wrist must not go missing simply because you have chosen to keep your diary on one device only.

- **Watch to phone: one symptom.** Which symptom you picked, how severe you said it was, when, and which person it is about. Nothing else — no note, no photo, and nothing else you have ever logged.
- **Phone to watch: only what a list needs.** The symptom names, so the watch can show them to you in your own language; a marker saying which of them involve breathing, so the emergency-care notice can appear on the watch itself instead of waiting for a phone in another room; and the names of the people you log for, so the watch can show whose entry it is. **Your diary, your patterns, your insights and your reports are never sent to the watch** — a watch is the screen in a household most easily read over your shoulder, so it is given the least.
- **The watch keeps no diary of its own.** It holds that list and the entries still waiting to be handed over, and nothing more. Your log lives on your iPhone. Removing the watch app removes the watch's copy of the list with it.

## Apple Health (optional)

If you turn on **Connect Apple Health** in Settings (it is off by default), Digestly reads sleep and activity information — sleep analysis, steps, active energy, and exercise minutes — from Apple Health, as recorded by your iPhone, Apple Watch, Oura ring, or other apps that write to Apple Health.

- **Read-only.** Digestly never adds, changes, or deletes anything in Apple Health.
- **On-device only.** Health data read from Apple Health is processed and stored only on your device. It is **never synced to iCloud**, never transmitted anywhere, never included in exported reports, and never used for advertising.
- **Only for you.** It is used solely to show your sleep and activity alongside your own symptom log and to look for patterns you can discuss with your doctor. Patterns are observations, not medical conclusions.
- **Reversible.** Turn the switch off at any time and Digestly deletes its stored copy of the Health data. You can also revoke Digestly's read access in the Health app under Sharing → Apps. "Erase all data" removes it as well.

## Health information

Digestly is a diary and pattern finder, not a medical device. It never provides medical conclusions. Information you log is health-related, so treat exported files with the same care you would any medical document.

## Deleting your data

Settings → **Erase all data** permanently deletes everything from the device **and** from your iCloud (the app's CloudKit zone). Deleting the app removes all on-device data.

## Children

Digestly is designed for parents logging on behalf of their children. Children's data is handled identically to all other data: on-device and in the family's own iCloud only. There are no accounts and no data collection. Apple Health data is only ever read on the device it belongs to.

## Changes

If this policy changes, the updated version will be available at this address and the change will be noted in the App Store release notes.

## Contact

Questions: os@eurolink.mt
