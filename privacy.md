---
title: Privacy Policy - Poppy Assistant
---

# Privacy Policy: Poppy Assistant

_Last updated: 13 October 2026_

Poppy Assistant is a personal tool built and used by one person, its owner, Chris
Matcham. It is not offered to the public. This policy explains what data it
accesses, why, and how that data is handled.

## What data the app accesses

With the owner's explicit consent through Google's OAuth screen, the app can access
the owner's own:

- **Gmail:** message and thread content, metadata (sender, recipients, subject,
  date), and labels. It can create labels and apply or remove them. Scopes:
  `gmail.readonly`, `gmail.labels`.
- **Google Calendar:** the list of calendars, events and their details, and
  free/busy information. It can create, update, and respond to events. Scopes:
  `calendar.calendarlist.readonly`, `calendar.events`, `calendar.events.readonly`,
  `calendar.events.freebusy`.

The app does not access any other Google data and does not access anyone else's
account.

## How the data is used

Data is accessed only when the owner asks the assistant to do something, such as
searching mail or checking a schedule. It is used solely to answer that request
and to carry out the action the owner asked for. It is not used for advertising,
profiling, or any other purpose, and it is never sold.

## Third-party processing

To answer requests, relevant excerpts of email and calendar content are sent as
part of a prompt to a large language model, through the OpenRouter API. Before
leaving the owner's server, a gateway redacts common personal identifiers (email
addresses, phone numbers, social security numbers, credit card numbers). The data
is sent only to generate a response for the owner. The app's operator does not use
Google user data to train or improve any AI model, and does not share it with
anyone else.

## Storage and retention

- Google user data is **not stored** by the app beyond the time needed to answer a
  request. It is not copied into a database.
- The assistant keeps a conversation history on the owner's private server so the
  owner can continue earlier conversations. That history may contain excerpts of
  Gmail or Calendar content the owner asked about. It stays on the owner's server
  and can be deleted by the owner at any time.
- The Google OAuth refresh token is stored on the owner's private server in a file
  readable only by the owner's account. Short-lived access tokens are refreshed
  automatically and are never shared outside the server.

## Security

Credentials are held by a gateway on a private server and are not given to the
assistant itself. An allow-list restricts which Gmail and Calendar actions are
possible: there is no tool for sending or deleting mail or deleting events.

## Sharing and disclosure

Google user data is not shared with, sold to, or disclosed to any third party,
other than the language-model processing described above, which is needed to
provide the app's single function for its owner. It is not disclosed except as
required by law.

## Revoking access and deleting data

The owner can revoke the app's access at any time at
<https://myaccount.google.com/permissions>. Revoking access invalidates the stored
token. Conversation history and any stored tokens can be deleted from the server on
request by the owner.

## Google API Services User Data Policy

Poppy Assistant's use and transfer to any other app of information received from
Google APIs adheres to the
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
including the Limited Use requirements.

## Changes

If this policy changes, the date above will be updated.

## Contact

Questions about this policy: cjmatcham@hotmail.co.uk
