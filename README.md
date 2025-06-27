# 🎟️ Muse-Bot 
### Revolutionizing Visitor Experience with Intelligent Ticket Booking through chatbot. 

Muse-Bot is a functional prototype of a chatbot-enabled ticketing platform developed for Jaipur’s heritage sites, built with Next.js 14, MongoDB Atlas, and Razorpay. This project demonstrates secure authentication, seamless payments, and a scalable architecture suitable for real-world deployments.


## 🎥 Demonstration video
https://github.com/user-attachments/assets/abb763d9-1d31-4ba0-a90c-b073bdc2c4c4

---

## 🚀 Features
- **User Authentication:** Email/password, Google OAuth, JWT-based sessions, and email verification.
- **Secure Payments:** Razorpay integration for real-time ticket booking and payment verification.
- **Admin & User Dashboards:** Role-based access, booking management, and analytics-ready structure.
- **Password Management:** Secure reset and update flows.
- **Responsive UI:** Built with Tailwind CSS for a modern, mobile-friendly experience.
- **API-First Design:** RESTful endpoints using Next.js App Router.
- **Cloud-Ready:** Uses MongoDB Atlas for production-grade, cloud-hosted data.

---

## 🛠️ Tech Stack
| Layer         | Technology                |
|---------------|---------------------------|
| Frontend      | Next.js 14, React, Tailwind CSS |
| State         | Redux Toolkit             |
| Auth          | NextAuth.js, JWT, Google OAuth |
| Backend/API   | Next.js App Router        |
| Database      | MongoDB Atlas, Mongoose   |
| Payments      | Razorpay                  |
| Utilities     | Axios, Nodemailer         |

---

## 🏗️ Project Structure
```
my-app/
├── app/           # Next.js app directory (routes, API, components)
├── models/        # Mongoose schemas
├── dbConfig/      # Database connection logic
├── redux/         # Redux Toolkit store & slices
├── utilities/     # Utility functions (mailer, etc.)
├── public/        # Static assets (images, icons)
└── ...
```

---

## ⚡ Getting Started

### 1. Clone & Install
```bash
git clone <your-repo-url>
cd my-app
npm install
```

### 2. Environment Variables
Create a `.env.local` file in the root directory:
```env
GOOGLE_ID=your_google_client_id
GOOGLE_SECRET=your_google_client_secret
MONGO_URI=your_mongodb_atlas_uri
DOMAIN=http://localhost:3000
TOKEN_SECRET=your_jwt_secret
NEXT_PUBLIC_URL=http://localhost:3000
NEXT_PUBLIC_KEY_ID=your_razorpay_key_id
NEXT_PUBLIC_KEY_SECRET=your_razorpay_key_secret
```

### 3. Run Locally
```bash
npm run dev
```
Visit [http://localhost:3000](http://localhost:3000)

---

## 🚢 Deployment
- **Production:** Set all environment variables in your deployment platform (Vercel, Netlify, etc.)
- **Database:** Use a MongoDB Atlas URI for `MONGO_URI` (not localhost)
- **Security:** Never commit secrets to your repository
- **Redeploy** after updating environment variables

---

## 📦 Key Modules
- `app/api/` — Secure RESTful endpoints for auth, payments, bookings
- `models/` — User, Payment, Booking schemas
- `redux/` — Centralized state management
- `utilities/mailer.js` — Email verification & password reset

---


## 👨‍💻 Authors & Credits
- Team AlgoSmiths — Jaipur Heritage Ticketing Platform
- Built for Smart India Hackathon 2024
---

## 💡 Notes
- The codebase is modular, scalable, and follows best practices for security and maintainability.
- All sensitive operations (auth, payments) are handled server-side.
- The UI is fully responsive and accessible.
- The app is ready for production deployment with minimal changes.
