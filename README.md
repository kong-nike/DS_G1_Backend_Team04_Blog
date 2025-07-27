DS_G1_Backend_Team04_Blog
Welcome to our Blog Project!
To get the project up and running, follow these steps:

1. Create the Database
Open your command prompt and run:

bash
Copy
Edit
psql -U postgres
Then, create the database:

sql
Copy
Edit
CREATE DATABASE blog;
⚠️ Important: Make sure to update your PostgreSQL password in back/env accordingly.

2. Install Dependencies
Open two terminal windows:

One for the back folder (backend)

One for the front folder (frontend)

In each terminal, navigate to the respective folder and run:

bash
Copy
Edit
npm install
