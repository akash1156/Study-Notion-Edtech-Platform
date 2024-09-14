# Study-Notion-Edtech-Platform

**Study Notion** is an ED Tech (Education Technology) web application developed using the MERN stack. 

# Note

This project is intended as a learning tool and can be used as a sample project for educational or personal purposes. 

## Features

- **User Authentication:** Secure user registration and authentication using JWT (JSON Web Tokens). Users can sign up, log in, and manage their profiles with ease.
- **Courses and Lessons:** Instructors can create and edit courses. Students can enroll in courses, access course materials, and track their progress.
- **Progress Tracking:** Students can track their progress in enrolled courses, view completed lessons, scores on quizzes and assignments, and overall course progress.
- **Payment Integration:** Integration with Razorpay for secure payment processing. Users can make payments for course enrollment and other services using various payment methods supported by Razorpay.
- **Search Functionality:** Built-in search feature to easily find courses, lessons, and resources.
- **Instructor Dashboard:** Comprehensive dashboard for instructors to view information about their courses, students, and income. Includes charts and visualizations for monitoring course performance and income.

## Important

- **Backend Directory:** The backend code is located in the `server` folder.
- **Categories Setup:** Before uploading courses, create categories (e.g., web dev, Python). Create categories by signing up as an Admin. To become an Admin, sign up as a student or instructor, then change the `accountType` to `Admin` in the database under the users model.

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/your-repository.git
   cd your-repository
2. **Install Required Packages**
   Navigate to the project directory and install the required packages:

     ```bash
         cd Study-Notion-master
         npm install

 Then, navigate to the server directory and install the server-side packages:
  
    ````bash
         cd server
         npm install


3. **Set Up Environment Variables**

   - Create `.env` files in both the root directory and the `/server` directory.
   - Add the required environment variables, such as database connection details, JWT secret, and any other necessary configurations.
   - Check the `.env.example` files in each directory for more information on the required variables.
  
4. **Start the development server.**

      ```bash
      npm run dev
5.  Open the project in your browser at http://localhost:3000 to view your project.





