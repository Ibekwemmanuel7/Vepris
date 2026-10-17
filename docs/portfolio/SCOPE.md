# Vepris scope and portfolio boundary

Updated 17 October 2026.

Portfolio hub: [Lillie US](https://github.com/Ibekwemmanuel7/Lillie_US)

Portfolio map: [Product responsibilities](https://github.com/Ibekwemmanuel7/Lillie_US/blob/main/docs/PORTFOLIO.md)

## Domain and status

**Domain:** Southern US forestry

**Status:** Design stage; scope documented, implementation pending.

## Current baseline

The repository documents a forestry scope and proposed inspection workflow. No operational forest-monitoring service has been established.

## Planned scope

Forest-condition and canopy-change screening, drought/stress investigation support, harvest and clearing histories, replanting, vegetation recovery, storm-disturbance documentation and timberland portfolio reporting.

## Ownership and interfaces

Vepris owns the forestry decision workflow. It may consume VHAGAR fire products and Vaughan flood/coastal event products. It does not duplicate their hazard engines. Canopy change alone does not establish cause, timber volume or financial loss.

## Delivery gate

Define the buyer, decision, last useful delivery time, reference data, baseline and acceptance criteria before implementation. Outputs must carry observation and processing dates, provenance, quality, uncertainty and unavailable-data states. Customer-provided records and assessments require explicit access control. No new operational or scientific performance claim follows from adding this roadmap.

The repository owns its reusable domain code, methods, tests and domain documentation. Lillie US owns cross-product integration, shared customer workflows, portfolio configuration and product-release coordination. Do not make this repository depend on Lillie US merely to create a backlink.
