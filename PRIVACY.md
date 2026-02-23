# JoyBeam Privacy Policy

**Effective Date:** February 8, 2026  
**Owner:** Dbaydev LLC

---

JoyBeam is built with a **"Privacy First"** architecture. We believe your most personal reflections should remain under your control. This policy explains how we handle your data across our local, cloud, and AI systems, and fulfills our legal obligation to disclose how Artificial Intelligence (AI) interacts with your information.

---

## 1. On-Device Storage (The Vault)

Most of your data resides exclusively on your iPhone.

- **Reflections & Daily Notes:** Stored in a local database (SwiftData) that is hardware-encrypted by Apple's iOS.
- **Encryption Keys:** Your journal data is encrypted using **AES-GCM (256-bit)** before any cloud synchronization. The decryption key is stored in your **iOS Keychain** and synced via **iCloud Keychain** to enable data recovery across your Apple devices and app reinstalls. **Note:** iCloud Keychain is managed entirely by Apple. While Apple represents that iCloud Keychain uses end-to-end encryption, JoyBeam cannot independently verify or guarantee the security of Apple's infrastructure. See Section 3 for details.
- **AI Context:** We generate a short-term summary (TLDR) of your history to assist Lumi. This summary is stored locally and is not archived on our servers.

---

## 2. Artificial Intelligence & Transparency (Lumi Chat)

JoyBeam utilizes **Lumi**, an AI agent powered by OpenAI (GPT-4o).

- **AI Disclosure:** In compliance with **California SB 243**, we disclose that Lumi is an artificially generated system and not a human. Lumi cannot provide medical advice, diagnosis, or crisis counseling.
- **Data Processing:** Only necessary, anonymized context is sent to the AI to answer your queries.
- **No Training:** Your personal data is **not** used to train OpenAI's foundational models. We use enterprise-tier privacy settings to ensure data is processed in a "Zero-Retention" environment.
- **Mandatory Safety Protocols:** We maintain a strictly coded "Safety Layer." If Lumi detects language indicating intent to harm yourself or others, the AI session will be suspended, and you will be automatically provided with crisis resources (e.g., 988 Suicide & Crisis Lifeline).

---

## 3. Cloud Synchronization & Security

To support backups and community features, we use **Firebase (Google Cloud)**:

- **Encrypted Cloud Backups (Plus/Pro):** Your reflections, check-in notes, gratitude entries, daily plans, and chat messages are encrypted on your device using AES-GCM (256-bit) before being transmitted to Firebase. The data stored on our servers is ciphertext that JoyBeam cannot read without your key.
- **Key Storage & Recovery:** Your encryption key is stored in your iOS Keychain and synced via Apple's iCloud Keychain to your other Apple devices. This enables recovery after reinstalling the app or switching to a new iPhone, as long as you remain signed in to the same Apple ID with iCloud Keychain enabled.
- **What This Means (Transparency):** JoyBeam's servers **never** see or store your encryption key. However, because the key is synced through Apple's iCloud Keychain, Apple's infrastructure handles key transport and storage. Apple represents that iCloud Keychain is end-to-end encrypted, but JoyBeam cannot independently audit or guarantee Apple's security practices. This system should be understood as **"encrypted at rest with key recovery managed by Apple"** rather than a fully zero-knowledge system controlled solely by JoyBeam.
- **Risk of Data Loss:** If you disable iCloud Keychain, sign out of your Apple ID, or lose access to your Apple account, your encryption key may become unrecoverable and your cloud-backed data will be permanently inaccessible. JoyBeam has no ability to recover your key. We strongly recommend enabling **Two-Factor Authentication** and **Advanced Data Protection** on your Apple ID.
- **Lumi Chat Retention:** To support multi-device use, Lumi Chat logs are stored in encrypted form. These logs are automatically and permanently purged from our servers after **30 days**.
- **Social Data:** Phone numbers and profile photos are stored solely to enable "Beaming" support to friends.

---

## 4. Your Control, Deletion & Audit Rights

You own your data. We provide tools to ensure transparency and portability:

- **AI Provenance:** You have the right to know when you are interacting with AI. Per 2026 regulations, JoyBeam provides a visual reminder every 3 hours during continuous AI sessions.
- **PDF Export:** Export your entire history at any time via Profile settings (Pro).
- **Account Purge:** When you delete your account, all personal documents, photos, and encrypted reflections are permanently destroyed. Past interactions in "Circles" are anonymized to "Deleted User."

---

## 5. Third-Party Partners

We partner with these providers under strict Data Processing Agreements:

- **Google Firebase:** Secure Authentication, Cloud Storage, and push notifications.
- **OpenAI:** AI analysis and content generation (Lumi).
- **Apple:** Sign in with Apple, App Store and in-app purchase processing.
- **RevenueCat:** Secure subscription management (if applicable).

---

## 6. App Analytics

We use Google Analytics for Firebase to understand how JoyBeam is used and to improve the app. This data is aggregated and anonymous. We do not track your location, and we do not share your personal reflections or private journal entries with Google.

---

## 7. Contact & Support

JoyBeam is owned and operated by **Dbaydev LLC**.

If you have questions about this policy or your data rights under the 2026 AI Transparency Acts, please contact us through the app's support channel or at your designated support URL (https://dbay.dev/#contact).

---

*Last Updated: February 8, 2026*
