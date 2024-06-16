<h1>Introduction</h1> <br>
Famous Places Explorer is a web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) that allows users to share and explore famous places they have visited. Users can post about the places they have visited, including the location, and can also view posts made by other users. Each user has the ability to modify or delete only their own posts.
<br>
<h1>Features</h1> <br>
<b>User Authentication:</b> Secure login and registration using JWT tokens. <br>
<b>Create Posts:</b> Users can add new posts about famous places they have visited. <br>
<b>View Posts:</b> Users can see posts from all other users. <br>
<b>Edit and Delete Posts:</b> Users can edit or delete only their own posts. <br>
<b>Responsive Design:</b> Optimized for both desktop and mobile devices. <br>
<h1>Technologies Used</h1> 
<h3>Frontend</h3> 
<ul>React.js</ul> 
<ul>Redux (for state management)</ul> 
<ul>Axios (for API calls)</ul> 
<ul>React Router (for routing)</ul> 
<ul>CSS and Bootstrap for styling</ul>
<h3>Backend</h3> 
<ul>Node.js</ul>
<ul>Express.js</ul> 
<ul>MongoDB (with Mongoose)</ul> 
<ul>JSON Web Token (JWT) for authentication</ul> 
<h1>Installation</h1>
<h3>Prerequisites</h3>
<ul>Node.js</ul>
<ul>MongoDB</ul>
<h3>Setup</h3>
1. Clone the repository: <br>
git clone https://github.com/Chandrakant8084/wanderGram-MERN Project.git <br>
cd wanderGram-MERN Project
<br>
2. Install the required dependencies: <br>
npm install<br>
3. Usage <br>
npm start
<br>
<h1>Working</h1>
Register a new user account or log in with an existing account. <br>
Navigate to the "Add Post" section to create a new post about a famous place you have visited. <br>
View posts from other users on the home page. <br>
Edit or delete your posts by navigating to the post and clicking the edit or delete button. <br>

<h3>API Endpoints</h3>
<b>Authentication</b> <br>
POST /api/auth/register: Register a new user. <br>
POST /api/auth/login: Log in an existing user. <br>
<b>Posts</b> <br>
GET /api/posts: Get all posts. <br>
POST /api/posts: Create a new post (authenticated users only). <br>
GET /api/posts/:id: Get a single post by ID. <br>
PUT /api/posts/:id: Update a post by ID (authenticated users only, post owner only). <br>
DELETE /api/posts/:id: Delete a post by ID (authenticated users only, post owner only). <br>
