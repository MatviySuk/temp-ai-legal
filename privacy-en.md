# Privacy Policy

**Effective date:** 2026-06-17
**Last updated:** 2026-06-17

This Privacy Policy explains how Matvii Suk ("we", "us") collects, uses, and protects personal data when you use the **temp-ai** mobile application ("the App"). The App is distributed worldwide via Apple's App Store.

If you have questions or wish to exercise any of the rights described below, contact us at **matvii.suk.se@gmail.com**.

---

## 1. Who is the data controller?

**Matvii Suk**
Email: matvii.suk.se@gmail.com
Jurisdiction: Ukraine

We are the data controller for personal data processed by the App as defined by the EU General Data Protection Regulation (GDPR), the UK GDPR and Data Protection Act 2018, the California Consumer Privacy Act / California Privacy Rights Act (CCPA / CPRA), Brazil's Lei Geral de Proteção de Dados (LGPD), and Ukraine's Law on Personal Data Protection.

---

## 2. What data we collect

We collect only what the App needs to function. We do not sell or rent your data. We do not use it for advertising. We do not track you across other apps or websites.

### 2.1 Account data
- **Email address** — received from Apple via Sign in with Apple. You may choose Apple's "Hide My Email" relay; we accept the relay address.
- **Display name** — provided by you (or by Apple on first sign-in).
- **User identifier** (UUID) — generated for you when you create your account.

### 2.2 Content you create
- Expenses, tasks, shopping items, places, group memberships, and other records you enter or that other members of your group share with you.
- Voice transcriptions when you use the AI assistant — see §2.4 below.

### 2.3 Location
- **Coarse-grained location coordinates** — only when you grant location permission and only for the purpose of triggering reminders when you arrive at a place you've saved (e.g., "remind me to buy milk when I'm at the supermarket"). Coordinates are processed on-device. We do not store your live location on our servers.

### 2.4 Voice and audio
- The App's AI assistant performs **all voice processing on your device** using an embedded language model. Audio is captured by the microphone, transcribed locally, processed locally, and discarded. Audio recordings are never transmitted to our servers or to any third party.

### 2.5 Diagnostic and crash data
- If a crash or non-fatal error occurs, anonymous technical details (stack trace, device model, OS version) are sent to Sentry to help us fix the bug. Crash data is not linked to your account.

### 2.6 What we do **not** collect
- We do not collect your contacts, calendar, photos, health data, or financial data outside the App.
- We do not use third-party advertising SDKs.
- We do not use analytics SDKs that profile you across apps.
- We do not collect IP addresses or device identifiers for tracking purposes (Apple's IDFA is never requested).

---

## 3. Lawful bases for processing (GDPR / UK GDPR)

We process your personal data under the following lawful bases:

| Purpose | Lawful basis |
|:---|:---|
| Creating and maintaining your account | Contract (Art. 6(1)(b)) — necessary to provide the service you signed up for |
| Storing the content you create (expenses, tasks, shopping items, places, group data) | Contract (Art. 6(1)(b)) |
| Sending you task reminders (time-based and location-based) | Contract (Art. 6(1)(b)) |
| Sharing your content with other members of groups you join | Contract (Art. 6(1)(b)) |
| Diagnosing crashes via Sentry | Legitimate interest (Art. 6(1)(f)) — operating a stable service |
| Voice processing on-device | Performed locally on your device; no transfer to us occurs |

---

## 4. Who we share data with

We share your personal data only with the service providers required to operate the App. We do not sell or rent your data to anyone.

- **Supabase Inc.** — database, authentication, and synchronization. See [Supabase's privacy policy](https://supabase.com/privacy).
- **Sentry / Functional Software, Inc.** — crash and error reporting. See [Sentry's privacy policy](https://sentry.io/privacy/).
- **Apple Inc.** — Sign in with Apple authentication. We never see your Apple ID password. Apple may share a privaterelay.appleid.com address if you choose "Hide My Email". See [Apple's privacy policy](https://www.apple.com/legal/privacy/).

Where your data is processed outside your country of residence, we rely on the legal mechanisms required by applicable data-protection law (for example, Standard Contractual Clauses for transfers from the EU/UK).

---

## 5. How long we keep your data

We keep your data for as long as your account exists. When you delete your account (see §7), your account record and personal information are permanently removed from our systems.

**Content reassignment on deletion:** If you have shared content with a group (expenses, tasks, shopping items) and you leave or delete your account, that content is reassigned to another active owner of the group so that group history is preserved. The content no longer carries any link to you personally. If you are the sole owner of a group, the entire group and all its content is permanently deleted with your account.

Crash reports retained by Sentry follow Sentry's standard retention policy.

---

## 6. Your rights

Depending on where you live, you have some or all of the following rights regarding your personal data:

- **Access** — request a copy of the personal data we hold about you.
- **Rectification / Correction** — ask us to correct inaccurate data.
- **Erasure / Deletion** — request deletion of your account and personal data.
- **Restriction** — limit how we process your data.
- **Portability** — request your data in a structured, machine-readable format.
- **Object** — object to processing based on legitimate interest.
- **Withdraw consent** — where processing relies on consent.
- **Complaint** — lodge a complaint with your local data-protection authority.

### 6.1 Additional rights for California residents (CCPA / CPRA)

- **Right to opt-out of sale or sharing** — we do not sell or share your personal information; this right is automatically honoured.
- **Right to limit use of sensitive personal information** — we do not collect "sensitive personal information" as defined under California law.
- **Right to non-discrimination** — exercising your rights will not change the service you receive.

### 6.2 How to exercise your rights

The simplest way to delete your account is via the App: **Settings → Delete Account**.

For any other request, email **matvii.suk.se@gmail.com** with a description of what you need. We will respond within 30 days (GDPR) or 45 days (CCPA), with a possible 30-day extension for complex requests.

---

## 7. Account deletion

You can delete your account at any time in the App: **Settings → Delete Account**. The action is irreversible.

When you delete your account:
- Your Apple Sign-in record is permanently removed from our authentication system.
- Your personal information (email, name, user ID) is permanently erased.
- Content you authored within shared groups is reassigned to another active owner of the group so other members retain access to group history.
- If you are the sole owner of a group, the entire group and all its content is permanently deleted alongside your account.
- Any pending notifications scheduled on your device are cancelled.

Apple's Sign in with Apple revocation (Settings → Apple ID → Sign in with Apple → temp-ai → Stop Using Apple ID) will also sign you out of the App. Note that this only revokes the sign-in link; to fully delete your account on our side, use the in-app deletion.

---

## 8. Security

We protect your data with industry-standard measures:
- **Encryption in transit** — all communication with our backend uses HTTPS/TLS.
- **Encryption at rest** — data stored by our backend provider (Supabase) is encrypted at rest by default.
- **Authentication** — Sign in with Apple, plus row-level security policies that ensure each user can only access data from groups they belong to.
- **No third-party trackers** — see §2.6.

No system is 100% secure. If we become aware of a security incident affecting your data, we will notify you and the relevant authorities as required by law.

---

## 9. Children

The App is rated 4+ in the App Store but is not directed at children under 13. We do not knowingly collect personal information from children under 13. If you believe a child has provided us with personal information, contact us at matvii.suk.se@gmail.com and we will delete the information promptly.

For the EU, the digital-consent age varies by member state (13–16). If you are below the age of digital consent in your country, please obtain a parent's or guardian's permission before using the App.

---

## 10. Cookies and similar technologies

The App does not use cookies. We do not run a website tied to the App at this time.

---

## 11. Changes to this Privacy Policy

We may update this policy from time to time. The "Last updated" date at the top of this document indicates when. Your continued use of the App after a change indicates acceptance of the updated policy.

---

## 12. Contact

Questions, requests to exercise your rights, or anything else: **matvii.suk.se@gmail.com**.
