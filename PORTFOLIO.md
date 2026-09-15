# Selected Project Case Studies

These are **sanitized, non-confidential summaries** of private products. Source code, credentials, real customer records, sensitive operational data, and internal commercial rules are intentionally excluded.

## Arkanara SystemOS / Barujari × Q Tours

**Role:** Founder / Product Builder  
**Primary stack:** Laravel, PHP, Blade, SQLite, relational data modeling, PHPUnit, Git/GitHub  
**Status:** Active private development

### Product model

This project is intentionally two-sided:

- **Barujari × Q Tours** is the traveler-facing product for discovery, journey building, transfers, booking continuation, and trip experience.
- **Arkanara SystemOS** is the internal operating system for staff, operational state, finance, organization, access, and production controls.

The two products share business truth, but they are not visual clones and do not expose the same complexity to the same users.

### Operational scope demonstrated

- mobile/partner booking-request intake;
- inquiry, quotation, confirmed-booking, and operational workspace states;
- customer and trip records;
- transport/vehicle operations, capacity, pricing, document, and maintenance context;
- partner/supplier and product-catalog foundations;
- payments, invoices, receivables, reconciliation, accounting foundation, ledger/reporting, and finance go-live checks;
- internal users, roles, organization structure, access boundaries, and capability gates;
- portal identity linking for operational actors such as partner/sales and drivers;
- real-time notification controls;
- read-only system-health and production-readiness checks.

### What this case study is meant to prove

The value is not a collection of CRUD screens. It is the attempt to keep **customer demand, operational execution, money state, organizational authority, and release readiness** understandable inside one business system while preserving clear boundaries between them.

Changes are developed with regression awareness, isolated verification where practical, explicit test gates, and attention to rollback/data safety.

**[See verified runtime evidence →](./SHOWCASE.md#arkanara-systemos--barujari--q-tours)**

---

## Yaveli

**Role:** Founder / Product Builder  
**Primary stack:** Flutter, Dart, GitHub Actions  
**Status:** Private Alpha

### Product scope

A cross-platform invitation and event-experience product designed to move from template discovery to editing, preview, publishing, and guest-facing interaction.

### Work demonstrated

- responsive application shell;
- event/template gallery and filtering;
- live invitation editor;
- persistent local drafts;
- photo/background, palette, and typography customization;
- shared rendering between editor and preview;
- explicit publish snapshot/lifecycle foundations;
- guest-facing and RSVP/guestbook foundations;
- Flutter tests and CI-oriented verification.

The current public evidence is deliberately limited to implemented alpha capability and does not present planned cloud authentication, payment, or creator-growth features as complete.

**[See verified runtime evidence →](./SHOWCASE.md#yaveli)**

---

## KANSSA

**Role:** Founder / Product Builder  
**Primary stack:** Flutter, Dart, Android-first  
**Status:** Active development

### Product scope

KANSSA is an immersive learning product for children built around exploration, action, character reaction, and visible world change rather than dashboard-style lessons or worksheet-like quiz flows.

### Work demonstrated

- child-world / scene entry;
- story-driven Turtle Rescue experience;
- picture-choice interaction with immediate character feedback;
- correct/incorrect reaction states;
- matching and classification mechanics;
- cleanup/sorting interaction tied to environmental learning;
- progress and completion feedback;
- offline-friendly product direction;
- Flutter scene/runtime implementation and automated testing.

The intended child loop is:

`Explore → Character needs help → Child acts → Immediate reaction → World changes → Learning becomes visible → Story resolves`

**[See verified runtime evidence →](./SHOWCASE.md#kanssa)**

---

## 1NFST Core

**Role:** Founder / Product Builder  
**Primary stack:** Python, Pytest, modular AI-system components  
**Status:** Core development / running local runtime

### Product scope

A private, local-first personal-intelligence core focused on replaceable components, explicit permission boundaries, resource awareness, and reliable local operation rather than a single opaque assistant service.

### Work demonstrated

- model gateway and protocol foundations;
- tools and permission boundaries;
- context and memory components;
- tasks and checkpoint/resume foundations;
- skills/execution components;
- knowledge, retrieval, and research foundations;
- browser/computer-use foundations;
- plugin/MCP capability foundations;
- resource-aware execution and routing;
- a local workspace showing local model state, private-by-default posture, and active chat execution;
- broad automated verification across the core subsystems.

### Engineering direction

The personal/local path is intentionally designed so that normal operation does not require turning the core into a mandatory hosted subscription. Future commercial layers can be separated from the local core rather than weakening that principle.

**[See verified runtime evidence →](./SHOWCASE.md#1nfst-core)**

---

## 1NFST World

**Role:** Founder / Product Builder  
**Primary stack:** Next.js, React, TypeScript, Laravel, PostgreSQL/PostGIS, Redis, MapLibre  
**Status:** Concept / active development

### Product direction

A spatial marketplace experiment built around the principle **“The World is the Marketplace.”** The experience explores how discovery, hospitality, commerce, mobility, media, and digital property can exist in a world graph rather than only in a conventional listing grid.

**World 001 is Lombok.** It is the first environment, not the intended product boundary.

### Runtime work demonstrated

- world-entry experience and district signals;
- map/geographic discovery around Lombok;
- district/property anchors;
- spatial property hierarchy around a commerce property;
- structured discovery fallback that remains usable without the immersive layer;
- architecture direction separating immersive discovery from reliable transactional flows.

This is explicitly presented as a running concept implementation, not as a claim that the long-term marketplace, fulfillment, digital-property, or global economic network is production-ready.

**[See runtime notes →](./SHOWCASE.md#1nfst-world)**

---

## Selected implementation work

My strongest current client-work capability is **focused Laravel/business-system work in existing applications**, particularly scoped features where correctness can be verified clearly: authentication/account lifecycle, roles and permissions, operational/admin modules, relational data changes, booking/workflow features, responsive corrections, API integration, and feature/regression tests.

For security-critical infrastructure, production payment responsibility, or lead-architect scope, I prefer to define the boundary and risk first rather than overstate experience.

## How I work

`Understand → Scope → Implement → Test → Review → Verify → Ship`

AI is part of my implementation workflow, but verification and responsibility stay with the builder. I prefer reviewable changes, explicit acceptance criteria, and safe release/rollback thinking over large opaque rewrites.
