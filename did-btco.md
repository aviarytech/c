# BTCO: decentralized identifiers on Bitcoin

**Project:** did:btco  
**Team:** Aviary Tech  
**Context:** November 2023 DIF Hackathon  
**Devpost creator:** Brian Richter

This case study summarizes the original [BTCO Devpost submission](https://devpost.com/software/did-btco) and [Aviary Tech's DIF Hackathon README](https://github.com/aviarytech/dif-hackathon/blob/master/README.md). It describes the work reported for the hackathon, not a new assessment of the implementation's current status.

## Goal and approach

BTCO explored identity management on Bitcoin using Ordinal Theory and inscriptions, without a sidechain or additional token. The Devpost submission describes a command-line tool for creating, resolving, updating, and deactivating DIDs. DID Documents are inscribed on satoshis; the implementation uses the `ord` wallet's command-line tools and inscription index. Resolution is also exposed through a Universal Resolver driver.

## Delivered work

The [hackathon README](https://github.com/aviarytech/dif-hackathon/blob/master/README.md) records:

- A working [DID registration and resolution implementation](https://github.com/aviarytech/btc-ordinal-dids).
- A [did:btco Universal Resolver driver](https://github.com/aviarytech/uni-resolver-driver-did-btco), added to the Universal Resolver.
- A simpler [did:btco method](https://github.com/ordinalsreserve/did-btco), using Ordinals reinscription and metadata.
- Use of DIDLint, the Universal Resolver, and the DID Resolution Specification.

## Challenges and learning

The [Devpost account](https://devpost.com/software/did-btco) describes adapting a complicated initial design as Ordinals capabilities evolved. New features enabled a simpler approach and on-ledger data compression. The team reports learning from wallet integration, building a resolver driver, validating DID Documents with DID Lint, and applying the DID Registration specification.

## Follow-on work recorded at submission

These were proposed next steps, not claims of completed features:

- CLI-assisted DID Document creation ([issues 6](https://github.com/aviarytech/btc-ordinal-dids/issues/6) and [9](https://github.com/aviarytech/btc-ordinal-dids/issues/9)).
- A shorter representation to reduce storage fees ([method issue 2](https://github.com/ordinalsreserve/did-btco/issues/2)).
- Support for `equivalentId` ([issue 11](https://github.com/aviarytech/btc-ordinal-dids/issues/11)).
- Block information in resolution metadata ([issue 13](https://github.com/aviarytech/btc-ordinal-dids/issues/13)).
- Resolution at a specified date and time ([issue 10](https://github.com/aviarytech/btc-ordinal-dids/issues/10)).

## Attribution and sources

- [BTCO on Devpost](https://devpost.com/software/did-btco), credited to Brian Richter and submitted to the Decentralized Identity Foundation Hackathon.
- [Aviary Tech DIF Hackathon README](https://github.com/aviarytech/dif-hackathon/blob/master/README.md), which dates the implementation work to November 2023.

Adapted for Cases on November 4, 2026. Original sources remain in place.
