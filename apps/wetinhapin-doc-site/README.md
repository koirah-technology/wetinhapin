# 📘 WetinHapin — Documentation Site

This is the official **documentation and onboarding site** for [WetinHapin](https://github.com/koirah-technology/wetinhapin), a fully open-source, self-hostable helpdesk platform built for African institutions and organizations.

It contains:

- 🌍 Step-by-step hosting instructions  
- ⚙️ Supabase setup and database migrations  
- 🧪 Testing, deployment, and environment guides  
- 🎨 Customization examples (logos, categories, email templates)

> Targeted at developers or IT teams who want to deploy WetinHapin internally without using SaaS.

---

## 📦 Features

- 📚 Clean documentation site built with Markdown & MDX  
- 🧭 Sidebar navigation for all setup phases  
- 🧪 Live code snippets and SQL examples  
- 📥 Downloadable `.sql` seed, migration, RLS policy files  
- 🛠️ Guides for both local and cloud deployment (Supabase, Vercel, etc.)

---

## 🧱 Tech Stack

- **Framework:** Next.js (App Router)  
- **Styling:** Tailwind CSS + MDX  
- **UI:** Shadcn UI Docs + custom layout  
- **Content:** Markdown/MDX files inside `/content`

---

## 🛠️ Local Development

```bash
# From the root of the monorepo
pnpm dev --filter docs-site