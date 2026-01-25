# JoyBeam Privacy Policy

**Effective Date:** January 24, 2026

JoyBeam is built with a "Privacy First" architecture. We believe your most personal reflections should remain under your control. This policy explains how we handle your data across our local, cloud, and AI systems.

---

## 1. On-Device Storage (The Vault)
Most of your data resides exclusively on your iPhone.
*   **Reflections & Daily Notes**: Stored in a local database (SwiftData) that is hardware-encrypted by Apple’s iOS.
*   **Encryption Keys**: Your journal data is encrypted using **AES-GCM (256-bit)** before any cloud synchronization. The decryption key is stored in your **iOS Keychain**, meaning it never leaves your physical device and cannot be accessed by us.
*   **AI Context**: We generate a short-term summary (TLDR) of your history to assist the AI. This summary is stored locally on your device and is not archived on our servers.

## 2. Cloud Synchronization (Secure Backup)
To support backups and community features, we use **Firebase (Google Cloud)**:
*   **Encrypted Content**: We sync your reflections and gratitudes to the cloud so you don’t lose them. However, because this content is encrypted on your device, **it cannot be read by anyone else**, including JoyBeam developers.
*   **Social Data**: Your phone number, profile photo, and circle names are stored to enable social discovery and "Beaming" support to friends.
*   **Lumi Chat Backup**: Your AI conversations (Lumi Chat) are backed up securely for multi-device support. Conversations are automatically and permanently deleted from our servers after **30 days**.

## 3. Artificial Intelligence (AI)
JoyBeam uses **OpenAI** (GPT-4o) to provide personalized growth insights:
*   **Data Usage**: Only necessary, summarized context is sent to the AI to answer your specific queries.
*   **Privacy**: Your personal data is **not** used to train OpenAI’s foundational models. We use enterprise-tier privacy settings to ensure your data is processed and then discarded.

## 4. Your Control & Deletion
You own your data. We provide tools to ensure you can take it with you or erase it:
*   **PDF Export**: You can export your entire journal history as a beautifully formatted PDF at any time via the Profile settings.
*   **Thorough Deletion**: When you delete your account:
    *   **Private Data**: All personal documents, photos, and encrypted reflections are permanently purged from our servers.
    *   **Anonymization**: To maintain the history of your friends' Circles, your past interactions are "anonymized." Your name is removed and replaced with "Deleted User," effectively erasing your identity from the group record.

## 5. Third-Party Services
We partner with these providers to ensure a seamless experience:
*   **Google Firebase**: Secure Authentication and Cloud Storage.
*   **OpenAI**: AI analysis and content generation.
*   **RevenueCat**: Secure subscription and purchase management.

---

## 6. Contact Us
If you have questions about this policy or your data, please contact us through the app’s support channel.
