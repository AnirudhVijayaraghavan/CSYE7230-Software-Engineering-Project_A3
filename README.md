## AI Learning Platform

AI Learning Platform is a Next.js application designed to provide an interactive and comprehensive environment for learning and exploring various aspects of Artificial Intelligence. It integrates a multitude of APIs including PlanetScale DB, Stripe, YouTube, Unsplash, OpenAI, and Google OAuth to offer a diverse and enriched user experience.

## PREREQUISITES

Before you begin, ensure you have met the following requirements:

Node.js and npm installed (see Node.js for installation instructions).

An account and API keys for:

PlanetScale DB
Stripe
YouTube Data API
Unsplash API
OpenAI API
Google OAuth Client

## INSTALLATION

1.Clone the repository:

git clone https://github.com/AnirudhVijayaraghavan/CSYE7230-Software-Engineering-Project_A3.git

cd CSYE7230-Software-Engineering-Project_A3

2. Install dependencies:

npm install


## CONFIGURATION

Create a .env.local file in the root directory of your project and add the following environment variables:

env

PLANETSCALE_DB_URL=your_planetscale_db_url

STRIPE_API_KEY=your_stripe_api_key

YOUTUBE_API_KEY=your_youtube_api_key

UNSPLASH_API_KEY=your_unsplash_api_key

OPENAI_API_KEY=your_openai_api_key

GOOGLE_CLIENT_ID=your_google_client_id

GOOGLE_CLIENT_SECRET=your_google_client_secret

Replace your_* with your actual API keys and credentials.

## Running the Application

To run the application in development mode:

npm run dev

Your app should be available at http://localhost:3000.

## Building for Production

## To create a production build:


npm run build

## To start the production server:


npm start


## Linting

To lint the code:


npm run lint


## Contributing


Contributions are welcome! For major changes, please open an issue first to discuss what you would like to change.
