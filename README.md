# S81_PetNames

Project Title: Weird Pet Name Generator

Project Overview: A hilariously absurd tool that generates ridiculous pet names based on user preferences.
 Different users will see unique, bizarre name suggestions tailored to their chosen pet type.

Key Features:

User authentication to save and retrieve personalized weird pet names Randomized name generation based on pet type (dog, cat, etc.).
 Community-driven database where users can submit their own weird names Leaderboard for the most upvoted weird pet names.

Tech Stack:

Frontend: React.js,Tailwind.
CSS Backend: Node.js,Express.js, MongoDB
Authentication: Firebase Auth 
Hosting: Frontend, Backend

Why This Project:

 I chose this project because pet names are often either too basic or too serious—this aims to change that with maximum absurdity.
Its a fun way to explore authentication, database interactions, and user-generated content while ensuring every pet has a truly unique (and ridiculous) identity.

## Installation and Development

### Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/s81_petnames.git
   cd s81_petnames

2. Install dependencies:
    npm install
3. Create a .env file in the root directory and add the following content:
    node_modules
    package-lock.json 

## Application Files

### `app.js`

The `app.js` file is the main entry point for the Node.js application. It sets up the Express server and defines the routes for the application.

#### Key Features:

- Initializes the Express application.
- Sets up middleware for parsing JSON and handling CORS.
- Defines routes for the application.
- Starts the server and listens on the specified port.

The connection.js file is responsible for establishing a connection to the MongoDB database using Mongoose.

Key Features:
Connects to the MongoDB database using the connection string from the environment variables.
Handles connection success and error events.