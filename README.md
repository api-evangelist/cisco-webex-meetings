# Cisco Webex Meetings (cisco-webex-meetings)

Cisco Webex Meetings is the meetings-focused subset of the Webex collaboration platform, providing scheduling, hosting, recording, transcription, and meeting administration capabilities through the Webex REST API. Authentication uses OAuth 2.0 access tokens, personal access tokens, or service apps and all endpoints respond with JSON. The legacy XML API remains available for deep integrations and enterprise scenarios that pre-date the REST surface.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cisco-webex-meetings/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cisco-webex-meetings/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Collaboration
- Communications
- Enterprise
- Meetings
- Video Conferencing

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-23

## APIs

### Webex Meetings API

The Webex Meetings API enables scheduling, updating, deleting, and listing of Webex meetings. Endpoints support recurring meetings, meeting templates, and host delegation. Authentication uses OAuth 2.0 bearer tokens or personal access tokens.

- **Human URL:** [https://developer.webex.com/docs/api/v1/meetings](https://developer.webex.com/docs/api/v1/meetings)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Conferencing
- Meetings
- Scheduling
- Video

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/meetings)
- [Authentication](https://developer.webex.com/docs/getting-started#accounts-and-authentication)
- [Postman Collection](collections/cisco-webex-meetings.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-webex-meetings.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Meeting Invitees API

Manage invitee lists for scheduled Webex meetings. Endpoints support adding, updating, and removing meeting invitees and bulk-inviting attendees by email.

- **Human URL:** [https://developer.webex.com/docs/api/v1/meeting-invitees](https://developer.webex.com/docs/api/v1/meeting-invitees)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Attendees
- Invitees
- Meetings

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/meeting-invitees)
- [Postman Collection](collections/cisco-webex-meetings.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-webex-meetings.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Meeting Participants API

List and update participants in active or completed Webex meetings. Supports admin-mute, lobby admit, and participant removal operations during in-progress meetings.

- **Human URL:** [https://developer.webex.com/docs/api/v1/meeting-participants](https://developer.webex.com/docs/api/v1/meeting-participants)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Attendees
- Participants
- Real-Time

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/meeting-participants)
- [Postman Collection](collections/cisco-webex-meetings.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-webex-meetings.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Meeting Preferences API

Manage host meeting preferences including personal room URLs, audio defaults, scheduling templates, and site preferences.

- **Human URL:** [https://developer.webex.com/docs/api/v1/meeting-preferences](https://developer.webex.com/docs/api/v1/meeting-preferences)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Personal Room
- Preferences
- Settings

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/meeting-preferences)
- [Postman Collection](collections/cisco-webex-meetings.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-webex-meetings.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Recordings API

List and manage meeting recordings. Provides access to recording details, download links, and metadata, with separate endpoints for admin and compliance officer access.

- **Human URL:** [https://developer.webex.com/docs/api/v1/recordings](https://developer.webex.com/docs/api/v1/recordings)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Compliance
- Media
- Recordings
- Storage

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/recordings)
- [Postman Collection](collections/cisco-webex-meetings.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-webex-meetings.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Meeting Transcripts API

Retrieve and manage meeting transcripts including download endpoints for VTT and TXT transcript formats. Supports compliance officer access for governance workflows.

- **Human URL:** [https://developer.webex.com/docs/api/v1/meeting-transcripts](https://developer.webex.com/docs/api/v1/meeting-transcripts)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Accessibility
- AI
- Captions
- Transcripts

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/meeting-transcripts)
- [Postman Collection](collections/cisco-webex-meetings.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-webex-meetings.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Meeting Q and A API

Retrieve questions and answers from Webex meetings and webinars for engagement reporting and post-event follow-up workflows.

- **Human URL:** [https://developer.webex.com/docs/api/v1/meeting-qanda](https://developer.webex.com/docs/api/v1/meeting-qanda)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Engagement
- Q and A
- Webinars

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/meeting-qanda)
- [Postman Collection](collections/cisco-webex-meetings.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-webex-meetings.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Meeting Polls API

Retrieve polls and poll responses from Webex meetings and webinars for engagement analytics and post-event reporting.

- **Human URL:** [https://developer.webex.com/docs/api/v1/meeting-polls](https://developer.webex.com/docs/api/v1/meeting-polls)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Engagement
- Polls
- Surveys

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/meeting-polls)
- [Postman Collection](collections/cisco-webex-meetings.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-webex-meetings.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex Meeting Chats API

Retrieve chat transcripts from completed Webex meetings for compliance and post-meeting reporting.

- **Human URL:** [https://developer.webex.com/docs/api/v1/meeting-chats](https://developer.webex.com/docs/api/v1/meeting-chats)
- **Base URL:** `https://webexapis.com/v1`

#### Tags

- Chat
- Compliance
- Meetings

#### Properties

- [Documentation](https://developer.webex.com/docs/api/v1/meeting-chats)
- [Postman Collection](collections/cisco-webex-meetings.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-webex-meetings.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Webex XML API

The Webex XML API is the legacy SOAP-style interface for deep integration with Webex Meetings. It supports site administration, user provisioning, and meeting management for scenarios that pre-date the REST API.

- **Human URL:** [https://developer.cisco.com/docs/webex-xml-api-reference-guide/](https://developer.cisco.com/docs/webex-xml-api-reference-guide/)

#### Tags

- Enterprise
- Legacy
- SOAP
- XML

#### Properties

- [Documentation](https://developer.cisco.com/docs/webex-xml-api-reference-guide/)
- [Postman Collection](collections/cisco-webex-meetings.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-webex-meetings.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/webex)
- [Portal](https://developer.webex.com/)
- [Documentation](https://developer.webex.com/docs/meetings)
- [Getting Started](https://developer.webex.com/docs/getting-started)
- [Authentication](https://developer.webex.com/docs/integrations)
- [S D Ks](https://developer.webex.com/docs/sdks)
- [Webhooks](https://developer.webex.com/docs/webhooks)
- [Rate Limits](https://developer.webex.com/docs/api-rate-limits)
- [Changelog](https://developer.webex.com/docs/api/changelog)
- [Status Page](https://status.webex.com/)
- [Support](https://developer.webex.com/support)
- [Blog](https://developer.webex.com/blog)
- [Community](https://community.cisco.com/t5/webex-developers/bd-p/4416j-disc-dev-webex)
- [Terms of Service](https://www.cisco.com/c/en/us/about/legal/cloud-and-software/end-user-license-agreement.html)
- [Privacy Policy](https://www.cisco.com/c/en/us/about/legal/privacy-full.html)
- [JSON-LD](json-ld/cisco-webex-meetings-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/cisco-webex-meetings-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
