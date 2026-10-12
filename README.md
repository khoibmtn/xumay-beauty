# Xumây Beauty

**Business management platform for beauty & wellness businesses in Vietnam** — spas, salons, aesthetic clinics and
retail shops. Multi-tenant SaaS, built by a founder who runs a real clinic on it every day.

🌐 **Website:** [xumay.vn](https://xumay.vn) · English: [xumay.vn/en](https://xumay.vn/en) · ✉️ admin@xumay.vn

> The application source code is private. This repository is the public home of the project: what we build, how,
> and where we are going.

## What it does

| Area | Features |
|---|---|
| Point of sale | Invoices, partial payments & debt, returns, VietQR bank-transfer QR with the amount pre-filled |
| Appointments | Calendar by room & technician, online booking page, reminders, courses scheduled across sessions |
| Customers | Packages, prepaid cards, loyalty points, deposits, customer history, automated care (birthday, win-back) |
| Inventory | Stock per branch, purchases, stocktakes, write-offs, **stock transfers between branches** with cost snapshots |
| Money | Cash book, **per-branch cash drawers**, end-of-day reconciliation, cross-branch collection ("thu hộ") |
| Staff | Accounts with roles per branch, schedules, payroll by pay branch, commissions |
| Clinics | Medical records for aesthetic clinics |
| Reports | Sales, finance, end-of-day, staff, customers, packages, suppliers, ratings — per branch or all, CSV export |
| Platform | Many shops on one platform, plans & limits, per-business-type vocabulary, audit log, changelog |
| Data safety | Nightly backups that skip unchanged nights, shop self-export, per-shop restore with preview |

## Built in production, fast

- Development started **5 Sep 2026**; live since **1 Oct 2026** (v1.0.0).
- **28 production releases in 12 days** (v1.0.0 → v1.17.0), each gated by **4,600+ automated tests**, business-invariant
  reviews and a security review.
- 119 database migrations · 800+ commits · multi-branch operations shipped in five rounds over two days.
- Dog-fooded daily at our first clinic (2 founders + 3 staff).

## Tech

Cloudflare Workers (Next.js via OpenNext) · Postgres (Supabase) via Hyperdrive · R2 · Workers KV · Durable Objects ·
Cloudflare Email · Drizzle ORM · TypeScript.

## Built with Claude

The whole platform is engineered with **Claude Code** — design, implementation, test suites, security reviews and
release automation (analyst → implementer → verifier agent loops).

Coming next, with the Claude API:

- **AI business analyst** for every shop — ask in Vietnamese about your own sales, bookings, stock and staff; get
  charts, insights and suggested actions (strict per-shop data isolation).
- **AI-drafted customer care** — reminders, win-back and birthday messages in each shop's tone.
- **Front-desk assistant** — a quick summary of a customer's history before each appointment.

## About

Operated by Nguyen Thi Thu Huong 1991 Household Business · Thuy Nguyen Ward, Hai Phong City, Vietnam · Est. 2026.

---

# Xumây Beauty (Tiếng Việt)

Nền tảng quản lý cho spa, salon, phòng khám thẩm mỹ và cửa hàng tại Việt Nam — bán hàng, lịch hẹn và đặt lịch online,
gói / thẻ / tích điểm, kho nhiều chi nhánh, sổ quỹ & cuối ngày theo chi nhánh, lương & hoa hồng, chăm sóc khách tự động,
báo cáo. Đang vận hành thật mỗi ngày tại gian hàng đầu tiên. Xem tại [xumay.vn](https://xumay.vn).
