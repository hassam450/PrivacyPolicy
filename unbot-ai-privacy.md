# Unbot AI Privacy Policy

**Effective date:** October 22, 2026

This policy explains what information the Unbot AI app ("Unbot", "we", "us") handles, why, and the choices you have. Unbot rewrites your text so it reads more naturally and gives it a Human Score. We built it to collect as little as possible: there is no sign-up, no name, no email address and no analytics.

Questions or requests: **hassam.ashraf450@gmail.com**

## 1. The short version

- You don't create an account. The app gets a random anonymous ID so it can count your free words.
- The text you rewrite is sent to our server and to Google's Gemini AI to produce the rewrite. **We don't store your text on our servers.**
- Your history of drafts and rewrites stays **on your phone**, for 30 days, and you can delete it at any time.
- We don't sell your information, and we don't use analytics or crash-reporting tools.

## 2. Information we handle

### Anonymous ID
When you first open Unbot, the app signs in anonymously with Google Firebase Authentication. This creates a random user ID that is not linked to your name, email or phone number. We use it to keep your word count and your subscription status working.

### Text you rewrite
When you tap **Humanize**, the draft you entered, along with the tone and strength you chose, is sent over an encrypted connection to our server (Google Cloud Functions for Firebase). The server sends the text to Google's Gemini API to produce the rewrite, scores the result, and returns both to your phone.

- Our server does **not** save your draft or the rewrite. It records only word counts and timestamps (see "Usage records" below).
- Google processes the text to generate the rewrite under the [Gemini API Additional Terms of Service](https://ai.google.dev/gemini-api/terms) and [Google's Privacy Policy](https://policies.google.com/privacy).
- Please don't paste sensitive personal information (such as health, financial or government ID details) into the app.

### Usage records
To enforce the free allowance, our database (Google Cloud Firestore) keeps a record for your anonymous ID containing:

- how many words you have used in the current 24-hour window, any bonus words, and when the window started;
- when you last used the app;
- your plan (free or Pro) and when it was last checked;
- a short record for each rewrite or bonus-word claim: its word count, whether it was charged, cancelled or refunded, and when. These records are deleted automatically after 7 days.

None of these records contains your text.

### Purchases
Subscriptions and one-time purchases are handled by Google Play or the Apple App Store, and managed through RevenueCat. We share your anonymous ID with RevenueCat so your purchase can be linked to the app. **We never see or store your payment card details**; the store handles payment. Our server asks RevenueCat whether your anonymous ID has an active Pro plan.

### Information stored on your device
The following stays on your phone and is never uploaded:

- **History:** each rewrite with its draft, tone, strength, scores, word counts and date. Entries are deleted automatically after 30 days.
- **Preferences:** default tone and strength, theme, and whether you have finished onboarding.

When you export or share a rewrite, the app creates a temporary file and hands it to your phone's share sheet. Where it goes next is up to you.

### Support emails
If you email us, we receive your email address and whatever you include. The app pre-fills the email with your app version, platform and OS version to help us troubleshoot. We use this only to reply to you.

### Advertising
The free plan may show ads from Google AdMob. Ads are never shown to Pro users. Unbot asks AdMob for **non-personalized ads only**, so ads are not based on your interests or past behavior. AdMob may still collect device information, such as your advertising ID, IP address and approximate location, to serve ads, limit how often they appear and prevent fraud. See [how Google uses information from apps that use its services](https://policies.google.com/technologies/partner-sites). You can reset or delete your advertising ID in your phone's settings.

## 3. How we use information

We use the information above only to:

- rewrite and score your text;
- apply the free word allowance, bonus words and Pro features;
- check and restore purchases;
- prevent abuse of the service; and
- answer your support requests.

We do not sell your information or use it for profiling. We do not use your text to train AI models.

## 4. Service providers

| Provider | What it does for Unbot | Data involved |
|---|---|---|
| Google Firebase (Authentication, Cloud Functions, Firestore) | Anonymous sign-in, our server, usage records | Anonymous ID, usage records, text in transit |
| Google Gemini API | Generates the rewrite | Your draft (processed, not stored by us) |
| RevenueCat | Manages subscriptions | Anonymous ID, purchase status |
| Google Play / Apple App Store | Payments | Handled by the store under its own policy |
| Google AdMob (free plan, when ads are shown) | Non-personalized ads | Device and advertising identifiers |

## 5. How long we keep information

- **Your text:** not kept on our servers. Kept on your device for up to 30 days, or until you delete it.
- **Per-rewrite and bonus-claim records:** 7 days.
- **Usage record for your anonymous ID:** kept while you use the app. You can ask us to delete it (see below).
- **Support emails:** kept as long as needed to resolve your request.

## 6. Your choices and rights

- **Delete history:** open History to delete one rewrite, select several, or go to **Settings → Your data → Clear history** to delete everything.
- **Delete everything else:** uninstalling the app removes all on-device data. To delete the usage record linked to your anonymous ID, email us at hassam.ashraf450@gmail.com. Your anonymous ID is shown nowhere in the app, so tell us roughly when you last used Unbot and on what device, and we will find and delete it. We may not be able to identify a record without enough detail.
- **Purchases:** manage or cancel subscriptions in Google Play or the App Store.
- Depending on where you live (for example, in the EU, UK or California), you may have rights to access, correct, delete or object to the processing of your personal information. Email us to exercise them. You can also complain to your local data protection authority.

## 7. Security

All data travels over encrypted connections (HTTPS). Our database can be written only by our server, not by the app. No method of transmission or storage is completely secure, but we work to protect what we handle.

## 8. Children

Unbot is not directed to children under 13, and we do not knowingly collect personal information from them. If you believe a child has used Unbot, contact us and we will delete any related records.

## 9. International transfers

Our service providers may process information in the United States and other countries. Where required, they use appropriate safeguards for these transfers.

## 10. Changes to this policy

We may update this policy. When we do, we will change the effective date above and, for significant changes, tell you in the app or on the store listing.

## 11. Contact

Email: **hassam.ashraf450@gmail.com**
