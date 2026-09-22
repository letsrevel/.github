# Revel

**Revel is an open-source event management, ticketing and membership platform for communities, clubs, independent venues and independent artists.**

[![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)](https://github.com/letsrevel/revel-backend/blob/main/LICENSE)
[![Docs](https://img.shields.io/badge/docs-docs.letsrevel.io-blue?style=for-the-badge)](https://docs.letsrevel.io)
[![Discord](https://img.shields.io/badge/Discord-Join%20us-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/Rnwbzuvxvn)

<p align="center">
  <img src="https://raw.githubusercontent.com/letsrevel/revel-backend/main/docs/screenshots/event-detail-page.png" alt="A Revel event page with cover art, ticket availability and a buy button" width="800"/>
</p>

Revel sells tickets, recurring memberships and series passes, with seat maps, attendee screening and EU VAT invoicing.
Ticket money goes straight to the organizer's own Stripe account, and buyers pay the ticket price with no service fee on top.
Use the hosted version at letsrevel.io, or run the MIT-licensed code on your own server.

The features, fees and a comparison with pretix and Hi.Events are in the [main README](https://github.com/letsrevel/revel-backend#readme).

## Try it

- **Demo:** [demo.letsrevel.io](https://demo.letsrevel.io). Pick a test account on the login page (password `password123`). Data resets every night at midnight CET. No real email is sent; outgoing mail shows up at [mailpit.letsrevel.io](https://mailpit.letsrevel.io).
- **Hosted:** [letsrevel.io](https://letsrevel.io)
- **Self-host:** `git clone https://github.com/letsrevel/infra && cd infra && ./setup.sh` ([guide](https://docs.letsrevel.io/self-hosting/))
- **Docs:** [docs.letsrevel.io](https://docs.letsrevel.io)
- **Community:** [Discord](https://discord.gg/Rnwbzuvxvn)

## Repositories

- [revel-backend](https://github.com/letsrevel/revel-backend): the Django API and the main project page
- [revel-frontend](https://github.com/letsrevel/revel-frontend): the SvelteKit web app
- [infra](https://github.com/letsrevel/infra): Docker Compose deployment and the `setup.sh` wizard
- [.github](https://github.com/letsrevel/.github): this organization profile

## License

MIT. See [LICENSE](https://github.com/letsrevel/revel-backend/blob/main/LICENSE).
