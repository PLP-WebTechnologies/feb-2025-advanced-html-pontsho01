<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Advanced HTML5 Example</title>
</head>

<body>

    <!-- Header Section -->
    <header>
        <h1>Welcome to Our Website</h1>
    </header>

    <!-- Ordered List with Roman Numerals -->
    <section>
        <h2>Important Steps</h2>
        <ol type="I">
            <li>Sign up</li>
            <li>Verify email</li>
            <li>Complete profile</li>
            <li>Start using the services</li>
        </ol>
    </section>

    <!-- External Image from Pexels -->
    <section>
        <h2>Beautiful Landscape</h2>
        <img src="https://images.pexels.com/photos/459225/pexels-photo-459225.jpeg" alt="Beautiful landscape" width="600">
    </section>

    <!-- Table of Contacts -->
    <section>
        <h2>Contact Information</h2>
        <table border="1">
            <thead>
                <tr>
                    <th>Name</th>
                    <th>Address</th>
                    <th>Mobile</th>
                    <th>Email</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>John tau</td>
                    <td>123 tugela St, Springs</td>
                    <td>076543454</td>
                    <td>johntau@example.com</td>
                </tr>
                <tr>
                    <td>Jane Smith</td>
                    <td>456 Oak St, Rivertown</td>
                    <td>>076543459</td>
                    <td>janesmith@example.com</td>
                </tr>
                <tr>
                    <td>Michael Brown</td>
                    <td>789 Pine St, Hilltop</td>
                    <td>0785558765</td>
                    <td>michaelb@example.com</td>
                </tr>
                <tr>
                    <td>Lisa White</td>
                    <td>101 Maple St, Downtown</td>
                    <td>0115554321</td>
                    <td>lisawhite@example.com</td>
                </tr>
                <tr>
                    <td>James Green</td>
                    <td>202 Birch St, Lakeside</td>
                    <td>555-6789</td>
                    <td>jamesgreen@example.com</td>
                </tr>
            </tbody>
        </table>
    </section>

    <!-- Registration Form -->
    <section>
        <h2>Registration Form</h2>
        <form action="/submit" method="post">
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required><br><br>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter your password" required><br><br>

            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required><br><br>

            <label for="gender">Gender:</label><br>
            <input type="radio" id="male" name="gender" value="male" required>
            <label for="male">Male</label><br>
            <input type="radio" id="female" name="gender" value="female" required>
            <label for="female">Female</label><br><br>

            <label for="interests">Interests:</label><br>
            <input type="checkbox" id="sports" name="interests" value="sports">
            <label for="sports">Sports</label><br>
            <input type="checkbox" id="music" name="interests" value="music">
            <label for="music">Music</label><br>
            <input type="checkbox" id="travel" name="interests" value="travel">
            <label for="travel">Travel</label><br><br>

            <label for="country">Country:</label>
            <select id="country" name="country" required>
                <option value="usa">USA</option>
                <option value="uk">UK</option>
                <option value="canada">Canada</option>
                <option value="india">India</option>
            </select><br><br>

            <input type="submit" value="Register">
        </form>
    </section>

</body>

</html>

