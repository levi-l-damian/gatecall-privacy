# GateCall Privacy Policy

Last updated: 2026-10-15

## Introduction

GateCall is an Android application providing whitelist-first call protection and SMS/MMS messaging. It is designed to reduce unwanted calls, spam calls, robocalls, and unknown caller interruptions while allowing users to manage text and multimedia messages.

GateCall follows a local-first privacy model. Its application data, including its SQLite databases, is stored on the user's device rather than in a GateCall-operated cloud service.

## Information GateCall Accesses

Depending on the features used and the permissions granted, GateCall may access:

- Phone contacts
- Incoming call metadata
- Explicitly blocked phone numbers
- Blocked activity history
- SMS and MMS message content and associated metadata, such as phone numbers and message timestamps
- MMS attachments and related message information
- Existing SMS/MMS history when the user chooses to import it

## Why GateCall Accesses This Information

GateCall uses this information to:

- Allow calls from approved contacts
- Block unknown callers and explicitly blocked numbers
- Maintain local blocked activity history
- Provide operational dashboard statistics
- Send, receive, display, and manage SMS/MMS messages when GateCall is the Android default SMS application
- Handle supported MMS attachments
- Import existing message history when the user chooses that option

## Local Processing and Storage

GateCall processes and stores its call-protection and messaging information locally on the Android device, including in local SQLite databases where applicable.

GateCall does not use Firebase, Supabase, or a GateCall-operated cloud service to store or synchronize contacts, blocked numbers, call activity, SMS/MMS content, or attachments.

Sending and receiving SMS/MMS necessarily involves the user's mobile carrier and the intended message recipients. Carrier processing and recipient handling are outside GateCall's local storage and are governed by their respective services and policies.

## Default SMS Application and Messaging Permissions

GateCall requests the Android default SMS application role when the user chooses to enable its SMS/MMS functionality. Android presents the system role-selection interface. Users can manage or change their default SMS application through Android settings.

For its default SMS functionality, GateCall may request the following Android permissions:

- `RECEIVE_SMS`: receive incoming SMS messages
- `RECEIVE_MMS`: receive incoming MMS messages
- `READ_SMS`: access messages needed for messaging functions, including supported message-history access
- `SEND_SMS`: send SMS messages initiated through the application

These permissions are used for GateCall's messaging functionality, not for advertising or the sale of message data.

## Existing Message History

GateCall offers an optional import of existing SMS and MMS history from Android. During onboarding, users can choose **Import Messages** or **Not Now**. The import option can also be accessed later from Settings.

Imported message information is stored locally on the device. Choosing not to import existing history does not itself authorize an import.

## Contacts Permission

GateCall uses Contacts permission to identify approved callers saved in the user's device contacts and to support relevant contact-based functionality.

## Call Screening

GateCall uses Android Call Screening APIs to identify and locally filter incoming calls.

## Battery Optimization Exemption

GateCall may request a battery optimization exemption so Android does not interrupt background call protection functionality.

## No Account Required

GateCall does not require account creation, login, or cloud synchronization.

## No Advertising

GateCall does not include advertising SDKs, third-party advertising, behavioral advertising, or ad tracking.

## No Data Sale

GateCall does not sell user information or personal data, including contacts and SMS/MMS information.

## Carrier Limitations

GateCall blocks calls locally on the Android device. Some telecom carriers may still route blocked calls to voicemail depending on carrier infrastructure and provider behavior.

SMS/MMS delivery, carrier charges, and message transport depend on the user's mobile network and carrier.

## User Control

Users may:

- Disable call protection
- Remove blocked numbers
- Clear blocked activity history
- Choose whether to import existing SMS/MMS history
- Change the default SMS application through Android settings
- Uninstall GateCall

Message and attachment deletion behavior depends on the application's available messaging functions and Android's handling of message data. Uninstalling the application does not necessarily remove copies of messages held by carriers, recipients, or other messaging applications.

## Data Retention

Blocked activity history is stored locally on the device and limited to the latest 500 events.

SMS/MMS messages, imported history, and supported attachments are stored locally. This policy does not claim a fixed automatic deletion period for messaging data.

## Security

GateCall uses Android platform security features and local device storage protections. Users should protect access to their devices using Android's available screen-lock and security settings.

## Changes to This Policy

This Privacy Policy may be updated when GateCall's functionality or data practices change. The last-updated date at the top identifies the current revision.

## Contact

Developer: Liviu Damian  
Application: GateCall
