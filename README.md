# RewaPay Cray Integration

Standalone repository for building the Cray integration module for RewaPay.

## What this is

A NestJS module (TypeScript, Node.js 22.x) that covers the Cray capabilities RewaPay needs: virtual accounts, funding, bank lookup and transfers, status tracking, and webhooks. It will be integrated into RewaPay's existing API by the RewaPay team once it is complete.

## Start here

1. Read [docs/INTERFACE_CONTRACT.md](docs/INTERFACE_CONTRACT.md). It defines the operations and events the module exposes.
2. Write your plan into `STATUS.md`, as the first entry. Cover the Cray products and endpoints per capability, your proposed interface changes, your data model, your webhook design, and your test plan.
3. Build and test against Cray's **test** environment only.

## Repository rules

- Do not commit `.env` files, keys, tokens, or any secret. Use `.env.example` with placeholder values only.
- Document environment variable names in the README, never their values.
- Keep `STATUS.md` up to date with each push: what is built, what works, what does not, what you are blocked on, and next steps.
- Push as you go, not only at the end.
- Tell RewaPay when you believe the module is complete. RewaPay reviews the code for security and then integrates it.

## Status

See [STATUS.md](STATUS.md).
