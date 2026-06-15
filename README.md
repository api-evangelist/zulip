# Zulip (zulip)

Zulip is an open-source team chat application with a unique topic-based threading model. Zulip's APIs power the web and mobile apps and provide REST endpoints, incoming webhooks, outgoing webhooks, and event-driven integrations to connect Zulip with external services.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/zulip/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/zulip/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Collaboration
- Messaging
- Team Chat
- Webhooks

## Timestamps

- **Created:** 2026-01-02
- **Modified:** 2026-05-29

## APIs

### Zulip REST API

The Zulip REST API powers the Zulip web and mobile apps. It provides programmatic access to messages, streams, users, organizations, and all other Zulip functionality. Anything you can do in Zulip, you can do with the REST API.

- **Human URL:** [https://zulip.com/api/rest](https://zulip.com/api/rest)

#### Tags

- Messaging
- REST
- Team Chat

#### Properties

- [Documentation](https://zulip.com/api/rest)
- [Reference](https://zulip.com/api/)
- [AsyncAPI](asyncapi/zulip-events-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/zulip.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zulip.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zulip Events API

The Zulip Events API delivers real-time updates from a Zulip server to a client via an HTTPS long-poll. Clients register an event queue via POST /api/v1/register, then call GET /api/v1/events with the returned queue_id and last_event_id to receive batches of typed events covering messages, reactions, subscriptions, presence, typing, channel/stream changes, user and organization updates, custom emoji, alert words, message-flag changes, drafts, scheduled messages, reminders, user groups, and system heartbeat/restart signals.

- **Human URL:** [https://zulip.com/api/get-events](https://zulip.com/api/get-events)

#### Tags

- Events
- Long Polling
- Real Time
- Team Chat

#### Properties

- [Documentation](https://zulip.com/api/get-events)
- [Reference](https://zulip.com/api/real-time-events)
- [AsyncAPI](asyncapi/zulip-events-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/zulip.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zulip.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zulip Webhooks

Zulip supports both incoming webhooks (allowing third-party services to push data to Zulip) and outgoing webhooks (allowing Zulip to send HTTP POST payloads to external services when messages are sent).

- **Human URL:** [https://zulip.com/api/incoming-webhooks-overview](https://zulip.com/api/incoming-webhooks-overview)

#### Tags

- Events
- Integrations
- Webhooks

#### Properties

- [Documentation](https://zulip.com/api/incoming-webhooks-overview)
- [Reference](https://zulip.com/api/outgoing-webhooks)
- [Postman Collection](collections/zulip.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zulip.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/zulip-by-kandra-labs)
- [Website](https://zulip.com/)
- [Documentation](https://zulip.com/api/)
- [Integrations](https://zulip.com/api/integrations-overview)
- [GitHub Organization](https://github.com/zulip)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
