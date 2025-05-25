# 🎫 WetinHapin — Customer Portal

This is the **customer-facing portal** for the [WetinHapin Helpdesk Platform](https://github.com/koirah-technology/wetinhapin).  
It allows customers and end-users to:

- Submit new support tickets
- Track the status of existing issues
- Browse the knowledge base
- Interact with support agents via threaded messages

> Designed to be simple, fast, and mobile-friendly — especially for organizations in Africa and similar infrastructure environments.

---

## ✨ Features

- 📝 Ticket submission form with dynamic fields
- 🔍 Ticket list and detail view (per user)
- 📚 Searchable Knowledge Base (public articles)
- 🔐 Secure login via OTP or OAuth (Google, Microsoft)
- 🌐 Custom branding via Supabase (per deployment)

---

## 🧱 Tech Stack

- **Framework:** Next.js (App Router)
- **Styling:** Tailwind CSS + Shadcn UI
- **Auth:** Supabase Auth (magic link, OAuth)
- **Data:** Supabase Postgres + RLS
- **Realtime:** Supabase Realtime
- **State/Validation:** Zod, useForm, etc...

---

## 🛠️ Local Development

```bash
# From the root of the monorepo:
pnpm dev --filter customer-portal

apps/customer-portal/
├── app/                # Next.js App Router files
│   ├── login/
│   ├── (dashboard)/
│   └─── tickets/
│   └─── knowledge-base/
├── components/         # UI components (button, card, etc.)
├── lib/                # Supabase client, helpers
├── types/              # Global/shared types
├── env.d.ts            # Environment typing
└── README.md
```
