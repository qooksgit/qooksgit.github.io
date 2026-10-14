# Privacy Policy — Rclone Pi5 Backup

**Last updated:** October 14, 2026  
**Contact:** `<YOUR_CONTACT_EMAIL>`

## 1. About this application

Rclone Pi5 Backup is a personal, non-commercial backup setup operated by an individual. It uses [Rclone](https://rclone.org/) to connect a personally controlled Raspberry Pi to Google Drive and [Restic](https://restic.net/) to create encrypted backup repositories. This website provides information about the setup; it does not itself perform backups.

## 2. Information accessed

When the operator authorizes the application with Google, it requests the Google Drive `drive.file` permission. This permission allows the application to access and manage Google Drive files that the application creates or that the user explicitly opens with it.

The backup workflow may process:

- Files and folders selected for backup by the operator.
- File metadata needed to upload, list, download, and maintain backups (such as names, sizes, identifiers, and timestamps).
- OAuth credentials needed to maintain authorized access to Google Drive.

The application is not designed to read Gmail, contacts, or other unrelated Google services.

## 3. How the information is used

Google Drive access is used **only to store, verify, retrieve, and, according to the operator's retention settings, remove backup data**. Backup contents are encrypted by Restic before upload to Google Drive. Google Drive still processes the encrypted objects and associated storage metadata.

Google user data is **not used for advertising, profiling, or training AI models**, and is not sold.

## 4. Storage and sharing

Backup data is stored in the operator's Google Drive account. OAuth credentials are stored in the operator-controlled Rclone configuration on local devices; they are not intentionally published on this website. Backups are handled locally and by Google Drive as the storage provider. No separate application backend collects or receives Google Drive user data.

This public information website does not intentionally collect visitor-submitted personal data and does not use its own advertising or analytics scripts. The website host (GitHub Pages) may process technical access logs under its own policies.

## 5. Retention and deletion

The operator controls backup retention and can delete backup repositories from Google Drive. Local copies and authentication configuration can also be deleted by the operator. Removing the application's Google account access prevents future authorized access but does not automatically delete backups already stored in Drive.

Google access can be revoked through [Google Account → Third-party connections](https://myaccount.google.com/connections).

## 6. Security

Restic encrypts backup contents before uploading them. Access to the Google account, OAuth credentials, and Restic repository password must be protected separately. No storage or transmission method is guaranteed to be risk-free.

## 7. Changes

This policy may be updated if the backup workflow or the way Google user data is handled changes. Updates will appear on this page with a revised date.

## 8. Contact

Questions about this personal application may be sent to: **`<YOUR_CONTACT_EMAIL>`**.
