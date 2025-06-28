# flask-mysql-auth-system
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Online Voting System</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
            background-color: #f9f9f9;
            color: #333;
        }
        h1, h2 {
            color: #2c3e50;
        }
        ul {
            margin-left: 20px;
        }
        section {
            margin-bottom: 30px;
        }
    </style>
</head>
<body>

    <h1>Online Voting System</h1>

    <section>
        <p>
            The Online Voting System is a secure, web-based application developed using <strong>Flask</strong> for the backend,
            <strong>HTML/CSS</strong> for the frontend, and <strong>MySQL</strong> for persistent data storage. It streamlines
            the voting process by allowing registered users to vote online. To enhance security, the system implements
            <strong>OTP-based authentication via Gmail</strong>, ensuring that only verified users can participate in elections.
        </p>
    </section>

    <section>
        <h2>Features</h2>
        <ul>
            <li><strong>OTP-Based User Authentication</strong>: Users receive a One-Time Password (OTP) via Gmail for secure login verification.</li>
            <li><strong>Secure Registration and Login</strong>: Unique voter credentials with session-based login to ensure identity validation.</li>
            <li><strong>Vote Casting</strong>: Each user is allowed to vote once per election, with backend checks for duplication.</li>
            <li><strong>Admin Panel</strong>: Administrators can create elections, manage candidates, and view real-time results.</li>
            <li><strong>Automatic Result Calculation</strong>: System calculates and displays results after the election ends.</li>
            <li><strong>Clean User Interface</strong>: HTML and CSS-based responsive design for an intuitive voting experience.</li>
        </ul>
    </section>

    <section>
        <h2>Technologies Used</h2>
        <ul>
            <li><strong>Backend:</strong> Flask (Python)</li>
            <li><strong>Frontend:</strong> HTML, CSS</li>
            <li><strong>Database:</strong> MySQL</li>
            <li><strong>Email Service:</strong> SMTP (Gmail) for OTP-based authentication</li>
            <li><strong>Session Management:</strong> Flask-Login or built-in session support</li>
        </ul>
    </section>

    <section>
        <h2>Benefits</h2>
        <ul>
            <li>Ensures secure, email-verified access to voting</li>
            <li>Eliminates the need for physical polling setups</li>
            <li>Enhances transparency, integrity, and accessibility of the voting process</li>
            <li>Ideal for institutions, events, and internal organizational elections</li>
        </ul>
    </section>

    <section>
        <h2>Conclusion</h2>
        <p>
            This project offers a modern, secure, and accessible approach to digital voting using Flask and OTP-based Gmail verification.
            It serves as an effective solution for small to medium-scale elections requiring a balance between security and simplicity.
        </p>
    </section>

</body>
</html>
