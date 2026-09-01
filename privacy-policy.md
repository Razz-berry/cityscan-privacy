---
title: Privacy Policy
---
**Last updated: September 1, 2026**

This Privacy Policy describes how CityScan ("CityScan," "we," "us," or "our") collects, uses, and shares information when you use our mobile application (the "App").

By using the App, you agree to the collection and use of information in accordance with this policy.

---

## Information We Collect

### Location Information

The App uses your device's location to identify buildings near you. When you photograph a building, use Peek, or view nearby landmarks, the App reads your GPS coordinates and, when photographing, your compass heading.

Your coordinates are transmitted to the third-party services described below in order to identify the building in front of you, retrieve street-level imagery, and look up property records. They are also included when you send feedback or submit a building, so that we can locate what you are describing.

We do not use your location for advertising, for tracking you across apps or websites, or to build a profile of your movements.

Location is only accessed while the App is in use. The App does not request or use background location.

### Photographs

**Photos you take to identify a building.** When you photograph a building, that image is transmitted to Google's Gemini AI service, which identifies the building. We do not store these photos on our servers.

**Photos saved with your collection.** When a scan results in a building being added to your collection, the photo is copied into the App's private storage on your device and kept there permanently as part of that collection entry, so it can be shown in your collection and on share cards. It stays on your device until you remove that building from your collection or delete the App. It is not uploaded to us.

**Photos you submit to us.** If you use the "Add It!" or "Help fill this in" features, the photo you submit is uploaded to our servers along with your coordinates, the address, and any notes you write, so that we can review it and potentially add the building to the App's database. These photos are stored privately: they are not published, not linked from anywhere, and cannot be retrieved by other users or by the public. Only we can view them, in order to review your submission.

**Access to your photo library.** The App does not read, browse, or import from your existing photo library. It requests add-only permission to your photo library for a single purpose: when you tap "Save to Photos" on a building's share card, the App writes that one image to your library. It cannot see the photos already there.

### Information You Voluntarily Submit

If you use the App's feedback, "Add It!", or "Help fill this in" features, we collect what you provide — the text you write, any photograph, the address, and your device's coordinates at the time of submission. Your installation ID, described below, is sent along with it.

We do not collect your device model, operating system version, or App version with these submissions.

### Information Stored On Your Device

The App stores the following locally on your device: your collection of found buildings and their photos, your favourites, your achievements and discovery streak, your scan and Peek usage counts, your display preferences, cached building information and imagery, and the installation ID described in the next section.

Apart from the installation ID, which is sent with submissions as described below, this information stays on your device. We cannot read it, and it is not transmitted to us except where you explicitly submit it.

### Installation ID

The first time you open the App, it generates an **installation ID** — a random string of characters, in the standard UUID format — and saves it on your device.

**What it is.** It is randomly generated and nothing more. It is not your device's serial number, advertising identifier, or any other identifier issued by your phone or by Apple, and it is not derived or calculated from anything about your device. It contains no personal information: not your name, not your email address, not your location, and nothing that describes you or your phone. On its own it identifies nobody — it is a number that means nothing except "these submissions arrived from the same copy of the App."

**What we use it for.** Only two things:

- **Rate limiting.** It is sent with submissions so we can cap how many any one installation can send in an hour. This is what stops a single source from flooding our review queue, and it lets us apply that limit without collecting anything about who you are.
- **Answering you about something you sent.** If you report a bug or send feedback, the ID lets us connect your message to the submission it refers to, and lets us find your submissions again if you ask us to.

**What we do not use it for.** We do not use it to track you across other apps or websites, to build a profile of you, to target advertising, or to link your activity to any identity. It is not shared with advertisers or data brokers, and it is not part of the shared building research described below.

**How to clear it.** The ID lives only in the App's own storage on your device. Deleting the App deletes it. If you reinstall, the App generates a brand-new, unrelated ID, and we have no way to connect the new one to the old one. Two installations on the same phone receive different IDs.

### Information We Do Not Collect

The App does not require an account. We do not collect your name, email address, or phone number unless you choose to include it in a message you send us.

**The App does not use an advertising identifier, and does not collect any identifier issued by your device or its operating system.** The only identifier it holds is the randomly generated installation ID described above.

We do not use analytics, crash-reporting, or advertising software, and we do not track you across other apps or websites.

---

## Content Generated From Your Activity Is Shared With Other Users

To avoid regenerating the same research repeatedly, and to make the App better for everyone, some information produced while you use the App is saved to our shared database and served to other users:

- **Building histories.** When the App generates a deep dive about a building — its history, its architect, notable residents and connections — that result is stored in a shared cache keyed to the building's address, and other users who look up the same building are served the same text.
- **People associated with a building.** Names of notable people identified at an address are added to a shared list for that address and shown to other users viewing it.
- **Buildings matched from public records.** When the App identifies a building by falling back to public city property records, the matched building's address, borough, coordinates, and year built are recorded so we can improve identification coverage.

This shared content describes **buildings, not users**. It is keyed to a building's address and contains no identifier for you, no coordinates of yours, and nothing that links a record to you or to your other activity. Your collection, your photos, and your usage history are never shared this way.

Because this content is keyed to buildings rather than to people, we cannot isolate or delete "your" contributions to it on request.

---

## How We Use Information

We use the information described above to:

- Identify buildings from photographs and location data
- Retrieve and display historical and architectural information about buildings
- Keep your collection, achievements, and preferences on your device
- Serve previously generated building research to other users, as described above
- Review submitted buildings and corrections in order to improve the App's database
- Limit how many submissions a single installation can send in an hour, to prevent abuse
- Diagnose problems you report and improve the App
- Comply with applicable law

---

## Third-Party Services

The App relies on the following services to function. Information sent to them is subject to their own privacy policies.

**Google.** We transmit your photographs and coordinates to Google in order to identify buildings and display imagery, specifically:

- *Gemini AI* — receives your building photo and nearby candidate addresses to identify the building, receives Street View imagery for verification, and generates building, architect, and person write-ups. Some of these requests use Gemini's Google Search grounding, which means Google performs web searches based on the building, architect, or person being researched.
- *Street View (Static and Embed)* — receives building coordinates to return street-level imagery.
- *Maps SDK* — renders the map in your collection.

Google's Privacy Policy: https://policies.google.com/privacy

**Supabase.** Hosts our database and file storage: submitted photos, notes, and coordinates; the shared building-research cache described above; and a global counter used to stay within our imagery quota. Supabase's Privacy Policy: https://supabase.com/privacy

**Wikipedia (Wikimedia Foundation).** The App requests article summaries and portrait images for architects and notable residents. These requests contain the name being looked up and no information about you. Wikimedia's Privacy Policy: https://foundation.wikimedia.org/wiki/Policy:Privacy_policy

**NYC Open Data.** The App queries New York City's public property dataset using coordinates or an address, to find candidate buildings. These queries contain no personal information.

Requests to these services necessarily reveal your device's IP address to them, as any internet request does.

---

## Data Retention

- Photos sent for building identification are processed and are not retained by us.
- Photos, notes, and coordinates you submit through "Add It!", "Help fill this in", or feedback are retained indefinitely so we can review them and improve the App. The installation ID attached to a submission is retained for as long as that submission is.
- Shared building research is retained indefinitely, as it describes buildings rather than people.
- Information stored on your device remains until you delete it in the App or delete the App itself.

---

## Your Choices and Rights

**Permissions.** You may revoke camera, location, or photo-library access at any time in your device settings. The App's building identification cannot function without camera and location access; the "Save to Photos" feature is the only thing affected by photo-library access.

**Your collection.** You can remove individual buildings from your collection in the App, which deletes the saved photo for that building from your device. Deleting the App removes everything it has stored locally.

**Submitted content.** If you submitted a photo, note, or feedback message and want it removed, contact us at the address below and we will delete it. Because submissions now carry your installation ID, we can identify the submissions sent from a given installation on request, and can retrieve or delete them as a group. Telling us roughly when you sent it and what building or subject it concerned still helps us find a single item quickly.

Note that this works only for submissions sent from an installation you still have. If you have since deleted and reinstalled the App, its ID is gone and cannot be recovered, so we can no longer connect you to those earlier submissions by ID — describe them instead and we will find them that way.

Depending on where you live, you may have additional rights regarding your personal information, including rights of access, correction, and deletion. Contact us at the address below to exercise them. Note that for most of what the App does we hold no information that identifies you, so in many cases there will be nothing to retrieve.

---

## Children's Privacy

The App is not directed to children under 13, and we do not knowingly collect personal information from children under 13. If you believe a child has provided us with personal information, contact us and we will delete it.

---

## Data Security

We take reasonable measures to protect the information we collect, including storing submitted photographs in private storage that is not accessible to other users or to the public. However, no method of internet transmission or electronic storage is completely secure, and we cannot guarantee absolute security.

---

## Changes to This Policy

We may update this Privacy Policy from time to time. When we do, we will revise the "Last updated" date at the top of this page. We encourage you to review it periodically. Your continued use of the App after changes constitutes acceptance of the updated policy.

---

## Contact Us

If you have questions about this Privacy Policy or how we handle your information, contact us at:

**cityscanhq@gmail.com**
