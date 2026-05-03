# Lex -- Privacy Policy

**Effective date:** April 30, 2026
**Last updated:** May 3, 2026

Lex ("the App") is published by **Misfits Studios** ("we", "us", "our").
This Privacy Policy explains what data Lex collects, how it is used,
and the choices you have. It applies to the iOS version of Lex
distributed through the Apple App Store.

If you have questions about this policy you can reach us at
**misfits.support@proton.me**.

---

## 1. The short version

Lex is a notes app. The notes you write, draw, and dictate stay on
your device. We do not run user accounts, we do not collect analytics,
we do not have access to your notes, and we do not sell personal
data.

There are exactly two situations in which any data leaves your
device, and both are covered in detail in Section 3 below:

1. **In-app purchases.** Apple StoreKit and RevenueCat receive the
   information needed to validate your purchase. Anonymous user ID
   only -- no name, email, or note content.
2. **AI Polish (optional, off by default).** If -- and only if -- you
   add an Anthropic API key in Settings *and* explicitly grant
   permission on the consent dialog the first time you tap Polish,
   Lex sends the raw text transcript of that single note to
   Anthropic, PBC for cleanup. You can revoke consent at any time
   in Settings -> AI Polish.

---

## 2. Data Lex handles on your device only

The following information is processed entirely on your iPhone or iPad
and is not transmitted to us or to any third party:

- **Note content** -- text, handwriting, sketches, attached images,
  audio recordings, and any metadata you add to a note.
- **Voice input** -- when you tap the microphone, audio is captured and
  transcribed to text using **Apple's on-device Speech Recognition
  framework**. The audio is processed locally; transcripts are written
  to the note you are editing and stay there.
- **Photos and camera captures** -- images you import or capture for a
  note are stored in Lex's local sandbox. Optical character recognition
  (OCR) is performed on-device using **Google ML Kit Text Recognition
  for iOS**, which runs locally and does not send images to Google.
- **App preferences** -- theme, paper, brush, focus-sound choice, and
  similar settings.

These items live in iOS app storage, are included in your iCloud Device
Backup if you have one enabled (controlled by your iOS settings, not by
Lex), and are removed when you delete Lex from your device.

---

## 3. Data shared with third parties

We use a small number of third-party services that are necessary to
deliver core features. We share only what each service needs.

### 3.1 Apple -- In-App Purchases and StoreKit
When you buy a stationery pack, brush pack, sound pack, template, or a
**Lex Pro** subscription, the transaction is handled by Apple through
StoreKit. We do not see your payment card, full Apple ID, or billing
address. Apple sends us a transaction receipt that confirms the
purchase. Apple's privacy practices for App Store transactions are
covered by the
[Apple Privacy Policy](https://www.apple.com/legal/privacy/).

### 3.2 RevenueCat -- purchase verification
We use **RevenueCat, Inc.** to validate App Store receipts and to
unlock paid content across your devices. RevenueCat receives:

- An anonymous user identifier generated on your device. It is not
  linked to your name, email, or Apple ID.
- The product identifier of the item you purchased.
- The receipt that Apple issued for the transaction.

RevenueCat does not receive your note content, voice recordings, or
photos. RevenueCat's practices are described in the
[RevenueCat Privacy Policy](https://www.revenuecat.com/privacy/).

### 3.3 Files, Photos, and share targets
When you export a note, iOS hands the file to whichever destination
you choose (Files, Photos, Mail, AirDrop, Drive, Dropbox, etc.). Lex
does not see what happens after the share sheet. The privacy policy
of the destination app applies once the file is handed off.

### 3.4 Anthropic -- AI Polish (optional, off by default)

Lex includes an optional feature called **AI Polish**. When enabled,
Lex sends the raw text transcript of a note you have chosen to polish
to **Anthropic, PBC** ("Anthropic") -- the company that operates the
Claude API. Anthropic's polished response is written back into your
note, replacing the unformatted transcript.

AI Polish is **off by default**. Two affirmative steps are required
before any text leaves your device:

1. You add your own Anthropic API key in **Settings -> AI Polish**.
2. The first time Lex is about to send a transcript, Lex shows a
   consent dialog summarising what is sent, who receives it, and the
   purpose. Polish only proceeds if you tap "Allow & polish". A
   decline falls back to Lex's offline rule-based polish -- nothing
   leaves the device.

**What is sent to Anthropic:**

- Only the raw text transcript of the single note you are polishing.

**What is NOT sent to Anthropic:**

- Your audio recordings.
- Your photos, attachments, sketches, or handwriting strokes.
- Your name, email address, Apple ID, IP-derived identifiers, or
  device identifiers.
- Any note other than the one you are polishing.

**Recipient:** Anthropic, PBC, accessed at `api.anthropic.com`,
authenticated with the API key you supplied. Anthropic is the only
third party in the AI Polish data path; Lex does not route the
request through any analytics or proxy service.

**Use:** Anthropic processes the request and returns the polished
text. Per Anthropic's commercial API terms, content submitted through
the API is **not used to train Anthropic's models**. Anthropic's
full privacy practices are described at
[https://www.anthropic.com/legal/privacy](https://www.anthropic.com/legal/privacy)
and their API usage policies at
[https://www.anthropic.com/legal/aup](https://www.anthropic.com/legal/aup).

**Revoking consent:** You can revoke consent at any time by opening
**Settings -> AI Polish** and tapping **"Clear & revoke consent"**.
This removes both your saved API key and the consent flag from
Lex's local storage. The next time you (or another user of the
device) attempts AI Polish, Lex will re-prompt for consent before
any data is sent.

We do **not** use any analytics, advertising, attribution, crash
reporting, or A/B-testing SDK in the iOS build of Lex.

---

## 4. App Tracking Transparency (ATT)

Lex does not track you across other apps and websites. We do not
present an App Tracking Transparency prompt because Lex performs no
tracking activity as Apple defines it.

---

## 5. Children

Lex is rated 4+ in the App Store. We do not knowingly collect personal
information from children. The features that handle content (notes,
voice, camera, photos) operate on-device, so no child-identifying data
is sent to us.

If you are a parent or guardian and want to confirm what is stored on
your child's device, you can delete the Lex app to remove all of its
local data.

---

## 6. Your rights and choices

Because Lex does not maintain user accounts and does not collect
personal data on our servers, there is no profile to access, modify,
or delete on our side. You can:

- **Stop voice transcription** -- revoke microphone or speech
  recognition access in **Settings -> Privacy & Security -> Microphone /
  Speech Recognition**.
- **Stop camera or photo access** -- revoke in **Settings -> Privacy &
  Security -> Camera / Photos**.
- **Restore purchases** -- Settings inside Lex -> "Restore Purchases"
  asks Apple and RevenueCat to re-verify any active entitlements.
- **Delete all local data** -- uninstall Lex from your device. iOS
  removes the app's container, including notes, audio, photos, and
  preferences.

You may also contact RevenueCat directly to request deletion of the
anonymous purchase record they hold for your installation:
[https://www.revenuecat.com/privacy/](https://www.revenuecat.com/privacy/).

---

## 7. International users

Lex is available worldwide through the App Store. The on-device
processing model means your content is governed by the privacy laws of
your jurisdiction and Apple's regional terms.

For users in the European Economic Area, the United Kingdom, and
Switzerland, the lawful bases for the limited processing we perform
are: (a) performance of a contract -- fulfilling your in-app purchase;
and (b) our legitimate interest in operating and securing the app.

For California residents (CCPA / CPRA): we do not sell or share
personal information for cross-context behavioral advertising.

---

## 8. Security

We rely on iOS sandboxing and Apple's Keychain to protect data on the
device. Communications with Apple's StoreKit and with RevenueCat are
encrypted in transit using TLS.

No security model is perfect. If you become aware of a security issue
in Lex, please contact us at **misfits.support@proton.me** and we will
investigate.

---

## 9. Changes to this policy

If we change how Lex handles data, we will update this page and bump
the **Effective date** at the top. Material changes will also be
called out in the app's **What's New** notes for that version.

---

## 10. Contact

**Misfits Studios**
Developer of record: Adam Donovan
Email: misfits.support@proton.me

This policy was prepared specifically for the App Store distribution
of Lex. The Google Play version of Lex is governed by a separate
policy that reflects the corresponding Google services.
