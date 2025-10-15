# T-VANAMM-BILLING-SOFTWARE-WEB-VERSION-


✅ Here’s your final complete README package — including the banner I just generated and full text below 👇

---

# 🍵 T VANAMM Billing Software


The **T VANAMM Billing Software** is a modern web-based billing and analytics system built for the **T VANAMM Tea Franchise Network**.
It simplifies **order management, real-time billing, and sales analytics** for every franchise — powered by **Supabase + Next.js (React 18)** and an intuitive, responsive UI.

---

## 📌 Overview

Each franchise (e.g., FR-CENTRAL, FR-0002) can securely log in, manage menus, generate bills, track transactions, and analyze performance — all in one place.
Includes live synchronization, predictive analytics, and Bluetooth printing for instant receipts.

---

## ✨ Features

### 🧑‍💼 Admin / Franchise Module

* 🔐 Secure Supabase Auth login
* 🧾 Generate and print digital receipts
* 🍽️ Add / edit / delete menu items instantly
* 💸 Real-time bill generation & summary
* ⏱️ Shift tracking (via localStorage)
* 📊 Live sales charts and insights
* 🧮 AI trend prediction (engine based on linear regression)
* 📡 Automatic sync across franchises with Supabase Realtime

### 👥 User Module

* 💻 Interactive dashboard for staff
* 🔍 Searchable menu and order tracking
* 🖨️ Bluetooth receipt printing
* 🌙 Dark / Light mode toggle
* 🔔 Instant update notifications

### 🧠 Analytics Module

* 📈 Top-selling items & time-based trends
* 🪄 Predictive AI for menu optimization
* 📅 Weekly performance comparison
* 🔁 Automatic data sync to central admin database

---

## ⚙️ Tech Stack

| Layer             | Technology                              |
| :---------------- | :-------------------------------------- |
| **Frontend**      | Next.js (React 18 + Vite)               |
| **Backend**       | Supabase (PostgreSQL + Auth + Realtime) |
| **Styling**       | Tailwind CSS · Shadcn UI · Lucide Icons |
| **Visualization** | Recharts · Framer Motion                |
| **Security**      | Supabase Auth · AES Encryption          |
| **Printing**      | Web Bluetooth API                       |
| **Deployment**    | Vercel (Production)                     |

---

## 🧩 Architecture

```
Frontend (Next.js + Tailwind)
        ↓
Supabase SDK → PostgreSQL DB
        ↓
Realtime Channels → Live Updates
        ↓
Franchise Dashboards + Admin Analytics
```

* 🔄 Realtime sync for menu & bills
* 🧮 Predictive analysis engine
* 🖨️ Bluetooth printer integration

---

## 🛠️ Installation & Setup

### 🔧 Requirements

* Node.js ≥ 18
* Supabase project URL & Anon Key
* Modern browser (Web Bluetooth enabled)
* Vercel (optional)

### 🪜 Steps

```bash
# 1. Clone the repository
git clone https://github.com/surojuhomsaisantosh/tvanamm-billing.git
cd tvanamm-billing

# 2. Install dependencies
npm install

# 3. Create .env file
NEXT_PUBLIC_SUPABASE_URL=<your_url>
NEXT_PUBLIC_SUPABASE_ANON_KEY=<your_key>

# 4. Run dev server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000)

---

## 🧪 Sample Credentials

| Role      | Username                                                | Password    |
| :-------- | :------------------------------------------------------ | :---------- |
| Admin     | [admin@tvanamm.com](mailto:admin@tvanamm.com)           | tvanamm@123 |
| Franchise | [fr-central@tvanamm.com](mailto:fr-central@tvanamm.com) | fr@123      |

> Change these in the Supabase Auth Dashboard.

---

## 📂 Project Structure

```
tvanamm-billing/
 ├── public/                 # Static assets
 ├── src/
 │   ├── app/                # Next.js routes
 │   ├── components/
 │   │   ├── CentralDashboard/
 │   │   ├── MenuManager/
 │   │   ├── BillHistory/
 │   │   ├── Charts/
 │   │   └── Shared/
 │   ├── lib/                # Supabase client
 │   ├── hooks/              # Custom React hooks
 │   ├── styles/             # Tailwind themes
 │   ├── utils/              # Helper functions
 │   └── data/               # Mock/demo data
 ├── .env.example
 ├── package.json
 ├── README.md
 └── vercel.json
```

---

## 📊 Example Workflows

### 💰 Bill Generation

1. Select items → auto-calculate total
2. Insert bill into `bills_generated_billing`
3. Add line items to `bill_items_generated_billing`
4. Print via Bluetooth printer

### 📈 Analytics Insight

1. Fetch bills by date → aggregate sales
2. Render charts (Recharts)
3. Predict future trends

---

## 🤝 Credits

| Role                 | Contributor               |
| :------------------- | :------------------------ |
| 👨‍💻 Developer      | **Surojuhom Sai Santosh** |
| 🧉 Franchise Testing | T VANAMM Team             |
| 💾 Database Infra    | Supabase Community        |
| 🎨 UI Inspiration    | Shadcn UI & Framer Motion |

---

## 📜 License

> © 2025 **Surojuhom Sai Santosh**
> All Rights Reserved. Unauthorized use, copying, distribution, or modification is strictly prohibited.
> For partnership or commercial queries, contact 📧 `surojuhomsaisantosh@tvanamm.com`

---

## 🌐 Links

* 🌎 [www.tvanamm.com](https://www.tvanamm.com)
* 💼 [GitHub Profile](https://github.com/surojuhomsaisantosh)
* 📧 `surojuhomsaisantosh@tvanamm.com`

---

**Made with 💚 in India ☕ — Empowering Every Franchise Digitally.**
<img width="1024" height="1536" alt="image" src="https://github.com/user-attachments/assets/833e0b85-f5d8-47f1-810c-a92049846e31" />
