# 💊 PharmaCare AI

An AI-powered pharmacy care assistant that helps users understand medications, check drug interactions, and get personalized healthcare guidance — built with React, TypeScript, and Tailwind CSS.

![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn--ui-000000?style=flat&logo=shadcnui&logoColor=white)
![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen?style=flat&logo=vercel)

---

## 🚀 Project Overview

Patients and caregivers often struggle to understand medication instructions, dosage details, and drug safety without consulting a doctor every time.

This project solves that problem by using **AI** to:

- Understand and answer pharmacy-related queries
- Provide medication information and dosage guidance
- Check drug safety and interactions
- Offer a clean, user-friendly chat interface

It also provides a **role-based portal** for Admins and Users (Patients/Caregivers).

---

## 🧠 Key Features

### 👨‍💼 Admin Portal

- Manage users and pharmacy data
- Monitor AI query activity
- View and manage reported issues
- Mark patient issues as resolved

### 🧑‍⚕️ User (Patient) Portal

- Chat with AI medication assistant
- Get drug information and dosage guidance
- Check drug interaction risks
- Report health concerns in real-time

### 🤖 AI Capabilities

- Answer queries about:
  - Medication usage and dosage
  - Drug side effects
  - Drug interactions
  - General pharmacy guidance
- Assign risk levels:
  - 🔴 High Risk (serious interaction)
  - 🟡 Medium Risk (use with caution)
  - 🟢 Low Risk (safe to use)
- Provide explainable AI responses
- Interactive chat-based interface

---

## 🔄 System Workflow

1. User opens the PharmaCare AI web app
2. User types a medication or health query
3. Query is sent to the AI service for analysis
4. AI identifies relevant drug information and risk level
5. System returns a clear, explainable response
6. User can continue the conversation or report an issue
7. Admin reviews reported issues and manages platform data

---

## 🏗️ Architecture

```
Frontend (React + TypeScript + Tailwind CSS)
        ↓
Vite Build System (Fast Dev & Production)
        ↓
shadcn/ui Component Library (UI Layer)
        ↓
AI Service (OpenAI / LLM Integration)
        ↓
Database (User Data, Query Logs, Reports)
```

---

## 🛠️ Technologies Used

### 🔹 Frontend
- React + TypeScript
- Tailwind CSS
- shadcn/ui component library
- Vite (build tool)

### 🔹 Mobile Support
- Capacitor (cross-platform mobile)

### 🔹 AI / LLM
- OpenAI GPT API (medication intelligence)

### 🔹 Styling
- Tailwind CSS + PostCSS

---

## 📁 Project Structure

```
PHARMACARE_AI/
│
├── src/
│   ├── components/     # Reusable UI components
│   ├── pages/          # Application pages/routes
│   ├── hooks/          # Custom React hooks
│   └── lib/            # Utility functions & helpers
├── public/             # Static assets
├── index.html          # App entry point
├── vite.config.ts      # Vite configuration
├── tailwind.config.ts  # Tailwind configuration
└── README.md
```

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/shrutikahage2005/PHARMACARE_AI.git
cd PHARMACARE_AI
```

---

### 2️⃣ Install Dependencies

```bash
npm install
```

---

### 3️⃣ Set Up Environment Variables

Create a `.env` file in the root directory:

```env
VITE_API_KEY=your_openai_api_key_here
```

> ⚠️ Never commit your `.env` file with real API keys. It is already added to `.gitignore`.

---

### 4️⃣ Start the Development Server

```bash
npm run dev
```

The app will run at `http://localhost:8080`

---

## 🔐 Demo Credentials

### Admin Login
- Email: admin@pharmacare.com
- Password: admin123

### User Login
- Email: user@pharmacare.com
- Password: user123

---

## 📊 Sample Use Cases

- Ask about medication dosage and timing
- Check if two drugs can be taken together
- Understand side effects of a prescription
- Get guidance on over-the-counter medications
- Report a health concern to admin

---

## 💡 Future Improvements

- [ ] Prescription image upload & OCR analysis
- [ ] Multilingual support (Hindi + English)
- [ ] Real-time pharmacist consultation
- [ ] Push notifications for medication reminders
- [ ] Cloud deployment on AWS / GCP
- [ ] Integration with real pharmacy APIs

---

## 🏆 Project Value

This project demonstrates:

- Real-world healthcare problem solving with AI
- Full-stack React + TypeScript development
- Role-based system design (Admin + User)
- Clean, production-ready UI with shadcn/ui
- Explainable AI outputs for sensitive domain

---

## 📸 Screenshots

*Add screenshots of your UI here for better presentation*
## 📸 Screenshots

### 🖥️ Admin Portal — AI Chat
![Admin Chat](screenshots/admin-chat.png)

### 📦 Inventory Management
![Inventory](screenshots/inventory.png)

### 🔔 Refill Alerts — AI Predictions
![Refill Alerts](screenshots/refill-alerts.png)

### 👤 User Portal — AI Pharmacist
![User Chat](screenshots/user-chat.png)

### 📄 Upload Prescription (Rx)
![Upload Rx](screenshots/upload-rx.png)

---

## 🤝 Contributing

Feel free to fork this repository and improve the project!

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

- Inspired by real-world healthcare accessibility challenges
- Built using modern AI and full-stack web technologies

---

## 👩‍💻 Author

**Shrutika Hage**
- GitHub: [@shrutikahage2005](https://github.com/shrutikahage2005)
- LinkedIn: [shrutikahage2005](https://linkedin.com/in/shrutikahage2005)

---

> ⭐ If you like this project, give it a star on GitHub!
