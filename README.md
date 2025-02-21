### Project Description and Installation Instructions on GitHub

#### Project Description

This project is a web application with two main interfaces:
1. **Homepage**: Displays information and images related to available courses and bootcamps, along with a contact form.
2. **Admin Panel**: Allows administrators to manage course data, including adding new courses and deleting existing ones.

### 1. Homepage

#### Homepage Contents:
- **Header Section**: Contains the website logo and main navigation links such as "Home", "Courses", and "Login".
- **Courses and Bootcamps List**: Displays a list of courses and bootcamps with images, brief descriptions, and registration links.
- **Events and Activities**: Provides details about upcoming events and activities, such as meetups and seminars.
- **Contact Form**: Offers a form for visitors to contact the website administration by entering their email and message.

### 2. Admin Panel

#### Admin Panel Contents:
- **Courses List**: Displays all registered courses in the system with the option to delete any course.
- **Add New Course**: Provides a form to add new courses to the system.
- **Admin Actions**: Allows the administrator to perform various actions such as deleting courses.

### Key Features
- **View and Manage Courses**: Users can view the list of available courses and log in to get more details. Administrators can manage these courses through the admin panel.
- **Contact Form**: Allows visitors to contact the website administration for more information or inquiries.
- **Add and Delete Courses**: The admin panel enables administrators to add new courses or delete unwanted courses.

### System Components
- **Frontend**: Built using HTML, CSS, and JavaScript, with EJS templates for data rendering.
- **Backend**: Developed using Node.js and Express.js to handle HTTP requests and interact with the database.
- **Database**: Uses MongoDB to store and manage course and bootcamp data.

### Installation and Usage Instructions

#### System Requirements
- Node.js (version 12 or later)
- MongoDB

#### Installation Steps



1. **Install Dependencies**
   ```sh
   npm install --silent	
   ```

2. **Set Up the Database**
   - Ensure MongoDB is running on your system.
   - Create a new database in MongoDB.

3. **Configure Environment Variables**
   - Create a `.env` file in the project root and add the following:
     ```
     PORT=8000
     MONGODB_URI=mongodb://localhost:27017/hackathonDB
     SESSION_SECRET=your_secret_key
     ```

3. **Run the Application**
   ```sh
   npm start
   ```

4. **Access the Website**
   - Open your browser and navigate to `http://localhost:8000`.



**Admin User**
admin@gmail.com
1234

