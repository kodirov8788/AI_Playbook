# Reference Pattern: Next.js Layout Structure

Ensure all Next.js applications follow this layout blueprint:
```
src/
├── app/                  # Routing App Router folder
│   ├── layout.tsx        # Global Layout
│   ├── page.tsx          # Landing
│   └── (routes)/         # Route Groups (e.g. (auth), (dashboard))
├── components/           # UI Elements
│   ├── ui/               # Reusable Atomic Elements (button, input)
│   └── dashboard/        # Feature-specific layouts
├── hooks/                # Custom React Hooks
├── lib/                  # Internal Shared Utilities (api, db, auth)
└── types/                # Shared TypeScript Type Interfaces
```
- Restrict Client Components (`'use client'`) to the outer leaf nodes of the UI tree.
- Keep server-side data fetching encapsulated in Page layouts or dedicated Server Action controllers.
