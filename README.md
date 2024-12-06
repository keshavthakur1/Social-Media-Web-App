# **Sociopedia - Community Web App**

**Sociopedia** Developed a Full-stack social app with secure JWT authentication for developer connections and expertise sharing.Implemented various features, including registration validation, profile picture uploading, and a dynamic home page.Users can perform actions such as viewing, adding, editing, deleting, liking, disliking, commenting on posts, and more.. Built with the MERN stack, it provides seamless features like user authentication, post creation, commenting, and real-time updates.

---

## **Directory Structure**


Project/ ├── client/ │ ├── public/ │ │ ├── index.html │ │ ├── manifest.json │ │ └── robots.txt │ ├── src/ │ │ ├── components/ │ │ │ ├── FlexBetween.jsx │ │ │ ├── Friend.jsx │ │ │ ├── UserImage.jsx │ │ │ └── WidgetWrapper.jsx │ │ ├── scenes/ │ │ │ ├── homePage/ │ │ │ │ ├── index.jsx │ │ │ ├── loginPage/ │ │ │ │ ├── Form.jsx │ │ │ │ └── index.jsx │ │ │ ├── navbar/ │ │ │ │ └── index.jsx │ │ │ └── profilePage/ │ │ │ └── index.jsx │ │ ├── widgets/ │ │ │ ├── AdvertWidget.jsx │ │ │ ├── FriendListWidget.jsx │ │ │ ├── MyPostWidget.jsx │ │ │ ├── PostsWidget.jsx │ │ │ ├── PostWidget.jsx │ │ │ └── UserWidget.jsx │ │ ├── state/ │ │ │ └── index.js │ │ ├── App.js │ │ ├── index.js │ │ ├── setupTests.js │ │ └── theme.js │ ├── .gitignore │ ├── package-lock.json │ ├── package.json │ └── README.md ├── server/ │ ├── controllers/ │ │ ├── auth.js │ │ ├── posts.js │ │ └── users.js │ ├── data/ │ │ └── index.js │ ├── middleware/ │ │ └── auth.js │ ├── models/ │ │ ├── Posts.js │ │ └── Users.js │ └── index.js ├── node_modules/ └── package.json

---

## **Features**

- **User Authentication**: Secure login and registration using JWT.
- **Create and Manage Posts**: Users can create, edit, and delete posts with text, images, or videos.
- **Engagement Features**: Commenting, liking, and sharing posts.
- **Responsive Design**: Fully optimized for mobile, tablet, and desktop devices.
- **Profile Management**: Personalized user profiles with avatars, bio, and post history.
- **Real-time Updates**: Instant content updates using WebSockets.

---

## **Setup and Usage**

### **Prerequisites**

Ensure you have the following installed:
- **Node.js** (v14+)
- **MongoDB** (running locally or on a cloud platform like MongoDB Atlas)
- **npm**

---

### **Environment Setup**

1. Create a `.env` file in the **root directory** of the project.
2. Add the following environment variables:



---

### **Backend**

1. **Navigate to the Backend Directory**:
```bash
cd server

Technologies Used
Frontend
React.js: For building the user interface.
Tailwind CSS: For styling.
Redux: For state management.
Backend
Node.js: Backend runtime.
Express.js: For building RESTful APIs.
MongoDB: Database for storing user and post data.
Cloudinary: For managing and storing media files.
Features in Progress
Notifications: Real-time notifications for user interactions.
Messaging: Direct messaging between users.
Admin Panel: Moderation tools for managing content and users.

The backend server script is index.js in the project root.
Ensure all required packages from package.json are installed (npm install).
Use nodemon to run the server for automatic restarts on file changes.
Contributions and Feedback
This project was developed independently without external funding. Contributions and feedback are welcome through GitHub issues and pull requests.
