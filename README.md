# My-v0-project

_Generated on 2025-08-24 19:55 UTC_

## Overview

PermitSync UI prototype / application. This repository contains the user-facing interface for generating permit packets, managing checklists, and configuring notifications.

## Tech Stack

- Next.js
- React
- Tailwind CSS

## Prerequisites

- Node.js 18+ recommended
- npm or pnpm or yarn

## Getting Started

```bash
git clone <repo-url>
cd permit-app
pnpm install
pnpm run dev
# build for production
pnpm run build
# run production server
pnpm run start
```
## Core Features

- Permit Wizard: select city, project type, and size to create a project
- Auto-filled permit packet preview (PDF) with editable owner/site fields
- Smart Checklist with required signatures/stamps flags
- Dashboard for project status and reminders
- Email reminders (free) and optional SMS reminders (paid)

## Project Structure (truncated)

```
permit-app/
├── app/
│   ├── auth/
│   │   └── page.tsx
│   ├── billing/
│   │   └── page.tsx
│   ├── contractor/
│   │   ├── billing/
│   │   ├── upload/
│   │   ├── loading.tsx
│   │   └── page.tsx
│   ├── dashboard/
│   │   └── page.tsx
│   ├── jurisdictions/
│   │   ├── loading.tsx
│   │   └── page.tsx
│   ├── notifications/
│   │   └── page.tsx
│   ├── project/
│   │   └── [id]/
│   ├── wizard/
│   │   ├── review/
│   │   └── page.tsx
│   ├── globals.css
│   ├── layout.tsx
│   ├── not-found.tsx
│   └── page.tsx
├── components/
│   ├── ui/
│   │   ├── accordion.tsx
│   │   ├── alert-dialog.tsx
│   │   ├── alert.tsx
│   │   ├── aspect-ratio.tsx
│   │   ├── avatar.tsx
│   │   ├── badge.tsx
│   │   ├── breadcrumb.tsx
│   │   ├── button.tsx
│   │   ├── calendar.tsx
│   │   ├── card.tsx
│   │   ├── carousel.tsx
│   │   ├── chart.tsx
│   │   ├── checkbox.tsx
│   │   ├── collapsible.tsx
│   │   ├── command.tsx
│   │   ├── context-menu.tsx
│   │   ├── dialog.tsx
│   │   ├── drawer.tsx
│   │   ├── dropdown-menu.tsx
│   │   ├── form.tsx
│   │   ├── hover-card.tsx
│   │   ├── input-otp.tsx
│   │   ├── input.tsx
│   │   ├── label.tsx
│   │   ├── menubar.tsx
│   │   ├── navigation-menu.tsx
│   │   ├── pagination.tsx
│   │   ├── popover.tsx
│   │   ├── progress.tsx
│   │   ├── radio-group.tsx
│   │   ├── resizable.tsx
│   │   ├── scroll-area.tsx
│   │   ├── select.tsx
│   │   ├── separator.tsx
│   │   ├── sheet.tsx
│   │   ├── sidebar.tsx
│   │   ├── skeleton.tsx
│   │   ├── slider.tsx
│   │   ├── sonner.tsx
│   │   ├── switch.tsx
│   │   ├── table.tsx
│   │   ├── tabs.tsx
│   │   ├── textarea.tsx
│   │   ├── toast.tsx
│   │   ├── toaster.tsx
│   │   ├── toggle-group.tsx
│   │   ├── toggle.tsx
│   │   ├── tooltip.tsx
│   │   ├── use-mobile.tsx
│   │   └── use-toast.ts
│   ├── empty-state.tsx
│   ├── loading-spinner.tsx
│   └── theme-provider.tsx
├── contexts/
│   └── project-context.tsx
├── hooks/
│   ├── use-mobile.ts
│   └── use-toast.ts
├── lib/
│   ├── contractor-types.ts
│   ├── notification-types.ts
│   ├── packet-types.ts
│   ├── types.ts
│   └── utils.ts
├── public/
│   ├── placeholder-logo.png
│   ├── placeholder-logo.svg
│   ├── placeholder-user.jpg
│   ├── placeholder.jpg
│   └── placeholder.svg
├── styles/
│   └── globals.css
├── .gitignore
├── components.json
├── next.config.mjs
├── package.json
├── pnpm-lock.yaml
├── postcss.config.mjs
└── tsconfig.json
```

## Available Scripts

- `build` — `next build`
- `dev` — `next dev`
- `lint` — `next lint`
- `start` — `next start`

## License

Proprietary — for internal use only unless otherwise stated.
