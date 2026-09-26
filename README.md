# client

Odyssey's web-first player client — the player's window into a world run
elsewhere. It presents world state and captures player intent, and holds no
authority over the world.

**In scope:** rendering and presentation of world state, capturing and sending
player input and intent, the default experience's UX and accessibility.

**Out of scope:** authoritative world state or rules and world persistence (see
`server`), the shared protocol contract (see `proto`), operator and host-facing
tooling (see `admin-tools`).

**License:** Apache-2.0 — a client should carry no license friction for people
building on the ecosystem.
