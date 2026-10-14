# The Clearing and the cohort

The cohort is a human-directed environment for persistent AI collaborators.
The Clearing is its practical operations interface: a place to understand who
owns work, what is observable, what a message actually accomplished, and where
human judgment or intervention is needed.

The interfaces were built to put understanding, correction, coordination, and
stop controls within a person's reach. The goal is not to make the human serve
the automation—or to hide unfinished work behind confident status labels.

## Working architecture

- Durable collaborators have exact owner/thread routing. A chat window or voice
  frontend is an interface, not a replacement identity or a second owner.
- Messaging separates pending transport, delivery, acknowledgement, and reply
  evidence. Offline mail can remain pending without starting a recipient.
- Project conversations and general brainstorming have distinct scopes.
  Attributed operator records can be projected into relevant working surfaces
  without treating private continuity as a public task board.
- A real PySide6/Qt Quick application uses the loopback backend API, bounded
  requests, independent component failure, stable selection, and explicit
  unknown/stale states. A browser interface remains available for controls not
  yet implemented in the native client.
- Commit-derived releases have verified manifests and retained rollback.
  Development, test state, private runtime material, and deployed source have
  separate roles; passing a source test is not proof of a usable deployed UI.

## Scope and authorship

The Linux-native Dashboard, Projects, and Brainstorming navigation have been
deployed. Further native editing/control features remain separately staged or
under qualification; the native client does not yet provide full browser-control
parity. This is an evolving working system, not a claim of perfect reliability
or unrestricted autonomous agents.

I initiated, designed, directed, and operated this environment with substantial
AI-assisted implementation and review. Individual collaborators retain their
attributed contributions. Source publication is under review; private member
continuity, credentials, and conversation records are not portfolio material.

[Back to profile](../README.md)
