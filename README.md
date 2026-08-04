# Cisco Webex Meetings (cisco-webex-meetings)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
