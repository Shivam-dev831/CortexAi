# CortexAI 🚀

CortexAI is a full-stack AI-powered web application featuring an interactive chat interface, conversation history tracking, automated message processing, and integrated payment verification.

---

## 🛠️ Tech Stack

### **Frontend**
- **Framework & UI:** React.js, Tailwind CSS, Lucide React Icons
- **State Management:** Redux Toolkit (`userSlice`, `messageSlice`, `conversationSlice`)
- **HTTP Client:** Axios (Custom utility setup)

### **Backend**
- **Runtime Environment:** Node.js
- **Framework:** Express.js
- **Payment Gateway:** Razorpay Integration (Includes `verifyPayment` API)

---

## ✨ Features

- 💬 **Interactive AI Chat:** Real-time user interaction with full message & conversation state tracking.
- 🔐 **User Management:** Auth workflows powered by Redux state management.
- 💳 **Payment Gateway:** Razorpay backend integration with payment verification logic.
- ⚙️ **CI/CD:** Automated GitHub Actions workflows included in `.github/`.

---

## 📁 Project Structure

```text
1.cortexAI/
├── .github/              # GitHub Actions workflows
├── backend/              # Node.js & Express server logic
├── frontend/             # React Client Application
│   ├── src/
│   │   ├── features/     # Component features (e.g., verifyPayment.js)
│   │   ├── pages/        # App pages (Home.jsx)
│   │   ├── redux/        # Redux Slices (store, user, message, conversation)
│   │   └── utils/        # Axios configuration
│   └── ...
└── .gitignore            # Git ignored files
