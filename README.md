# AgentOS — Contact Center Agent Dashboard

A high-fidelity UI/UX portfolio prototype of a dark-mode-first agent performance dashboard for contact centers. Built as a single self-contained HTML file — no frameworks, no build tools, no dependencies.

---

## Overview

AgentOS is a concept product designed to give contact center agents a clean, minimal interface to track their daily performance, view their schedule, and manage time off — all without the noise of legacy CRM dashboards.

The design direction is dark-mode-first, Apple-influenced minimalism using the DM Sans and DM Mono type system with a green/amber/blue accent palette.

---

## Screens

| Screen          | Description                                                                  |
| --------------- | ---------------------------------------------------------------------------- |
| **Login**       | Split-panel login with live stat preview, SSO options                        |
| **Dashboard**   | KPI cards, today's schedule timeline, this week table, alerts, activity feed |
| **Performance** | Weekly productivity, quality and efficiency tables with status indicators    |
| **Schedule**    | Week-view shift grid with tooltips, days off table, time-off and swap modals |
| **Profile**     | Agent details, employment info, contact info, evaluations grid               |

---

## Features

- **Dark / Light mode** toggle — persists across all screens via CSS custom properties
- **KPI detail overlay** — click any KPI card for a weekly breakdown
- **Schedule block tooltips** — hover any time block for start/end/volume info
- **Status icon tooltips** — hover any ✓ or ⚠ in performance tables for context
- **Request Time Off modal** — with form validation states and success confirmation
- **Swap Shift modal** — day selector, colleague picker, success state
- **Help panel** — quick navigation and theme toggle shortcut
- **Responsive layout** — adapts to desktop, tablet and mobile with a bottom navigation bar on small screens
- **Smooth page transitions** — fade + translate between all 5 screens
- **Toast notifications** — lightweight feedback on every navigation action

---

## Design System

| Token            | Value                            |
| ---------------- | -------------------------------- |
| Background       | `#0A0A0B`                        |
| Surface          | `#111113`                        |
| Surface 2        | `#18181C`                        |
| Surface 3        | `#1F1F25`                        |
| Text Primary     | `#F0F0F2`                        |
| Text Secondary   | `#7A7A8A`                        |
| Green (positive) | `#3DDC84`                        |
| Amber (negative) | `#F59E0B`                        |
| Blue (info)      | `#4FACFE`                        |
| Font             | DM Sans + DM Mono (Google Fonts) |

---

## Built With

- Vanilla HTML, CSS, and JavaScript — zero dependencies
- CSS custom properties for theming
- SVG icons (inline, no icon library)
- Google Fonts (DM Sans, DM Mono)

---

## Author

Designed and built as a portfolio project exploring dark-mode dashboard UI patterns for contact center tooling.

---

## License

MIT — free to use, modify, and share.
