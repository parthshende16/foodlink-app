**Project Title**
FoodLink: Bridging Food Waste with Community Aid

**Description**
FoodLink is a web-based platform designed to minimize food waste and alleviate hunger. It connects food donors (e.g., restaurants, event organizers, households) with volunteers who can distribute leftover food to those in need. Using Firebase for real-time database functionality, the platform allows users to donate and pick up food, track the progress, and mark items as "Picked," which removes them from the database.

**Getting Started**
**Dependencies**
Node.js - Install from https://nodejs.org

Firebase CLI - Install globally via the following command:

npm install -g firebase-tools

**Installing**
Clone the repository to your local machine:
git clone https://github.com/<your-username>/foodlink.git
cd foodlink

**Install any dependencies (if applicable):**
npm install
Make sure to update the Firebase configuration in index.html with your project credentials.

**Executing Program**
To run the project locally, either open index.html directly in your browser or use an editor like VS Code with a live server extension.

**To deploy your project to Firebase Hosting:**
firebase login
firebase init
firebase deploy

**Help**
Ensure that your Firebase rules allow public read and write access if you encounter issues with data visibility.

If Firebase credentials are not configured properly, you may get an error when initializing the Firebase project.

**Author**
Parth Shende
parth.shende123@gmail.com
