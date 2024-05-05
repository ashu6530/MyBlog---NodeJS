# MyBlog - A Simple Blogging Website

## Description

MyBlog is a simple blogging website built using Node.js and MongoDB. It allows users to create an account, log in securely, add their blogs, and view them on the website. The authentication system employs password hashing with salt and HMAC, while user sessions are managed using JSON Web Tokens (JWT) with cookies. The application is deployed on AWS Elastic Beanstalk for easy scalability and management.

## Features

1. **User Authentication:**
   - Users can create an account with a username and password.
   - Passwords are securely hashed using salt and HMAC.
   - Authentication is handled using JWT with cookies for maintaining user sessions.

2. **Blog Management:**
   - Authenticated users can add their blogs to the website.
   - Blogs are stored in a MongoDB database.
   - Added blogs are displayed on the website for other users to read.

3. **Deployment:**
   - The application is deployed on AWS Elastic Beanstalk for scalability and reliability.
   - Elastic Beanstalk automates the deployment, scaling, and management of the application.

## Technologies Used

- Node.js: Backend JavaScript runtime environment.
- Express.js: Web application framework for Node.js.
- MongoDB: NoSQL database for storing user data and blogs.
- JWT: JSON Web Tokens for secure authentication.
- AWS Elastic Beanstalk: Cloud deployment and management service.
- HTML/CSS: Frontend development for the website.

## Getting Started

1. Clone the repository:
  
2. Install dependencies:
   cd myblog
   npm install

3. Set up environment variables:
- Create a `.env` file in the root directory.
- Define the following variables:
  ```
  PORT=8000
  MONGODB_URI=your_mongodb_uri
  JWT_SECRET=your_jwt_secret
  ```

4. Run the application: you can use npm and then name of the root file or install nodemon 
   
5. Access the application:
- Open a web browser and navigate to `http://localhost:8000`.

## Contributing

Contributions are welcome! If you'd like to contribute to the project, please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/new-feature`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/new-feature`).
5. Create a new Pull Request.


## Contact

For any inquiries or support, please contact [your-email@example.com](mailto:ashu6530@gmail.com).

## Acknowledgments

- Thanks to [Node.js](https://nodejs.org/) and [MongoDB](https://www.mongodb.com/) for providing powerful tools for building web applications.
- Special thanks to the contributors and open-source community for their valuable contributions and support.



