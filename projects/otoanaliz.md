# OtoAnaliz — Used-car listing decision support

**Automotive technology · Research workflows · API development**

[← Back to portfolio](../README.md)

## Product challenge

An online vehicle listing gives a buyer a partial picture. Useful decision support must organize available facts while clearly identifying what cannot be verified from the listing itself.

## Project overview

OtoAnaliz is a Turkish-first, bilingual workspace for researching listings from Turkish vehicle marketplaces. It aims to combine listing facts, price heuristics, saved analyses, and negotiation notes.

## Selected implementation work

- Source-page import and structured listing extraction when pages are accessible.
- Saved analysis records, favorites, notes, and dashboard summaries.
- An API-backed TypeScript application with PostgreSQL persistence.
- Explicit unavailable-data and import-error states instead of invented inspection records.
- Turkish/English experience and responsive layouts.

**Technology:** TypeScript, React, Express, PostgreSQL, Drizzle ORM, OpenAPI, Zod.

## Current status

This is a project under development. External marketplace anti-bot restrictions can prevent automated import; estimated prices are guidance, not formal valuations or vehicle-history verification. The source repository is private.

**What this project demonstrates:** building decision support around reliable data boundaries, transparent uncertainty, and a practical buyer workflow.
