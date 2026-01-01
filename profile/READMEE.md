<div align="center">

# OH

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="../assets/dark/SPACE.svg">
  <source media="(prefers-color-scheme: light)" srcset="../assets/light/SPACE.svg">
  <img src="../assets/light/SPACE.svg" alt="OH Logo" width="100%">
</picture>

**A system for building functional, transactional digital spaces.**

[Website](https://o-h.systems) · [Experience](https://o-h.systems/space) · [O-OH](https://o.o-h.systems)

</div>

## About

OH develops infrastructure, software, and tooling that allow immersive environments to operate as complete products — not previews, simulations, or marketing layers. Browsing, interaction, commerce, and state all exist inside the same system.

Most digital environments treat commerce as external. You explore in-world, then get redirected to a website to actually buy. OH keeps everything inside. The focus is on making spatial experiences usable, reliable, and production-ready.

## Experience Layer

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="../assets/dark/EXP.svg">
  <source media="(prefers-color-scheme: light)" srcset="../assets/light/EXP.svg">
  <img src="../assets/light/EXP.svg" alt="Experience" width="100%">
</picture>

The real-time environment where users exist. Built in Unreal Engine with a focus on stability, performance, and native commerce UI. This is where browsing, interaction, and transactions happen — spatial interfaces designed for function, not spectacle.

Responsibilities include in-world rendering, commerce UI (cart, checkout, confirmation states), WebView integration for hosted checkout, analytics event emission, and multiplayer infrastructure.

## Design Principles

| | |
|---|---|
| **Function before presentation** | Systems over surfaces |
| **Real transactions** | Not simulations |
| **Persistence and continuity** | Minimal abstraction between user and system |

OH avoids speculative features and decorative layers. Everything built is intended to work under real conditions.

## Web

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="../assets/dark/WEB.svg">
  <source media="(prefers-color-scheme: light)" srcset="../assets/light/WEB.svg">
  <img src="../assets/light/WEB.svg" alt="Web" width="100%">
</picture>

The surfaces that connect OH to the world. The main website, streaming entry points, and the infrastructure that lets users enter experiences from any browser.

This layer handles the bridge between web platforms and real-time engines — deployment, access, and interoperability. It supports streaming distribution (cloud and self-hosted), PC build downloads, mobile adaptation, and serves as the primary entry point at [o-h.systems](https://o-h.systems).

## Core Systems

<table>
<tr>
<td width="50%" valign="top">

### Commerce Runtime
Infrastructure for in-world transactions. Cart state, checkout flow, payment processing, order confirmation, and failure handling — without external redirects.

</td>
<td width="50%" valign="top">

### Identity + Session
Persistent session layers that track user state, actions, and context across immersive experiences. Guest-to-login transitions, cross-surface state, and preference memory.

</td>
</tr>
</table>

## O-OHs

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="../assets/dark/O-OH.svg">
  <source media="(prefers-color-scheme: light)" srcset="../assets/light/O-OH.svg">
  <img src="../assets/light/O-OH.svg" alt="O-OH" width="100%">
</picture>

Conversational agents designed to operate as in-world staff. O-OHs are not chatbots — they take real actions. Product discovery, cart management, checkout initiation, failure explanation, and support handoff — native to the experience.

Every action is deterministic. If an O-OH says it added something to your cart, it actually did. The goal is assistance that feels like part of the world, not an overlay or interruption.

Currently accessible at [o.o-h.systems](https://o.o-h.systems) with voice, text, and visual interaction.

## Repositories

| Repository | Description | Language |
|------------|-------------|----------|
| [oh-sss](https://github.com/oh-systems/oh-sss) | Strategy, scope, and execution documentation | Markdown |
| [oh-web](https://github.com/oh-systems/oh-web) | Main website and experience entry | TypeScript |
| [oh-companion-frontend](https://github.com/oh-systems/oh-companion-frontend) | O-OH web client — 3D avatar, voice, lip-sync, chat | JavaScript |
| [oh-companion-backend](https://github.com/oh-systems/oh-companion-backend) | O-OH backend — LLM, session memory, voice I/O | Python |
| [e-cohm](https://github.com/oh-systems/e-cohm) | Commerce runtime API | TypeScript |

## Status

OH is under active development. Some repositories represent production systems, others are proofs of concept or internal tools. Not all projects are intended for public use.

## Philosophy

OH treats digital environments as systems, not content.

If a space cannot operate independently — remember state, process transactions, and support users — it is incomplete.

<div align="center">

**[o-h.systems](https://o-h.systems)**

</div>
