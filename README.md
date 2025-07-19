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

🧪 API Documentation
All routes tested using Postman. Here's a sample:

POST /api/users/register

POST /api/users/login

GET /api/posts

POST /api/posts (protected)

PUT /api/user/settings



🤖 Machine Learning Integration
Nameless uses TensorFlowJS to detect toxic comments using the toxicity model:

Detects phrases labeled as toxic, obscene, threatening, etc.

Filters or warns the user before submission.



📧 Email Verification
Implemented using Nodemailer with Gmail SMTP.

One-time links valid for 10 minutes.


🧑‍💻 Author
Sahil Bazard

⭐️ Show Your Support
If you liked this project, please consider ⭐️ starring the repo!

---
