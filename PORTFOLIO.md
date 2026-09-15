# Selected Project Case Studies

This page presents **sanitized, non-confidential summaries** of selected private projects. Proprietary source code, production credentials, customer data, internal commercial rules, and sensitive operational details are intentionally not published.

The goal of this portfolio is to show the kinds of products, systems, workflows, and engineering problems I have worked on without pretending that private projects are public releases.

## Laravel Business Operations Platform

**Role:** Independent Developer / Product Builder  
**Primary stack:** PHP 8.3, Laravel 13, Eloquent, SQLite, Blade, PHPUnit, Git/GitHub

### Problems addressed

The application needed more than simple CRUD. It required internal account lifecycle controls, organization-aware access, role and permission handling, operational workflows, booking-related processes, reporting, and changes that could be introduced without casually breaking existing data or workflows.

### Work demonstrated

- organization membership and internal access boundaries;
- role-to-permission mapping and permission-aware workspace access;
- authentication and account lifecycle flows;
- relational Eloquent models and schema migrations;
- booking and operations-oriented modules;
- finance/reporting foundations;
- feature, contract, and regression-oriented tests;
- GitHub-based change history and verification workflows.

### Delivery mindset

Changes are approached with scoped implementation, isolated verification where practical, regression checks, and explicit attention to data safety rather than assuming that a successful page load proves a change is safe.

---

## Barujari / Arkanara Travel Commerce & Operations

**Role:** Founder / Product Builder  
**Primary stack:** Laravel, Blade, Eloquent, SQLite, PHPUnit, plus earlier TypeScript/React/PostgreSQL platform exploration

### Product scope

A travel technology direction that connects customer-facing discovery, booking, payment, trip access, and travel experiences with internal operations such as access control, organizational workflows, drivers, vehicles, transport, finance foundations, and operational reporting.

### Work demonstrated

- customer-facing booking and trip-oriented flows;
- authentication and access-control boundaries;
- organization, people, and operational assignment foundations;
- transport booking, driver, and vehicle workflows;
- payment and finance lifecycle foundations;
- regression-oriented verification and safe rollout gates;
- separation between customer experience and internal operations.

### Delivery mindset

The product is treated as an operating system for a real business domain rather than a collection of unrelated CRUD screens. Changes are introduced with explicit migration, verification, rollback, and data-safety thinking.

---

## Yaveli

**Role:** Founder / Product Builder  
**Primary stack:** Flutter, Dart, GitHub Actions

### Product scope

A cross-platform invitation and event-experience product designed around creating, previewing, publishing, and sharing digital event experiences.

### Work demonstrated

- Flutter application organization across app/core/features/shared layers;
- template discovery and filtering;
- live editor and preview flows;
- persistent local drafts;
- photo, background, palette, and typography customization;
- shared editor/preview rendering foundations;
- publish lifecycle foundations;
- guest-facing flow foundations;
- responsive UI work;
- automated Flutter tests and CI-oriented checks.

### Current state

The product is still in active development. The editor and local authoring experience are substantially ahead of cloud publishing, public guest flows, account infrastructure, and commercial release readiness.

---

## KANSSA

**Role:** Founder / Product Builder  
**Primary stack:** Flutter, Dart, Android-first

### Product scope

An immersive learning product for children where learning is delivered through exploration, characters, actions, consequences, and world reactions rather than conventional dashboard or worksheet-style interaction.

### Work demonstrated

- scene-based learning runtime work;
- character-driven reactions and feedback;
- child action → world reaction interaction loops;
- offline-friendly progress foundations;
- picture-choice, drag-and-drop, and matching activities;
- automated Flutter testing;
- manual device-level experience validation.

### Product principle

The child experience is treated as a world to explore rather than an LMS interface. Educational intent is embedded inside play, rescue, making, discovery, experimentation, and story progression.

---

## 1NFST AI Core

**Role:** Founder / Product Builder / Systems Research  
**Primary stack:** Python, Pytest, modular AI-system components

### Product scope

A private local-first AI core focused on modular capability boundaries rather than a single monolithic assistant runtime.

### Work demonstrated

- model gateway and protocol foundations;
- permissions and tool boundaries;
- context and memory components;
- task persistence and checkpoint/resume concepts;
- skills and execution components;
- knowledge/retrieval foundations;
- browser and computer-use foundations;
- plugin and extension foundations;
- resource-aware and model-routing work;
- broad automated test coverage across subsystems.

### Delivery mindset

AI capability is treated as something that requires permission boundaries, replaceable components, explicit contracts where practical, and extensive verification rather than uncontrolled model calls.

---

## 1NFST World

**Role:** Founder / Product Builder  
**Product direction:** Spatial marketplace / commerce platform

### Product scope

A digital-world marketplace concept where discovery, commerce, hospitality, mobility, experiences, media, digital property, fulfillment, and transactions can coexist inside a spatial experience.

### Work demonstrated

- world and spatial hierarchy concepts;
- commerce and booking foundations;
- payment-intent abstractions;
- partner and provider control concepts;
- fulfillment and mobility foundations;
- creator/storefront direction;
- separation between immersive discovery and conventional transactional UX.

---

## UTUH

**Role:** Founder / Product Research Builder  
**Product direction:** Digital trust infrastructure

### Product scope

A trust-system direction focused on identity, consent, authority, verification, credentials, risk signals, auditability, recovery, and human-controlled delegation to AI systems.

The project is still research- and architecture-heavy and is not presented here as a production-ready trust product.

---

## Selected client work I am currently best suited for

My strongest near-term client-work capability is **focused Laravel development in existing applications**, especially:

- bug investigation and fixes;
- scoped feature additions;
- authentication and account flows;
- roles and permissions / RBAC;
- CRUD/admin modules;
- Eloquent relationships and migrations;
- booking and operational workflow modules;
- responsive Blade/UI corrections;
- REST API integrations with clear documentation;
- PHPUnit feature/regression tests;
- Git/GitHub-based delivery and technical handover.

I also have hands-on product work across Flutter/Dart, Python AI systems, TypeScript/React applications, relational data modeling, and automated testing.

For larger infrastructure, security-critical systems, production payments, or lead-architect responsibilities, I prefer to define scope, dependencies, and risk carefully before committing rather than overstate experience.

## Working approach

My default approach is:

`Understand → Scope → Implement → Test → Review → Verify → Ship`

I use AI tools as part of that workflow, but generated output is treated as a draft to inspect and verify, not as proof that a change is correct.
