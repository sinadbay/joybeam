# JoyBeam Privacy Policy

**Effective Date:** February 7, 2026

JoyBeam is built with a **"Privacy First"** architecture. We believe your most personal reflections should remain under your control. This policy explains how we handle your data across our local, cloud, and AI systems, and fulfills our legal obligation to disclose how Artificial Intelligence (AI) interacts with your information.

---

### 1. On-Device Storage (The Vault)
Most of your data resides exclusively on your iPhone.
* **Reflections & Daily Notes:** Stored in a local database (SwiftData) that is hardware-encrypted by Apple’s iOS.
* **Encryption Keys:** Your journal data is encrypted using **AES-GCM (256-bit)** before any cloud synchronization. The decryption key is stored in your **iOS Keychain**; JoyBeam cannot read your journal entries.
* **AI Context:** We generate a short-term summary (TLDR) of your history to assist Lumi. This summary is stored locally and is not archived on our servers.

### 2. Artificial Intelligence & Transparency (Lumi Chat)
JoyBeam utilizes **Lumi**, an AI agent powered by OpenAI (GPT-4o).
* **AI Disclosure:** In compliance with **California SB 243**, we disclose that Lumi is an artificially generated system and not a human. Lumi cannot provide medical advice, diagnosis, or crisis counseling.
* **Data Processing:** Only necessary, anonymized context is sent to the AI to answer your queries. 
* **No Training:** Your personal data is **not** used to train OpenAI’s foundational models. We use enterprise-tier privacy settings to ensure data is processed in a "Zero-Retention" environment.
* **Mandatory Safety Protocols:** We maintain a strictly coded "Safety Layer." If Lumi detects language indicating intent to harm yourself or others, the AI session will be suspended, and you will be automatically provided with crisis resources (e.g., 988 Suicide & Crisis Lifeline).

### 3. Cloud Synchronization & Security
To support backups and community features, we use **Firebase (Google Cloud)**:
* **Zero-Knowledge Backups:** While your reflections sync to the cloud, they remain encrypted with your device-side key. JoyBeam developers cannot read your content.
* **Lumi Chat Retention:** To support multi-device use, Lumi Chat logs are stored securely. These logs are automatically and permanently purged from our servers after **30 days**.
* **Social Data:** Phone numbers and profile photos are stored solely to enable "Beaming" support to friends.

### 4. Your Control, Deletion & Audit Rights
You own your data. We provide tools to ensure transparency and portability:
* **AI Provenance:** You have the right to know when you are interacting with AI. Per 2026 regulations, JoyBeam provides a visual reminder every 3 hours during continuous AI sessions.
* **PDF Export:** Export your entire history at any time via Profile settings.
* **Account Purge:** When you delete your account, all personal documents, photos, and encrypted reflections are permanently destroyed. Past interactions in "Circles" are anonymized to "Deleted User."

### 5. Third-Party Partners
We partner with these providers under strict Data Processing Agreements:
* **Google Firebase:** Secure Authentication and Cloud Storage.
* **OpenAI:** AI analysis and content generation.
* **RevenueCat:** Secure subscription management.

### 6. Contact & Support
If you have questions about this policy or your data rights under the 2026 AI Transparency Acts, please contact us through the app’s support channel.
