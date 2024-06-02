## Install Dependencies
npm install

## Run Postgres
Run Postgres either locally or on the cloud (e.g., neon.tech).

## Set up Environment Variables
Copy over all .env.example files to .env
Update .env file with the right database URL

## Database Migration and Seeding
Go to packages/db
npx prisma migrate dev
npx prisma db seed

## Run User App
Go to apps/user-app
npm run dev

## Testing
Try logging in using:
Phone: 1111111111
Password: alice (See seed.ts)
