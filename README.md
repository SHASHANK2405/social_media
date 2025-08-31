GossipGram 📸

A MERN stack social media application where users can share posts, connect with friends, and interact in real-time.

🚀 Tech Stack

Frontend: React.js, TailwindCSS

Backend: Node.js, Express.js

Database: MongoDB Atlas

Authentication: JWT

Cloud Storage: Cloudinary

Email Service: Nodemailer (Gmail SMTP)

⚙️ Installation & Setup

1. Clone the Repository
   git clone https://github.com/SHASHANK2405/social_media.git
   cd gossipgram

2. Install Dependencies

For frontend:

npm install

For backend:

cd server
npm install

3. Create .env File in Server Directory

Add the following variables:

# Server Configuration

PORT=4000
JWT_SECRET=Uchiha

# Database

MONGODB_URL="mongodb+srv://shashankgulati2405:DnOLHOXCaJhfBwWm@cluster0.feowlv1.mongodb.net/gossipgram_new"

# Email (Nodemailer with Gmail SMTP)

MAIL_HOST=smtp.gmail.com
MAIL_USER=gossipgram.app@gmail.com
MAIL_PASS=cqiv jdqk tokf pmur

# Cloudinary Configuration

FOLDER_NAME=MajorProject
CLOUD_NAME=dmnbbtccl
API_KEY=232195756354274
API_SECRET=oorBRxXSyen_PNfA0k2K3FRo8Ls

▶️ Running the Project
cd to main directory (gossipgram)

npm run dev

📦 Features

🔐 User Authentication (JWT)

📸 Upload & Store Images (Cloudinary)

📬 Email Notifications (SMTP Gmail)

💬 Post, Like, Comment System

🌐 MongoDB Atlas for scalable data storage

🛠 Troubleshooting

If you face querySrv ENOTFOUND error, make sure your MongoDB Atlas cluster is active and your network access (IP whitelist) is set to 0.0.0.0/0.

For Gmail SMTP, ensure "App Passwords" are enabled in your Google account (2FA required).

👨‍💻 Author

Shashank Gulati
💌 Email
| 🌍 Full Stack Developer
