# Next.js Admin Dashboard

This is a **Next.js** based admin dashboard application built with modular components, reusable layouts, and scalable architecture. The app features category and vendor management, user authentication, and search functionalities, with a clean and maintainable folder structure.

## 📁 Project Structure

src
├── components # Reusable UI components
│ ├── BreadCrumb
│ ├── Categories
│ ├── Dropdowns
│ ├── Feedbakcs
│ ├── Modals
│ ├── Navbars
│ ├── Search
│ ├── Vendors
│ ├── ButtonLoader.tsx
│ ├── Compare.tsx
│ ├── Profile.tsx
│ └── HomeCarousal.tsx
├── layouts # Layout wrappers (Admin/Auth)
│ ├── Admin.tsx
│ └── Auth.tsx
├── lib # Utility files for API, constants, types
│ ├── api.ts
│ ├── constants.ts
│ └── types.ts
├── pages # Next.js pages (routing)
│ ├── 404.tsx
│ ├── categories.tsx
│ ├── dashoard.tsx
│ ├── forgot-password.tsx
│ ├── index.tsx
│ ├── login.tsx
│ ├── profile.tsx
│ ├── reset-password.tsx
│ ├── search.txs
│ └── vendors.tsx
├── reducers # Redux reducers
│ └── auth.ts
├── store # Redux store setup
│ └── index.ts
├── templates # Template containers
│ └── Main.tsx
└── utils # Utility/helper functions
├── AppConfif.ts
├── Feedback.ts
└── Helpers.ts


## 🛠️ Features

- Modular component-based architecture
- Category and vendor listing and detail views
- Auth pages (login, forgot/reset password)
- Reusable layouts for Admin and Auth pages
- Redux setup for auth state management
- Utility files for configuration and helper logic
- Carousel, loaders, dropdowns, and feedback UI

## 🚀 Getting Started

### Prerequisites

- Node.js ≥ 16
- npm or yarn

### Installation

```bash
npm install
# or
yarn install
