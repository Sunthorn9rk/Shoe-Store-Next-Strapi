# My Project (Next.js + Strapi)

This is a full-stack e-commerce project built using **Next.js** for the frontend and **Strapi** for the backend.

## Images
![LandingPage](https://github.com/user-attachments/assets/8ae714d8-ad41-4b96-bf84-b8cdf2b3fd9d)
![CategoryPage](https://github.com/user-attachments/assets/c9804c65-2746-4428-b2bc-b2970bd407f5)
![ProductPage](https://github.com/user-attachments/assets/7dd18b40-e599-44ea-b738-cc912e6d5c08)
![CartPage](https://github.com/user-attachments/assets/a256d99c-0c5e-4a3c-847b-84ce38f44d9d)
![PaymentPage](https://github.com/user-attachments/assets/a826ec10-6b63-4cb5-9a34-a8f0a7989ac8)



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
