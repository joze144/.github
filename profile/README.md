
<p align="center">
  <img src="img/holaplex-avatar.png" width="250px" />
</p>

<h2 align="center">The best way to experiment & explore with NFTs.</h2>

With Hub and developer APIs, you can quickly and easily launch NFT campaigns, mint digital collectibles, run loyalty programs, and more. No matter what industry you're in, we're here to help you see what’s possible.

## Getting Started

Visit our docs site at [https://docs.holaplex.dev](https://docs.holaplex.dev) to read useful guides and review our API reference.

## Services Catalogue

Hub is a collection of loosely coupled microservices that emits and process messages through a shared [Redpanda](https://redpanda.com/) cluster, a Kafka compatible streaming data platform. The services also expose their own [GraphQL API](https://graphql.org/) that are stitched together into a single API endpoint using [Apollo Federated Router](https://www.apollographql.com/docs/router/).

- [Hub Console](https://github.com/holaplex/hub) - Friendly management console for interacting with the Hub API.
- [Hub NFTs](https://github.com/holaplex/hub-nfts) - Multi-chain minting and indexing of NFT campaigns.
- [Hub Orgs](https://github.com/holaplex/hub-orgs) - Catalogue of all organizations, projects, and memberships for Hub. 
- [Hub Treasuries](https://github.com/holaplex/hub-orgs) - Create crypto wallets using [Fireblocks](https://www.fireblocks.com/) and submit blockchain transactions using Hub custodial wallets.
- [Hub Customers](https://github.com/holaplex/hub-customers) - Customer references that receive a treasury for storing crypto wallets.
- [Hub Permissions](https://github.com/holaplex/hub-permissions) - Contains all permission relationships for the Hub. Leverages Ory Keto.
- [Hub Identities](https://github.com/holaplex/hub-identities) - Manages all identities for Hub. GraphQL API for Ory Kratos.
- [Hub Credentials](https://github.com/holaplex/hub-credentials) - Create API credentials for Hub. GraphQL API for Ory Hydra. 
- [Hub Webhooks](https://github.com/holaplex/hub-webhooks) - Receive webhook events as Hub resources change using [Svix](https://github.com/svix/svix-webhooks/) webhooks service.

## Reference Projects

A few reference project that demonstrate how to work with Hub to create unique NFT campaigns.

- [Eluvio SxSW Scavenger Hunt](https://github.com/holaplex/eluvio-sxsw) - At SxSW 2023 Holaplex partnered up with Eluvio to offer attendees a scavenger hunt where they scanned access badges using NFC to collect NFT keys that unlocked viewing of a video demo of Holaplex Hub.

  Showcases:
    - Custodial Wallets
    - NFT Edition minting through API
    - Token gated content

## Open Source

Holaplex is committed to building in the open. All of our services have been publicly viewable from Day 1 and licensed under GNU Affero General Public License v3.0.
