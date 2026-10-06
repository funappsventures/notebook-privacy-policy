# Privacy Policy — FunApps Notebook

**Last updated: October 6, 2026**

This Privacy Policy explains how **Notebook** ("we", "our", or "us") handles information when you use the Notebook Android application ("App").

## 1. Overview

Notebook is an offline-first notebook application designed to keep your notes and personal content on your device.

**We do not collect, sell, or transmit your personal information to our servers.** The App does not use analytics, advertising networks, crash-reporting services, or other third-party services that collect information from the App.

Notebook does not require an internet connection for its notebook functionality.

## 2. Information We Do Not Collect

We do not collect:

- Your name, email address, or phone number
- Contacts or address-book information
- Device identifiers
- Advertising IDs
- Location information
- Analytics or usage information
- Note content
- Notebook files or folders
- PINs or passwords
- Crash reports or telemetry

The App does not have its own server or backend for collecting your notebook data.

## 3. Information Stored on Your Device

Notebook stores information locally on your Android device so that the App can provide its features.

This may include:

### Notebook content

- Folders
- Files
- Note text

### Notebook metadata

- File and folder names
- Creation and modification information
- Sort order
- Pinned state
- Colors
- Trash state

### App settings

- Theme preference
- Sort preference
- "Show locked items" preference
- Focus Mode hint preference

### Lock information

If you enable the App's item-locking feature, Notebook stores protected information required to verify your PIN.

Your raw PIN is **not stored in plaintext**.

If you configure a security question for PIN recovery, the security question information and answer are stored locally in protected form.

## 4. How Your Local Data Is Protected

Notebook takes steps to protect locally stored information.

### Note content

Note content is encrypted at rest using **AES-GCM** with a key stored in the Android Keystore. The encryption key is not stored as ordinary application data.

### PIN

Your PIN is processed into a protected credential before being stored. The raw PIN is not persisted by the App.

### Security question

Security question information used for PIN recovery is stored locally in protected form.

### File writes

Notebook uses atomic file-writing operations for note content to reduce the risk of corruption during writes.

No security system can guarantee absolute protection against every possible threat.

## 5. Backup and Restore

Notebook provides an optional, user-initiated backup and restore feature.

When you create a backup, Notebook creates a **ZIP backup that is not encrypted**.

Anyone who obtains the backup file may be able to read the information contained within it.

You choose the backup destination using Android's standard Storage Access Framework. Notebook does not choose or control the destination.

By default:

- Locked items are excluded from backups.
- You may choose to include locked items after successful PIN verification.
- Bin contents are excluded.
- Recent-file history is excluded.
- Your PIN credential is not included in the backup.

Backup and restore operations may temporarily create files in the App's private cache directory. These temporary files are removed when the operation completes or fails.

## 6. Android System Backup

Notebook is configured not to participate in standard Android application backup.

The App also specifically excludes sensitive lock-related information from its backup configuration.

However, Android device-transfer and backup behavior can vary by Android version and device manufacturer. Some non-sensitive local application data may potentially be transferred as part of device migration depending on your device's configuration.

For a complete independent copy of your notebook, use Notebook's built-in backup feature.

## 7. Clipboard and Sharing

Notebook provides user-initiated **Copy** and **Share** functionality.

When you choose to copy note content, the selected content is passed to the Android system clipboard.

When you choose to share note content, the content is passed through Android's standard sharing mechanism to the app or service you select.

Notebook does not automatically access your clipboard or automatically share your notes.

Once information is intentionally shared with another application or service, that application's privacy policy and practices apply.

## 8. External Links

The App may provide a link to this Privacy Policy.

When you tap the link, Android may open your default web browser to display the policy.

Notebook itself does not send your notebook data to the website hosting this policy.

## 9. Data Sharing

Notebook does not sell, rent, or share your notebook data with third parties.

The App does not transmit your notebook content or personal information to our servers.

Information is only passed outside the App when you **explicitly choose an Android system action**, such as copying content to the clipboard, sharing content with another application, or saving a backup to a location you select.

## 10. Children's Privacy

Notebook is not directed toward children under the age of 13.

We do not knowingly collect personal information from children.

## 11. Your Data and Deletion

Because Notebook does not maintain an online account or server-side profile for you, we do not have a copy of your notebook data to retrieve or delete.

You can manage your locally stored information by:

- Deleting individual notes or folders
- Emptying the Bin
- Permanently deleting items
- Removing your lock information
- Clearing the App's data through Android Settings
- Uninstalling the App

**Important:** Clearing App data or uninstalling Notebook may permanently remove locally stored notebook content if you do not have a backup.

Backup files you create are controlled by you and remain wherever you chose to save them.

## 12. Security Limitations

We take reasonable measures to protect information stored by Notebook, including encryption of note content and protected handling of PIN credentials.

However, no application or storage system can guarantee absolute security.

If you lose your PIN and cannot use the available recovery mechanism, locked content may not be recoverable.

You should also protect any backup files you create because Notebook backups are not encrypted.

## 13. Changes to This Privacy Policy

We may update this Privacy Policy when the App's functionality changes or when required by applicable laws or regulations.

When we make material changes, we will update the **"Last updated"** date at the top of this policy.

## 14. Contact Us

If you have questions, concerns, or requests regarding this Privacy Policy or Notebook, please contact us at:

**Email:** funappsventures@gmail.com
