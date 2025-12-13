# Privacy Policy for SeClip

**Effective Date:** December 12, 2025

KuroAppWorks ("we," "our," or "us") operates the SeClip mobile application (the "Service"). This Privacy Policy informs you of our policies regarding the collection, use, and disclosure of personal data when you use our Service and the choices you have associated with that data.

We are committed to protecting your privacy. All data you create within SeClip is stored locally on your device and is not transmitted to us or any third party, except for data collected by our advertising partners as described below.

## Information Collection and Use

### 1. Data You Provide (Stored Locally and Encrypted):

*   **Keywords, Secure Items, and Notes:** Any text, IDs, passwords, notes, or other information you save in the "Clips" and "Secure" tabs is stored exclusively in a local database on your device.
*   **Encrypted Data:** Information saved in the "Secure" tab, including notes and custom fields, is encrypted using industry-standard AES-256 (GCM mode) encryption before it is saved to your device's local database. The decryption key is derived from your master password and is never stored in plaintext.

### 2. App Settings and Preferences (Stored Locally):

Your app preferences, such as theme settings, font size, and authentication settings, are stored locally on your device using Android's DataStore.

### 3. Information for Advertising and Consent Management:

To support the Service, we display ads and manage user consent. This involves the collection of certain device information by our third-party partners.

*   **Google AdMob:** We use Google AdMob to serve ads. AdMob may collect data such as device identifiers (e.g., Advertising ID), IP addresses, and information about your interaction with ads to provide a personalized advertising experience.
*   **Google User Messaging Platform (UMP) SDK:** In regions subject to data protection regulations like GDPR and CCPA, we use Google's UMP SDK to obtain and manage your consent for the collection and use of data for advertising purposes. Your consent choices are stored locally and respected by the advertising services.

## Data Security

We take the security of your data very seriously and have implemented multiple layers of protection.

*   **Encryption at Rest:** All items in the "Secure" tab are encrypted. Without your master password, this data is computationally infeasible to decrypt.
*   **In-Memory Password Caching:** To provide convenient access to the Secure tab (e.g., via PIN or biometrics), your master password may be temporarily held in your device's memory (RAM) after you successfully authenticate. This cache is cleared as soon as the app goes to the background or is closed.
*   **Screen Security:** To protect against visual data leakage, the Service utilizes Android's `FLAG_SECURE`. This prevents screenshots, screen recording, and the display of the app's content in the recent apps list (task switcher).
*   **Backup Restriction:** We have intentionally disabled the standard Android Auto Backup feature for this app. This is a security measure to prevent your sensitive data (including encrypted items and settings) from being automatically uploaded to your Google Drive or other cloud backup services.

## Backup and Restore (User-Controlled)

*   **Optional Feature:** The Service provides an optional feature to back up your data to a file of your choosing. This process is initiated and controlled entirely by you.
*   **Backup File Security:** If you include "Secure Items" in your backup, the backup file will contain the encrypted data and a hash of the password from the time of backup. The plaintext password itself is not stored in the same way as it is for live app use.
*   **Restore Security:** To restore a backup containing secure items, you **must** provide the master password that was active when the backup was created. This ensures that only someone who possesses both the backup file and the correct password can access the encrypted information.

## Clipboard Management

*   **Clipboard Writing:** The core function of the app is to write your saved information to the device's clipboard for your convenience. The app **does not read** the clipboard's contents.
*   **Sensitive Data Handling (Android 13+):** When copying items from the "Secure" tab on devices running Android 13 or higher, the data is marked as "sensitive." This signals to the Android OS to hide the content from previews and automatically clear it after a period of time (typically one hour).
*   **Manual Clipboard Clearing (Optional):** The Service provides an optional notification with a "Clear Clipboard" button. When enabled, this allows you to manually clear the clipboard's contents at any time for enhanced security.

## Permissions

The Service may request the following permissions:

*   **Biometric/Fingerprint:** To enable unlocking the "Secure" tab with your device's biometric sensors.
*   **Notifications:** To provide a persistent notification for quick app access and the optional clipboard clearing feature.

## User Choices and Consent

In regions covered by GDPR, CCPA, or similar regulations, you will be presented with a consent form upon first launch to choose how your data is used for advertising. You can change your consent preferences at any time from the app's Settings screen.

## Changes to This Privacy Policy

We may update our Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy within the app. You are advised to review this Privacy Policy periodically for any changes.

## Contact Us

If you have any questions about this Privacy Policy, please contact us at: [kuroappworks+contact@gmail.com](mailto:kuroappworks+contact@gmail.com)

---

### Other Languages

*   [日本語 (Japanese)](https://kuroappworks-gif.github.io/seclip-privacy-policy/ja.html)
*   [中文 (Chinese)](https://kuroappworks-gif.github.io/seclip-privacy-policy/zh.html)
*   [한국어 (Korean)](https://kuroappworks-gif.github.io/seclip-privacy-policy/ko.html)
*   [Français (French)](https://kuroappworks-gif.github.io/seclip-privacy-policy/fr.html)
*   [Deutsch (German)](https://kuroappworks-gif.github.io/seclip-privacy-policy/de.html)
*   [Español (Spanish)](https://kuroappworks-gif.github.io/seclip-privacy-policy/es.html)
*   [हिन्दी (Hindi)](https://kuroappworks-gif.github.io/seclip-privacy-policy/hi.html)
