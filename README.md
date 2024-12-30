#Details
•	Led the creation of a cutting-edge AI Assisted Learning Platform. Adopted an 3-tier architecture with MVC pattern, ensuring clear separation of concerns for easy maintenance and robust security. Applied SDLC principles for efficient project management.
•	Engineered a secure and scalable backend. Implemented strong user authentication using NextAuth and efficient database management with PlanetScale (MySQL) and Prisma ORM.
•	Developed an AI-leveraged course generation system utilizing RESTful APIs. Integrated the OpenAI API to dynamically generate relevant courses and chapters based on user input. Incorporated the YouTube API to fetch and display relevant videos for each chapter.
•	Utilized GitHub Actions for efficient CI/CD, ensuring smooth and continuous integration and deployment. Hosted the platform on DigitalOcean. Employed Next.js with Tailwind CSS for a sleek, responsive user interface. Leveraged ShadCN to manage UI components.
•	Implemented well-structured prompts, using persona pattern as a case study of prompt engineering, to generate course recommendations, quizzes, and summaries of YouTube transcripts.

## Application Demo
Check out our presentation here : 
[![Video Title](https://img.youtube.com/vi/lngtD_pHc_w/0.jpg)](https://www.youtube.com/watch?v=lngtD_pHc_w)

https://www.youtube.com/watch?v=lngtD_pHc_w

""Temporarily down for DB upgrade.""

## AI Learning Platform
YOU CAN CHECK OUT THE APP AT  : [https://assistedinstructai.anirudhvijayaraghavan.me](https://assistedinstructai.anirudhvijayaraghavan.me)

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
