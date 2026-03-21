# Homelab HA Energy Management Agent Guide

## Scope

This repo holds Home Assistant energy-management documentation and YAML tied to the current homelab setup.

## Operating Rules

- Keep energy logic readable and tied to current entities, dashboards, and packages.
- Preserve existing naming and dashboard structure unless a change requires a real redesign.
- Do not place secrets or environment-specific credentials in tracked files.
- Keep documentation and YAML in sync.

## Maintenance Expectations

- Treat this repo as the maintained source of truth for energy-management content that is worth preserving.
- If a change belongs in the main `ha-config` repo, update that repo and document the dependency here instead of copying logic.

## Change Standard

- Prefer practical improvements over broad redesign.
- Keep the repo usable by a single homelab operator without extra process overhead.