---
title: LunaGmail Privacy Policy
---

# LunaGmail Privacy Policy

Last updated: September 14, 2026

LunaGmail is a personal, single-user application operated by the Gmail account owner on the owner's private computer.

## Google user data accessed

LunaGmail requests Gmail permissions that allow it to read selected email messages, view and modify Gmail labels, and compose and send email. The application is operationally restricted to the account owner's private workflows.

For automated incoming-mail processing, LunaGmail reads only messages that the account owner intentionally places under the designated `LunaWorld/Incoming` label. It does not open links or download attachments as part of that workflow. After successful processing, it moves those messages to the designated processed label.

For outgoing mail, LunaGmail is configured to send task reminders, processing summaries, and operational alerts only from and to the same authorized Gmail account.

## Use of Google user data

Selected message metadata and text are used only to create summaries for the account owner and to identify explicitly stated action items and dates. Gmail labels are modified only to operate the designated incoming-message workflow. Compose access is used only to send the owner's reminders, summaries, and operational alerts.

LunaGmail does not use Google user data for advertising, marketing, profiling, sale, or development or training of general-purpose artificial intelligence models.

## AI-assisted summarization and limited sharing

When the account owner uses the incoming-message summarization workflow, selected message metadata and text are transmitted to OpenAI's Codex service solely to generate the requested summaries. Attachments are not transmitted by this workflow. OpenAI processes that data as a service provider under the terms and data controls applicable to the account owner's OpenAI service.

Google user data is not otherwise sold, rented, publicly disclosed, or shared with unrelated third parties. Access by humans is not permitted except with the account owner's affirmative consent, when necessary for security or abuse investigation, to comply with applicable law, or after aggregation and anonymization for internal operations where the data cannot identify an individual.

## Local storage and security

OAuth credentials are stored locally in access-controlled files on the account owner's private computer. LunaGmail stores limited local workflow state, including Gmail message identifiers and the identifiers of generated summary messages, to avoid duplicate processing. It does not maintain a separate general archive of source-message bodies.

Temporary files used to produce summaries are removed after processing. Messages and generated summaries remain subject to the Gmail account owner's normal Gmail storage and deletion settings.

## Retention and deletion

Local workflow state is retained only while needed to operate and recover the designated workflow. The account owner may delete that local state and locally stored OAuth credentials at any time. Deleting local state does not itself delete messages from Gmail.

The account owner controls retention and deletion of source messages and generated summaries through Gmail. The application does not automatically delete source messages; successful processing changes their designated workflow label.

## Revoking access

The account owner may revoke LunaGmail's access at any time through Google Account security settings. The account owner may also disable the local scheduled jobs and delete the locally stored OAuth token.

This application's use and transfer to any other app of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.

## Contact

Questions or deletion requests may be submitted through the [magic-luna GitHub profile](https://github.com/magic-luna).

[Back to LunaGmail](./)

