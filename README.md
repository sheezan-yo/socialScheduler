# 🚀 AI Social Media Scheduler

An AI-powered social media scheduling platform that allows users to create, generate, and schedule posts across multiple social media platforms from a single dashboard.

The application integrates with **Zernio** for social media publishing and uses a **Large Language Model (LLM)** to generate engaging post content based on user prompts.

---

## ✨ Features

* 📅 Schedule posts for future publishing
* 🤖 Generate AI-powered social media content
* 🌐 Publish to multiple platforms simultaneously
* 🖼️ Upload images or videos with posts
* 📊 View upcoming and published posts
* 🔐 Secure authentication and user-specific data
* ⚡ Automatic background scheduler for publishing due posts

---

## 🌍 Supported Platforms

* Instagram
* LinkedIn
* X (Twitter)
* Facebook

Publishing is handled through the **Zernio API**, allowing one scheduled post to be distributed across multiple connected social accounts.

---

## 🛠️ Tech Stack

### Frontend

* React
* TypeScript
* Tailwind CSS
* Axios
* React Hot Toast

### Backend

* Node.js
* Express.js
* TypeScript
* MongoDB
* Mongoose

### AI

* Large Language Model (LLM) for AI post generation

### Media Storage

* Cloudinary

### Social Publishing

* Zernio API

---

## 📂 Project Structure

```
client/
├── src/
│   ├── api/
│   ├── components/
│   ├── context/
│   ├── pages/
│   └── ...

server/
├── controllers/
├── middlewares/
├── models/
├── routes/
├── services/
└── ...
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/your-username/social-scheduler.git
cd social-scheduler
```

### Backend

```bash
cd server
npm install
```

Create a `.env` file:

```env
PORT=3000

MONGO_URI=your_mongodb_connection

JWT_SECRET=your_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

ZERNIO_API_KEY=your_zernio_api_key

GOOGLE_API_KEY=your_llm_api_key
```

Start the backend:

```bash
npm run dev
```

---

### Frontend

```bash
cd client
npm install

```

Create a `.env` file:

```env
VITE_API_BASE_URL=your_vite_url(backend_url)
```

Start the frontend:

```bash
npm run dev
```

---

## 🤖 AI Post Generation

The application can generate high-quality social media posts using a Large Language Model.

Users simply provide:

* Topic
* Platform
* Tone
* Optional prompt

The AI generates optimized content suitable for the selected social media platform.

### Image generation will be added soon.

---

## 📅 Scheduling Workflow

1. Write or generate a post.
2. Select one or more social media platforms.
3. Upload media (optional).
4. Choose the publishing date and time.
5. Schedule the post.

A background scheduler continuously checks for posts whose scheduled time has arrived and automatically publishes them through Zernio.

---

## 🖼️ Media Support

Supported uploads include:

* Images
* Videos

Media files are uploaded to Cloudinary before being sent to the publishing service.

---

## 🔒 Authentication

* User Registration
* Login
* JWT Authentication
* Protected Routes

Each user only has access to their own scheduled posts and connected social accounts.

---

## 📈 Future Improvements

* Analytics dashboard
* Draft management
* Recurring posts
* Team collaboration
* Content calendar
* AI-generated hashtags
* AI-generated captions
* Post performance insights
* Email and push notifications

---

## 📸 Screenshots

Add screenshots of:

* Dashboard
* Scheduler
* AI Post Generator
* Upcoming Posts
* Connected Accounts

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push your branch
5. Open a Pull Request

---

## Author
 * https://github.com/sheezan-yo