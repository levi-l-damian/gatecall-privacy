# GateCall Privacy Policy

Last updated: 2026-10-31

## Developer and contact

GateCall is developed by Liviu Damian and listed on Google Play under Damian App Dev. For privacy questions or support, email levi.l.damian@gmail.com. You do not need to provide caller numbers, contact lists or call history when asking for help.

Published policy: https://levi-l-damian.github.io/gatecall-privacy/PRIVACY_POLICY.html

## Scope

This policy describes GateCall 1.1 Free for Android: a calls-only application. GateCall has no accounts, advertisements, purchases, subscriptions, SMS/MMS features or external unwanted-call reporting. No registration is required.

## Information accessed and its purpose

With your Contacts permission, GateCall reads contact names and telephone numbers to display Approved Contacts, identify callers and help you select numbers to block. GateCall does not add, edit or delete Android Contacts and does not maintain a separate persistent copy of your contact list.

Android supplies incoming-call metadata, including the available caller ID and call timing, to GateCall's authorized call-screening service. When protection is on, GateCall checks explicitly blocked numbers before allowing saved contacts; unknown callers are rejected within Android's supported capabilities. Screening operates when the app is not open. Emergency safeguards apply. Android does not provide private or unavailable caller IDs for screening, and carrier voicemail remains outside GateCall's control.

GateCall stores your explicit blocked numbers, recorded blocked-call events (number, time and screening reason), local suspected-scam labels, and application preferences on your device. These support call protection, caller details, repeat-attempt history and Home counters. A recorded screening decision is not independent proof that a carrier disconnected a call.

## Local suspected-scam labels

Mark as Scam records your own local suspicion. Caller ID can be spoofed; a label is not proof of fraud. Labels are not sent to authorities, carriers, Google or other users. A label does not automatically add a number to Blocked Numbers or change the screening rules. You can remove a classification through caller details or Manage scam labels. Labels remain independent of call history, including after history is cleared.

## Local processing and sharing

GateCall processes its call-protection data locally. The app does not transmit contacts, caller IDs, call history, blocked numbers or scam labels to the developer or external services. It contains no advertising or analytics SDKs and does not sell personal data. The production app does not request Internet access.

If you choose to email support, the email service processes your message and the developer receives the information you include. Support correspondence is used to address your request, is not linked to an in-app account, and may be kept while needed to resolve the matter or meet applicable obligations. You may request its deletion by email, subject to those obligations. Visiting the published policy uses your browser and GitHub Pages; those services handle web requests under their own privacy terms. Reading the policy inside GateCall works offline and makes no web request.

## Permissions and Android settings

Contacts permission is used only for the local functions described above. You may revoke it in Android Settings. Without Contacts permission, GateCall does not query or use cached Contacts data and continues rejecting callers Android supplies when protection is on. Android may bypass screening for saved contacts in this state, so explicit blocks against saved contacts cannot be guaranteed. Home and Settings display limited protection and offer a way to restore permission. Full contact-based protection resumes after permission is restored. If a Contacts lookup fails or exceeds its bounded deadline, a delivered caller is rejected with the lookup limitation recorded; a failed lookup is not proof that the number is absent from Contacts. Android's call-screening authorization is required to screen calls. GateCall does not request SMS or Android Call Log access; its Blocked Calls list contains its own screening records.

GateCall can display Android's battery-optimization status and open ordinary Android battery settings at your request. It does not request a direct battery-optimization exemption. Battery status alone does not establish whether a call was screened successfully.

## Retention and deletion

Blocked-call history retains up to the latest 500 recorded events. Older events are removed as new records exceed that limit. You can clear this history in Blocked; doing so does not remove explicit blocks or scam labels.

Explicit blocks and local scam labels remain until you remove them. Preferences remain until changed or app storage is removed. Turning protection off does not erase any of these records. Removing a block or scam label does not delete Android Contacts or historical call events.

Uninstalling GateCall or clearing its Android app storage removes the app's local records and preferences. These actions are optional and are not required to install an ordinary compatible update. The developer has no server copy of this local data to retrieve or delete remotely.

## Backup and device transfer

GateCall 1.1 is configured to exclude its private data from Android cloud backups and Android device-to-device transfer using backup exclusions for supported Android versions. This configuration does not delete records already stored in the installed app. Ordinary compatible app updates preserve local data.

Automatic restoration of GateCall records after uninstalling, resetting or moving to another device is not provided. These settings do not retroactively erase backups created by earlier versions. Older backups are managed through the device or backup provider. Manufacturer-specific transfer tools may behave differently; GateCall cannot guarantee the behavior of tools that do not honor Android's exclusions. Android Contacts and their separate account backup settings are outside GateCall's control.

## Security

GateCall uses Android app-private storage and platform access controls. Caller numbers, contact names and individual call records are excluded from GateCall's diagnostic logging. Local protection data is not included in support messages automatically. Keep your device protected and send only the information needed when contacting support.

## Policy changes

Material changes to GateCall's data handling will be reflected in this policy and relevant in-app disclosures. The current policy is available offline in Settings and at the published URL above.
