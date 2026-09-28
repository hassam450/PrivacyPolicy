# Privacy Policy — IntelliDraft AI

**Effective date:** September 28, 2026
**App:** IntelliDraft AI ("IntelliDraft", "the app"), Android package `com.intellidraft.ai`
**Developer:** Tradewyn ("we", "us")
**Contact:** support@intellidraft.ai

IntelliDraft helps you write and read messages. You give it a draft, a one-line intent, a screenshot, or a message you received. The app uses AI to analyze the tone and suggest rewrites or replies. This policy explains what data the app handles, why, who it is shared with, and the choices you have.

The short version:

- The text and images you submit are sent to our server and to Google's Gemini AI to produce your result. We do not sell your data or use it for advertising.
- If you sign in with Google, your history and saved items sync to your account so they survive a reinstall. If you don't sign in, your history stays on your device.
- You can ask us to delete your account and data at any time (see [Deleting your account](#deleting-your-account-and-data)).

---

## 1. Information we collect

### 1.1 Content you submit for analysis
- **Text:** drafts you want analyzed or rewritten, one-line intents, and messages you paste or share into the app for Decode.
- **Images:** screenshots or photos you choose to attach, for example a screenshot of a conversation.
- **Settings that shape the analysis:** the context, recipient or "stakeholder" details, goals, forbidden words, presets and templates you choose or create.

This content can include information about other people, such as names or what they wrote to you. Only submit content you are comfortable having processed as described here.

### 1.2 Account information
- **Anonymous account:** when you first open the app we create an anonymous account identified by a random user ID. It contains no name or email.
- **Google sign-in (optional):** if you link a Google account, we receive your name, email address and profile photo URL from Google through Firebase Authentication.

### 1.3 Data saved to your account (signed-in users only)
If you are signed in with Google, the following is stored in our database (Google Cloud Firestore) under your user ID:
- **Analysis history:** your original text, the analysis and rewrites, and the context used. Your 100 most recent entries are kept (older ones are dropped automatically). Attached images are **not** saved in history.
- Your saved contexts, stakeholders, presets, templates, forbidden words and app settings.
- Usage statistics (for example, how many analyses you have run).

If you use the app anonymously, your history is stored only on your device.

### 1.4 Usage and limits
We record how many analyses, image analyses and decodes you run each day. This lets us apply the daily limits of the free and Pro plans.

### 1.5 Subscription information
Purchases are handled by **Google Play**. We never see your payment card details. Our subscription provider **RevenueCat** receives your app user ID and your purchase and subscription status from Google Play, so we can tell which features you have unlocked.

### 1.6 Diagnostics and app analytics
- **Firebase Crashlytics** collects crash reports: device model, OS version, app version, a stack trace, and your app user ID. We use them to find and fix bugs.
- **Google Analytics for Firebase** collects in-app usage events, for example "analysis started", "paywall viewed" or "onboarding completed", along with standard device and app information. **The text and images you submit are not included in analytics events.**
- **Server logs:** each request to our server writes a log line with technical details: user ID, plan, mode, whether an image was attached, token counts, timing and error codes. **Your message text and images are not written to these logs.**

### 1.7 Device integrity
We use **Firebase App Check** (backed by Google Play Integrity) to confirm that requests come from a genuine copy of the app. This helps protect the service from abuse.

### 1.8 What we do **not** collect
We do not collect your precise location, contacts, call logs or SMS. The app does not read your clipboard in the background. It only checks whether text is available, and reads it when you tap Paste. Reminder notifications are scheduled on your device, and no push token is sent to us.

---

## 2. How we use information

- To analyze your text or images and return tone analysis, rewrites, reply predictions and decodes. This is the core service.
- To save and sync your history and saved items if you are signed in.
- To enforce plan limits and unlock paid features.
- To keep the service secure and prevent abuse.
- To fix crashes and improve the app, using aggregated usage and diagnostic data.
- To answer you when you contact support.

We do **not** sell your personal information, use it for targeted advertising, or use your submitted content to train our own AI models.

---

## 3. AI processing by Google Gemini

To produce a result, the app sends your submitted text, any attached image, and the settings described in section 1.1 to our backend (Google Cloud Functions). The backend forwards them to **Google's Gemini API**. Google processes this content to generate the response, under the [Gemini API Additional Terms of Service](https://ai.google.dev/gemini-api/terms) and [Google's Privacy Policy](https://policies.google.com/privacy). Under the paid-service terms we use, Google does not use this content to improve its products. Google may keep it for a limited time to detect abuse.

AI output can be inaccurate, incomplete or inappropriate. Review every suggestion before you send it. If you see a harmful or offensive result, report it to support@intellidraft.ai.

---

## 4. Who we share information with

We share information only with the service providers that run the app, and only for the purposes above:

| Provider | Purpose | Data involved |
|---|---|---|
| Google Firebase / Google Cloud (Authentication, Firestore, Cloud Functions, Crashlytics, Analytics, App Check) | Accounts, storage, backend, diagnostics, analytics, abuse prevention | Account info, synced data, usage, diagnostics |
| Google Gemini API | Generating analyses and rewrites | Submitted text, images and settings |
| RevenueCat | Managing subscriptions | App user ID, purchase status |
| Google Play | Payments and app distribution | Handled under Google's own terms |

We may also disclose information when the law requires it, or to protect the rights and safety of users or others. If the app is ever sold or transferred, this policy will continue to apply to your data.

---

## 5. Data retention

- **Synced account data** (history, saved items, settings) is kept until you delete it in the app or delete your account.
- **Daily usage counters** are kept to enforce limits and may be deleted after they are no longer needed.
- **Server logs** are kept for up to 30 days.
- **Crash and analytics data** are kept according to Firebase's retention settings (Analytics event data for up to 14 months at most).
- **Content you submit** is not stored by us beyond your history (signed-in users) and is not written to our logs.

---

## 6. Deleting your account and data

- **In the app:** you can delete individual history entries, or clear all history, from the History screen. Deleted entries are also removed from your synced account.
- **Delete your account:** email **support@intellidraft.ai** from the email address of your linked Google account, with the subject "Delete my account". We will delete your account and all data stored under it (history, saved items, settings, usage records) within 30 days and confirm by email. Anonymous accounts that were never signed in keep their history only on your device. Uninstalling the app removes it.
- **Subscriptions:** deleting your account does not cancel a Google Play subscription. Cancel it in Google Play → Payments & subscriptions.

---

## 7. Security

Data is encrypted in transit (HTTPS/TLS) and stored on Google Cloud infrastructure. Database rules allow each user to access only their own data. The AI API key is kept on our server and is never shipped in the app. No system is perfectly secure, but we work to protect your information.

---

## 8. Children

IntelliDraft is not directed to children under 13 (or the minimum age of digital consent in your country). We do not knowingly collect their personal information. If you believe a child has given us data, contact us and we will delete it.

---

## 9. Your rights

Depending on where you live (for example under the GDPR in the EU/UK or the CCPA in California), you may have the right to access, correct, delete or export your personal data, and to object to or restrict certain processing. To use these rights, email support@intellidraft.ai. We will respond within the time the law requires. You may also complain to your local data protection authority.

Your data is processed on Google Cloud servers in the United States. Where required, transfers rely on the safeguards our providers offer, such as Standard Contractual Clauses.

---

## 10. Changes to this policy

We may update this policy as the app changes. We will change the effective date above. If the changes are significant, we will notify you in the app or on the store listing.

---

## 11. Contact

Questions or requests: **contact@tradewyn.uk**
