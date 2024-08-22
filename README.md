# plaNest
plaNest is a comprehensive project management platform that allows users to create and manage projects, sprints, and tasks efficiently. Designed to streamline collaboration, plaNest helps users stay organized, assign tasks, manage deadlines, and improve productivity through an intuitive interface and powerful features.

<h1>Features</h1>

<h3>Landing Page:</h3>
Provides a brief overview of the plaNest platform and its benefits.

<h3>User Authentication:</h3>
<h4>Sign Up:</h4> Includes validations for phone number length, email format, and strong password requirements (uppercase, lowercase, special characters). After sign-up, users are redirected to an OTP verification page.
<h4>OTP Verification:</h4>Securely validates user accounts with an OTP sent to the user’s email. The OTP expires after 60 seconds, with error handling for expired or incorrect OTPs.
<h4>Login:</h4>Validations ensure the correct email and password are entered. Includes a "Forgot Password" link that leads to an OTP verification for password reset.

<h3>Home Page: </h3>
Displays tasks assigned to the logged-in user with search, filter, and sorting options for easy navigation.

<h3>Project Management</h3>
<h4>Project Page:</h4>Lists all user-created and assigned projects. Features search, filter, and project deletion (only for user-created projects). Users can also create new projects via a pop-up form.
<h4>Sprint Page:</h4>Displays all sprints within a project, including clickable tasks, sprint status, and deadlines. Sprints are automatically updated based on task statuses. The page also includes search, filter, and sorting options, and a form for adding new sprints or members.
<h4>Taskstable Page:</h4>A detailed view of all tasks within a sprint, including task name, label, category, status, priority, deadline, reporter, assignee, and a delete option. Tasks are searchable and sortable, with filtering options by status, priority, category, and reporter. The page also shows task counts, including done and in-progress tasks.
<h4>Task Details Page:</h4>The Task Details Page provides an in-depth view of each task within a sprint. It includes comprehensive information such as the task name, description, label, category, status, priority, start date, deadline, reporter, assignee, and any file attached during task creation. Supported file types include images, videos, Excel, Word, and PDF documents. The page also features a comment section where project members can discuss the task, ask questions, or provide updates. Users can edit or delete their comments, with each comment showing the date and time it was posted. Additionally, the task status can be updated from "In Progress" to "Done" by the assignee once the task is completed.

<h3>User Profile:</h3>
Displays user information, with options to update personal details and change the password. Includes a log-out button.

<h3>Sidebar Navigation:</h3>
Includes shortcuts to the home, profile, projects, pricing/upgrading plans, and theme switching (light/dark mode).

#Technologies Used:
<hh3>Frontend:</h3> HTML, CSS, JavaScript
<h3>Backend:</h3> PHP
<h3>Database:</h3> MySQL
<h3>Email Handling:</h3> PHPMailer
<h3>Hosting/Server:</h3> XAMPP for local development
