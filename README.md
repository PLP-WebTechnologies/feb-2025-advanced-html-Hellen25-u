# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Assignment</title>
</head>
<body>
    <!-- Ordered List with Roman Numerals -->
    <ol type="I">
        <li>First item</li>
        <li>Second item</li>
        <li>Third item</li>
    </ol>

    <!-- External Image from Pexels -->
    <img src="https://www.pexels.com/photo/mirror-lake-reflecting-wooden-house-in-middle-of-lake-overlooking-mountain-ranges-147411/" alt="Beautiful Landscape" width="500">

    <!-- Table of Contacts -->
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
                <td>John Doe</td>
                <td>123 Main St</td>
                <td>123-456-7890</td>
                <td>john.doe@email.com</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>456 Oak Rd</td>
                <td>987-654-3210</td>
                <td>jane.smith@email.com</td>
            </tr>
            <!-- Add more rows as needed -->
        </tbody>
    </table>

    <!-- Registration Form -->
    <form action="#" method="post">
        <fieldset>
            <legend>Registration Form</legend>

            <label for="name">Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your name" required><br><br>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter your password" required><br><br>

            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required><br><br>

            <label for="gender">Gender:</label><br>
            <input type="radio" id="male" name="gender" value="Male">
            <label for="male">Male</label><br>
            <input type="radio" id="female" name="gender" value="Female">
            <label for="female">Female</label><br><br>

            <label for="country">Country:</label>
            <select id="country" name="country">
                <option value="USA">USA</option>
                <option value="UK">UK</option>
                <option value="Canada">Canada</option>
                <option value="Australia">Australia</option>
            </select><br><br>

            <label for="terms">Accept Terms and Conditions:</label>
            <input type="checkbox" id="terms" name="terms" required><br><br>

            <input type="submit" value="Submit">
        </fieldset>
    </form>

    <!-- Multimedia Elements -->
    <audio controls>
        <source src="audio-file.mp3" type="audio/mp3">
    </audio>

    <video width="320" height="240" controls>
        <source src="video-file.mp4" type="video/mp4">
    </video>
</body>
</html>

