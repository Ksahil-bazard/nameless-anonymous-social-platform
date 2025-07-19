# 🕵️ Nameless – Anonymous Social Platform

Nameless is a full-stack anonymous social platform for college students to interact, express, and engage freely without revealing their identities. It supports secure user registration, anonymous posting, sentiment filtering, and ML-based moderation.

---

## 🚀 Features

- 🔐 **User Authentication** — Secure login/signup with JWT.
- 📩 **Email Verification** — Email confirmation via Nodemailer with 92% delivery success.
- 🧾 **Anonymous Posting** — Post anonymously while preserving user control and moderation.
- 🧠 **Toxicity Detection** — Integrated TensorFlowJS for filtering toxic content.
- 🧠 **Real-time Sentiment Tags** — Posts tagged with sentiment using lightweight NLP.
- ⚙️ **RESTful APIs** — 15+ APIs for users, posts, and settings with Postman testing.
- 🗃️ **Redux State Management** — Global state handling for seamless UI experience.

---

## 🛠️ Tech Stack

**Frontend**

- ReactJS
- Redux
- Vanilla CSS

**Backend**

- NodeJS
- ExpressJS
- MongoDB (Mongoose)
- Nodemailer (for email verification)
- TensorFlowJS (for ML moderation)

---

## 📸 Screenshots

> (Add some UI screenshots here using `![alt text](link)` if you have deployed it or have sample UI)

---

## 📦 Installation

```bash
# Clone the repo
git clone https://github.com/yourusername/nameless.git
cd nameless

# Install backend dependencies
cd server
npm install

# Start backend
npm run dev

# Install frontend dependencies
cd ../client
npm install

# Start frontend
npm start
```
