# Terms of Service

**Effective date:** June 26, 2026
**Last updated:** June 26, 2026

These Terms of Service ("Terms") govern your use of the **temp-ai** mobile application ("the App") provided by Matvii Suk ("we", "us").

By creating an account and using the App, you agree to these Terms. If you do not agree, do not use the App.

If you have questions, contact us at **matvii.suk.se@gmail.com**.

---

## 1. The Service

temp-ai is a voice-controlled household assistant for managing shared expenses, tasks, shopping lists, and places. Groups of users (e.g., families, roommates, partners) can share data within a group. The App processes voice commands either entirely on your device (default) or via Google's Gemini API in optional Cloud mode — see §5 for details.

The App is provided **as-is**, free of charge, with no warranty (see §10).

---

## 2. Your account

To use the App, you must sign in via Apple's Sign in with Apple. You agree:
- To provide accurate information (name, email — including Apple's "Hide My Email" relay).
- That you are at least 13 years old (or the digital-consent age in your country, whichever is higher).
- To keep your Apple ID credentials secure. Activity performed under your account is your responsibility.
- That one account per natural person; no bot, automated, or shared accounts.

---

## 3. Acceptable use

You agree **not** to use the App to:
- Violate any law of any country where you use the App.
- Harass, threaten, defame, or abuse other group members.
- Share content that is illegal, fraudulent, infringing on intellectual property, sexually explicit, or otherwise harmful.
- Attempt to reverse-engineer, decompile, or extract source code from the App beyond what is permitted by law.
- Attempt to gain unauthorized access to other users' accounts or data.
- Use the App to spam, scrape, or otherwise burden the service.
- Use the App for any commercial purpose beyond personal household management without our written permission.

We may suspend or terminate your account if you violate these rules. See §8.

---

## 4. Your content

You retain ownership of all the content you create in the App — expenses, tasks, shopping lists, places, group invitations, voice commands, and everything else you input.

By creating content within a shared group, you grant other members of that group the right to view, edit, and (where they have ownership permissions) delete that content. This is necessary for the App's group-collaboration features to function.

You grant us a **limited, non-exclusive, royalty-free license** to host, store, and display your content within the App for the sole purpose of operating the service for you. This license is automatically revoked when you delete your account or the content.

We do not sell your content. We do not use it for advertising or analytics. We do not transfer it to third parties beyond the backend providers listed in our Privacy Policy.

---

## 5. AI / voice features

The App includes an AI assistant with two processing modes that you choose between in **Settings → AI mode**:

- **On-device mode (default).** Voice is captured, transcribed, and interpreted entirely on your device by an embedded language model. Nothing about the request leaves your device.
- **Cloud mode (optional).** Voice is still transcribed on-device by Apple's speech recogniser; the resulting text plus the App context needed to act on it (place / category / task / expense names from your group) is sent over HTTPS to a Supabase Edge Function we operate, which calls **Google's Gemini API** to produce the response. Cloud mode is subject to **Google's Generative AI terms** (https://ai.google.dev/gemini-api/terms); by enabling Cloud mode you agree to those terms in addition to these. We use a paid (billing-enabled) Gemini API tier, under which Google does not use your prompts or responses to train its models. Cloud mode is available only to users aged 18 or older, as Google's Gemini API terms require; you confirm your age in-app before enabling it. We may apply daily usage limits to bound operating costs. We may also disable Cloud mode globally at any time without notice; the App will automatically fall back to On-device mode availability.

The AI may occasionally misinterpret commands or produce unexpected results in either mode. You are responsible for verifying that any action the AI proposes — adding an expense, creating a task, modifying a shopping list — is what you actually intended. We recommend carefully reviewing AI-suggested changes before confirming destructive actions (deletions).

We make no warranty about the accuracy, completeness, or fitness-for-purpose of AI-generated content.

---

## 6. Group invitations and ownership

A user who creates a group becomes its "owner". Owners can:
- Invite others to join via a 6-character invite code.
- Promote members to owners or demote owners to members.
- Remove members from the group.

If a group has multiple owners and one owner deletes their account, ownership of that owner's content is transferred to a remaining owner. If a sole owner deletes their account, the entire group is permanently deleted along with all its content.

You agree not to invite people to your group without their consent. The invite code is provided to you for sharing with people you trust.

---

## 7. Privacy

Our handling of your personal data is described in our [Privacy Policy](./privacy-en.md). By using the App, you confirm you have read and understood the Privacy Policy.

Key points:
- **Voice audio always stays on your device** — even in Cloud mode, speech recognition runs locally and only the resulting text command is sent over the network.
- **Cloud mode** (when you opt in) sends transcribed text + App context to Google's Gemini API via our server; it can be disabled at any time in Settings.
- Account email and content are stored on Supabase backend infrastructure.
- Crash diagnostics are sent to Sentry (no PII).
- You can delete your account at any time in the App.

---

## 8. Suspension and termination

We may suspend or terminate your account, at our discretion, if you:
- Violate these Terms (see §3).
- Engage in conduct that harms other users or the service.
- Use the App in a way we reasonably believe is fraudulent or illegal.

We will notify you of suspension or termination unless doing so would compromise an investigation or violate the law.

You may delete your account at any time via **Settings → Delete Account**. Deletion is permanent and irreversible.

---

## 9. Discontinuation of the service

We may discontinue, suspend, or change the App at any time without prior notice and without any obligation to provide a means of exporting your data.

temp-ai is operated by an individual developer, not a company, on a best-effort basis. We have no obligation to provide support, maintenance, updates, or continued availability of the App or any feature (including Cloud mode), and we may stop operating it entirely at any time.

We may also push updates to the App that change its features.

---

## 10. Disclaimer of warranties

THE APP IS PROVIDED **"AS IS"** AND **"AS AVAILABLE"** WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO IMPLIED WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, AND NON-INFRINGEMENT.

We do not warrant that:
- The App will be uninterrupted, error-free, or secure.
- The AI assistant will be accurate or produce specific results.
- Data sync between devices will be instant or never fail.
- Reminders (time-based or location-based) will always fire (subject to iOS background limits, network, and device permissions).

You use the App at your own risk.

---

## 11. Limitation of liability

To the maximum extent permitted by applicable law, in no event shall Matvii Suk be liable for any indirect, incidental, special, consequential, or punitive damages, including but not limited to loss of profits, data, use, goodwill, or other intangible losses, arising out of or related to your use of the App.

Our total cumulative liability to you for any claim arising from or related to the App shall not exceed the total amount you have paid us for the App in the 12 months before the claim — which, because the App is currently free, is **€0** — and in any case shall not exceed **€50** (fifty euros) or the equivalent in your local currency.

Some jurisdictions (notably the EU and some US states) do not allow the exclusion of certain warranties or the limitation of certain damages. In such jurisdictions, our liability is limited to the maximum extent permitted by law.

Nothing in these Terms limits liability that cannot legally be limited, including liability for death or personal injury caused by negligence, fraud, or willful misconduct.

---

## 12. Indemnification

You agree to indemnify and hold harmless Matvii Suk from any claim, demand, or expense (including reasonable attorneys' fees) arising out of:
- Your violation of these Terms.
- Your violation of any law or third-party right.
- Your misuse of the App.

This obligation survives termination of these Terms.

---

## 13. Governing law and jurisdiction

These Terms are governed by the laws of **Ukraine**.

For disputes involving consumers resident in the **European Union**, you may also rely on the mandatory consumer-protection rules of your country of residence, including the right to use the European Commission's Online Dispute Resolution platform: https://ec.europa.eu/consumers/odr/

For disputes involving consumers resident in the **United Kingdom**, the Consumer Rights Act 2015 applies in addition to these Terms.

Any dispute not resolved informally shall be subject to the exclusive jurisdiction of the courts of Ukraine, except where mandatory consumer-protection law of your jurisdiction requires otherwise.

---

## 14. Changes to these Terms

We may update these Terms from time to time to reflect changes in law, security, or how the App works. The "Last updated" date at the top indicates when. We will take reasonable steps to bring material changes to your attention through the App.

Your continued use of the App after a change indicates acceptance of the updated Terms. If you do not agree with the changes, you may delete your account.

---

## 15. Severability and entire agreement

If any provision of these Terms is found unenforceable or invalid, the remaining provisions remain in effect.

These Terms, together with the [Privacy Policy](./privacy-en.md), constitute the entire agreement between you and Matvii Suk regarding the App. They supersede any prior agreements or understandings.

---

## 16. Contact

Questions about these Terms: **matvii.suk.se@gmail.com**.
