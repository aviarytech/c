# VAI: provenance for AI conversations

**Project:** Verifiable AI (VAI)  
**Devpost creator:** Brian Richter  
**Context:** Decentralized Identity Foundation Hackathon 2024  
**Recognition:** Cheqd 1st Place; Anonyome Labs 2nd Place, as listed on [Devpost](https://devpost.com/software/vai).

## The case

VAI explored making AI conversations easier to inspect through signed records of prompts, responses, and model information. The [hackathon entry](https://devpost.com/software/vai) describes a chatbot using verifiable credentials, with cheqd DID-Linked Resources for publishing public conversations. It links directly to [aviarytech/vai](https://github.com/aviarytech/vai), establishing the connection between the submission and source repository.

The submission reports a working prototype. It identifies conversation context, privacy, interoperability, and verification usability as challenges. Its proposed follow-on work includes additional model integrations, zero-knowledge proofs, browser and messaging plugins, and a public API. These are historical plans, not verified completed features.

## Repository design

The [repository README](https://github.com/aviarytech/vai/blob/master/README.md) describes chat with automatic credential creation, credential management and verification, batch export and verification, and a Public Square for browsing shared interactions.

It documents a React, Vite, and TypeScript frontend with a Bun/Elysia backend and MongoDB persistence. The Devpost narrative instead names Express for the backend. This case preserves that distinction rather than treating the two descriptions as an independently verified implementation inventory.

## Scope of the evidence

This is an attributed account of the hackathon submission and repository documentation, reviewed on November 4, 2026. The application, live demo, performance, and security properties were not tested for this case study.

Credential verification should be understood in terms of the issuer, signed claims, and trust assumptions. This case does not establish the factual correctness of model answers, independent proof of model execution, or an immutable record of every conversation.

## Sources

- [Original VAI Devpost entry](https://devpost.com/software/vai): creator, event, awards, project account, and linked demo.
- [VAI source repository](https://github.com/aviarytech/vai) and [README](https://github.com/aviarytech/vai/blob/master/README.md): architecture and documented features.
- [DIF's 2024 winners announcement](https://blog.identity.foundation/dif-2024-hackathon-winners-announced-2/): organizer context and link to the event's Devpost gallery.

Summarized for Cases. The original submission and source repository remain in place.
