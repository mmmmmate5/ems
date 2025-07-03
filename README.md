Step 1: Start the Backend Server
Open a terminal and run:

cd backend
npm install
npm run dev
The backend will start on http://localhost:3001

Step 2: Start the Frontend Server
Open a second terminal (keep the backend running) and run:
npm install
npm run dev
The frontend will start on http://localhost:5173

Step 3: Open the Website
Once both servers are running, open your web browser and go to:
http://localhost:5173

Important Notes:
You need both servers running - the frontend (port 5173) communicates with the backend (port 3001)

Create a user first - Before you can log in, you need to create a user account using the script:
cd backend
node scripts/create-user.js admin@gmail.com admin

Set up your .env file - Make sure you have a .env file in the backend folder with your database credentials


The website will be accessible at http://localhost:5173 where you can log in with the user credentials you created and start managing events!
