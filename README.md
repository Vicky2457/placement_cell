<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">
</head>

<body>
    <h1>Placement Cell Web Application</h1>
    <p>This is the README for a web application for managing student placement data. The application is built using Node.js and Express, with MongoDB as the database. It includes various features related to student information, interviews, results, and job listings.</p>

   <h2>Features</h2>
    <ul>
        <li><strong>Employee Dashboard</strong>: Allows employees to view a list of all students.</li>
        <li><strong>Add Student</strong>: Provides a form for adding new students, including details such as batch, name, email, college, and more.</li>
        <li><strong>Download Student Data</strong>: Generates and downloads student data in CSV format.</li>
        <li><strong>Interview Management</strong>: Allows employees to allocate students to interviews, record results, and view a list of companies for interviews.</li>
        <li><strong>Result Management</strong>: Enables the update of interview results and tracks which students have completed interviews.</li>
        <li><strong>Job Listings</strong>: Provides job listings with details like job type, publication date, location, and salary information.</li>
        <li><strong>Authentication</strong>: Utilizes Passport.js for user authentication, allowing employees to sign in and out.</li>
    </ul>

  <h2>Getting Started</h2>
    <ol>
        <li><strong>Install Dependencies</strong>:
            <pre>npm install</pre>
        </li>
        <li><strong>Environment Configuration</strong>:
            <p>Create a <code>.env</code> file based on the provided <code>.env.example</code>. Adjust the configurations as needed.</p>
        </li>
        <li><strong>Database Setup</strong>:
            <p>Set up MongoDB and configure the database connection in <code>.env</code>.</p>
        </li>
        <li><strong>Run the Application</strong>:
            <pre>npm start</pre>
            <p>The server will start, and you can access the application in your web browser.</p>
        </li>
    </ol>

   <h2>Usage</h2>
    <p>Navigate to <a href="http://localhost:7000/">http://localhost:7000/</a> to access the home page. Sign in as an employee using your credentials. Explore and use the various features of the application.</p>


</body>

</html>
