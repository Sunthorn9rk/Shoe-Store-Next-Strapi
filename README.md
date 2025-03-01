# My Project (Next.js + Strapi)

This is a full-stack e-commerce project built using **Next.js** for the frontend and **Strapi** for the backend.

## Images
![Uploading LandingPage.png…]()


2️⃣ Setup Environment Variables
Create an .env file inside both frontend and backend, and add the necessary configurations.

Frontend (frontend/.env)

NEXT_PUBLIC_STRAPI_API_TOKEN=http://localhost:1337

NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=your_stripe_public_key

Backend (backend/.env)

HOST=0.0.0.0

PORT=1337

APP_KEYS=YOUR_APP_KEYS

API_TOKEN_SALT=YOUR_APP_SALT

ADMIN_JWT_SECRET=YOURJWT_SECRET

TRANSFER_TOKEN_SALT=YOUR_TRANSFER_TOKEN_SALT

# Database

DATABASE_CLIENT=sqlite

DATABASE_FILENAME=.tmp/data.db

JWT_SECRET=YOUR_JWT_SECRET

# Urls

STRIPE_KEY=YOUR_STRIPE_KEY

CLIENT_URL=http://localhost:3000

 Run the Project
 
#  frontend

cd shoe-store-frontend

npm run dev

# backend

cd shoe-store-backned

npm start
