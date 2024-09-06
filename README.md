# Blog Management System 
 `A powerful and efficient Blog Management System built using the MERN stack (MongoDB, Express, React, Node.js). This application allows users to create, read, update, and delete blogs. Additionally, users can view blogs created by others, leave comments, and like posts.`

# Features
- User Authentication: Secure login and registration using JWT authentication.
- Blog Creation and Management: Users can create, edit, and delete their own blogs.
- View Blogs: Users can view blogs created by other users.
- Comment and Like: Users can comment on and like other users' blogs.
- Responsive UI: A modern and responsive user interface designed with React and Tailwind CSS.
- Efficient Backend: RESTful APIs using Node.js and Express.
- Database: MongoDB for data storage, providing fast and scalable data management.

# Tech Stack
- Frontend: React, Tailwind CSS
- Backend: Node.js, Express.js
- Database: MongoDB
- Authentication: JWT (JSON Web Tokens)

bash
Copy code
# Install server dependencies
cd server
npm install

# Install client dependencies
cd ../client
npm install
3. Set Up Environment Variables
Create a .env file in the server directory and add the following environment variables:

env
Copy code
- MONGO_URI=your_mongodb_uri
- JWT_SECRET=your_jwt_secret
PORT=5000
4. Run the Application
Open two terminals: one for the client and one for the server.

bash
Copy code
# Run server
cd server
npm run dev

# Run client
cd ../client
npm start
The application will run on http://localhost:3000 for the client and http://localhost:5000 for the server.

# Contributing
Feel free to fork this repository and contribute by submitting a pull request. Any contributions, issues, and feature requests are welcome!


# For More Contact
For any inquiries, please contact [datardimohsinali@gmail.com].
