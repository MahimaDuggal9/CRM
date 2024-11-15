Frontend = client
To enter client folder = cd client
To run client = npm start

Backend = server
To enter server folder = cd server
To run server = node index.js


Description
In the frontend, we fil a form to add or update contact details. 
When we click on submit, it sends the data using  POST to the backend server. 
The backend takes that data and saves it in a MySQL database. 
If we want to see all contacts, the frontend sends a GET request to the backend, which gets the list from MySQL and shows it on the page.

Database= MySQL
 user: 'root', 
  password: 'Mahi777m@', 
  database: 'contacts_db'
  
Challenges Faced=
i was facing some difficulty in setting mongoDB connection so i used mysql instead
edit button was not updating values so i searched about it from youtube
