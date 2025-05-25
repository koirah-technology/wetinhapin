# 🛠️ WetinHapin — Internal Helpdesk Dashboard

This is the **core application** of the [WetinHapin Helpdesk Platform](https://github.com/koirah-technology/wetinhapin), designed for use by Admins, Supervisors, and Agents.  
It provides internal tools to manage tickets, respond to customers, assign workloads, and analyze service performance.

> Built for modern organizations that want full control over their helpdesk operations — fast, secure, and entirely self-hostable.

---

## 👥 User Roles

- **Agent:** Respond to tickets, manage queues, collaborate via internal notes.  
- **Supervisor:** Oversee teams, monitor ticket metrics, reassign workloads.  
- **Admin:** Full access — manage users, categories, workflows, org settings, reports.

---

## ✨ Features

- 🎟️ Advanced ticketing lifecycle with SLA timers  
- 🔔 Realtime notifications & internal messaging  
- 🧑‍🤝‍🧑 Role-based dashboard views  
- 📈 Analytics for ticket volume, resolution time, SLAs  
- 📂 Bulk invite users via CSV  
- 🧠 Integrated knowledge base  
- ⚙️ Custom categories, priorities, branding  
- 🛡️ Secure login with magic links or OAuth (Google/Microsoft)

---

## 🧱 Tech Stack

- **Framework:** Next.js (App Router)  
- **UI:** Tailwind CSS + Shadcn UI  
- **Auth:** Supabase Auth (OTP + OAuth)  
- **Database:** Supabase PostgreSQL (RLS enforced)  
- **Realtime:** Supabase Realtime for updates + presence  
- **Notifications:** Resend (Email), Twilio (Post-MVP)  
- **Testing:** Jest, Playwright

---

## 🛠️ Local Development

```bash
# From the root of the monorepo
pnpm dev --filter wetinhapin