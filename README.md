# 🏎️ AD17 // High-Velocity Engineering Portfolio

A high-performance, Formula 1 pit-wall-inspired telemetry portfolio engineered to showcase advanced full-stack applications, automated pipelines, and intelligent AI agent systems. Designed with zero structural inefficiency and maximum render velocity.

![Next.js](https://img.shields.io/badge/Next.js-15-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178c6?style=for-the-badge&logo=typescript&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-Database-3ecf8e?style=for-the-badge&logo=supabase&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-v4-38bdf8?style=for-the-badge&logo=tailwindcss&logoColor=white)

---

## 🛠️ Telemetry & System Stack

The architecture mirrors a trackside telemetry control room, organizing component layers structurally for zero layout shifting:

* **Core Framework:** Next.js (App Router Engine) & React
* **Type Safety:** Strict TypeScript Engineering
* **Database Infrastructure:** Supabase Real-Time Data Streams
* **Styling Architecture:** High-Contrast Matte Black Foundations (`#0a0a0a`) via Tailwind CSS
* **Automations & Logic:** Client-side state engines and optimized React hooks

---

## 🚦 System Architecture Features

### 1. FIA Light Staging Gate (Preloader)
An immersive, sequenced preloader simulating an FIA starting light sequence. It manages critical DOM hydration states asynchronously, switching seamlessly to green before loading the viewport layout.

### 2. Driver Profile Bento Grid
A modular information grid displaying comprehensive developer metrics:
* **Telemetry Analytics:** Interactive skill matrices detailing core full-stack competencies.
* **Paddock Status:** A real-time data indicator tracking direct availability conditions.
* **Data Log Streams:** Dynamically generated activity feeds visualizing development output.

### 3. Pit Radio Transmission Loop (Contact Form)
A connected messaging gateway integrated directly with a backend Supabase instance. Features reactive visual telemetry states (Amber: Transmitting, Green: Received, Red: Failure) to log incoming project contracts without page refreshes.

---

## 📁 Repository Directory Map

```text
├── public/                 # Static asset tracks (Binaries, resume.pdf)
└── src/
    ├── app/                # Main server-side page router loop
    │   ├── layout.tsx      # System shell metadata configurations
    │   └── page.tsx        # Linear layout stack entry point
    ├── components/
    │   ├── cards/          # Reusable 3D tilt component containers
    │   ├── sections/       # Layout blocks (Navbar, BentoGrid, ContactSection)
    │   └── ui/             # Core widgets (FIA Preloader layout engine)
    └── lib/
        └── supabase.ts     # Singleton database connector client
```
## ⚙️ Initial Pit Stop (Local Setup) ##
To spin up the development engine on your local machine, complete these steps:

1. Clone the Chassis
Bash
git clone [https://github.com/Adityac17/portfolio.git](https://github.com/Adityac17/portfolio.git)
cd portfolio
2. Install Component Parts
Bash
npm install
3. Configure the Environment Lines
Create a .env.local file in the root directory and map your Supabase database access tokens:

Bash
NEXT_PUBLIC_SUPABASE_URL=[https://your-project-id.supabase.co](https://your-project-id.supabase.co)
NEXT_PUBLIC_SUPABASE_ANON_KEY=your-actual-public-anon-key
4. Ignite the Development Server
Fire up your local engine run loop:

Bash
npm run dev
Open http://localhost:3000 inside your web client to review your live site.

🏁 Author
Aditya Chouksey (AD17) - Full-Stack Developer & AI Agents Specialist

Institutional Base: ITM Skills University

Contact Path: 2025.adityac@isu.ac.in
