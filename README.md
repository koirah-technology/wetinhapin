# 🧭 WetinHapin — Open Helpdesk Platform

**WetinHapin** is an open-source, fully featured helpdesk platform designed for organizations, institutions, and companies across Africa and beyond. It allows teams to handle internal or external support requests, track ticket lifecycles, collaborate across departments, and customize workflows.

> 🔧 Self-hostable · 🪄 Built with modern tools · 💬 Designed for real-world teams · 🇸🇱 Made for Africa

---

## 🧱 Monorepo Structure

This project is built using [Turborepo](https://turbo.build/repo) and follows a modern mono-repo architecture.

```bash
wetinhapin/
├── apps/
│   ├── wetinhapin-helpdesk/        # Main helpdesk dashboard (admin, agents, supervisors)
│   ├── wetinhapin-customer-portal/   # Public customer portal (create ticket, view status, self-help)
│   └── wetinhapin-docs-site/         # Static documentation site for deployment + setup
│
├── packages/
│   ├── ui/                # Shared Shadcn UI components, Tailwind config
│   ├── eslint-config/     # ESLint config
|   |-- typescript-config/ # TSConfig base files and config
│   ├── db-schema/         # Supabase schema + RLS + seed scripts
│   └── utils/             # Shared validation, helper functions, email templates
```

## 🧰 Tech Stack

- **Frontend:** Next.js App Router · Tailwind CSS · Shadcn UI · Framer Motion, more...(check the package.json file)
- **Backend:** Supabase (Postgres, Auth, Realtime, Storage)
- **Testing:** Jest · Playwright
- **CI/CD:** GitHub Actions (planned)
- **Infrastructure:** Docker (optional), Render (for backend), Vercel (for frontend)
- **Email:** Resend · React Email
- **Other:** Zod · TypeScript · Turborepo, and more...

## 🔓 License

This software is licensed under the **AGPL-3.0 License**.
You are free to self-host and modify, but **commercial SaaS use (hosting for others)** is **not permitted** under this license.

## 👏 Contributing

Community contributions are welcome!

Please see the `CONTRIBUTING.md` file for:
- Development setup
- Code style guidelines
- Pull request process
- ...

## 🗺️ Roadmap (MVP)

- ✅ Ticketing system with status transitions
- ✅ Internal agent messaging + comments
- ✅ SLA timers and workflows
- ✅ Notifications (Email + Realtime)
- ✅ Customer portal and KB
- ✅ Multi-role access: Admin, Supervisor, Agent
- ✅ Audit logs, metrics, export features
- 🔜 Custom field configuration
- 🔜 Email template theming
- 🔜 Deployment script and CI/CD templates

## 🌍 Made by [Koirah Technology](https://github.com/koirah-technology)

Open software for a connected continent.
