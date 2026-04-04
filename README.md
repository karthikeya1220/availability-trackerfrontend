# 🚀 MentorQue: Premium Frontend Ecosystem

The high-fidelity, 3D-animated entry portal and administrative dashboard for the MentorQue ecosystem. Built using the **Sero Framer** aesthetic with custom React components, Tailwind CSS, and Framer Motion.

## ✨ Core Platforms
1.  **3D Landing Wall**: Performance-optimized hero section with scroll-linked animations.
2.  **Admin Scheduler**: AI-powered recommendation engine with localized availability matching.
3.  **Mentor/Candidate Portals**: Role-specific, minimal dashboards for session management.

## 🏗️ Technical Architecture
*   **Engine**: Vite / React 18
*   **Styling**: Tailwind CSS (PostCSS)
*   **Animations**: Framer Motion (Hardware Accelerated)
*   **Authentication**: React Context and Protected Routing (with RBAC)
*   **State Management**: Unified API Client using axios and interceptors.

## 🚀 Quick Start (Local Setup)

### 1. Prerequisite Sync
Ensure you are in the root of the frontend repository.
```bash
npm install
```

### 2. Environment Configuration
Create a `.env` file in the root directory.
```env
# URL of your backend engine (Step 4 in Backend Setup)
VITE_API_URL=http://localhost:5001
VITE_JWT_SECRET=1dbaf9fa929cfd7ca4b1d78180673a9dd391770413c99cdff3801e77fcee0a20
```

### 3. Launch Dashboard
```bash
# Start the local development server
npm run dev
```

### 4. Local Access
Open `http://localhost:5173` to view the 3D landing wall.

## 📐 Design System & Styles
*   **Background**: Deep Black (`#0A0A0A`)
*   **Accent**: High-fidelity Lavender (`#9E9EFF`)
*   **Typography**: Medium Inter with reduced letter-spacing for premium feel.
*   **Cards**: Glassmorphic with translucent borders (`rgba(255, 255, 255, 0.1)`).

## 🔐 Master Demo Identities
| Access Tier | Identifier | Security Key |
| :--- | :--- | :--- |
| **Administrator** | `admin@mentorque.com` | `admin123456` |
| **Mentor** | `arjun.sharma@mentorque.com` | `mentor123` |
| **Candidate** | `aditya.kumar@example.com` | `user123456` |

## 🌲 Project Structure
```text
src/
├── api/            # Unified communication unit
├── components/     # High-fidelity atoms & modules
├── context/        # Auth & Shared identity state
├── hooks/          # Domain-specific logic
├── pages/          # Fully animated views
└── utils/          # Transformation & Formatting
```

## 🛠️ Troubleshooting
- **Failed Login**: Ensure the backend is running and the `VITE_API_URL` is pointing to the correct port (usually 5001).
- **Broken CSS**: Make sure PostCSS is correctly configured if you are running in a custom environment.

---
**Institutional Access Only.** Engineered by the MentorQue Development Unit.
