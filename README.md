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
    <title>Advanced HTML5 Elements and Forms</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        header, nav, main, footer {
            padding: 20px;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #333;
        }
        footer {
            background: #f1f1f1;
            padding: 10px;
        }
        table {
            width: 80%;
            margin: auto;
            border-collapse: collapse;
        }
        table, th, td {
            border: 1px solid black;
        }
        th, td {
            padding: 10px;
            text-align: left;
        }
    </style>
</head>
<body>
    <header>
        <h1>Advanced HTML5 Elements and Forms</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>
    <main>
        <section>
            <h2>Ordered List</h2>
            <ol type="I">
                <li>First Item</li>
                <li>Second Item</li>
                <li>Third Item</li>
            </ol>
        </section>
        <section>
            <h2>Image from Pexels</h2>
            <img src="https://www.pexels.com/photo/beautiful-sunset-123456/" alt="Beautiful Sunset" width="500">
        </section>
        <section>
            <h2>Contact List</h2>
            <table>
                <tr>
                    <th>Name</th>
                    <th>Address</th>
                    <th>Mobile</th>
                    <th>Email</th>
                </tr>
                <tr>
                    <td>John Doe</td>
                    <td>123 Street, City</td>
                    <td>+1234567890</td>
                    <td>john@example.com</td>
                </tr>
                <tr>
                    <td>Jane Smith</td>
                    <td>456 Avenue, Town</td>
                    <td>+0987654321</td>
                    <td>jane@example.com</td>
                </tr>
                <tr>
                    <td>Michael Brown</td>
                    <td>789 Boulevard, Village</td>
                    <td>+1122334455</td>
                    <td>michael@example.com</td>
                </tr>
                <tr>
                    <td>Emily White</td>
                    <td>101 Road, County</td>
                    <td>+5566778899</td>
                    <td>emily@example.com</td>
                </tr>
                <tr>
                    <td>David Green</td>
                    <td>202 Lane, District</td>
                    <td>+6677889900</td>
                    <td>david@example.com</td>
                </tr>
            </table>
        </section>
        <section>
            <h2>Registration Form</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" placeholder="Enter your name" required><br><br>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>
                <label for="password">Password:</label>
                <input type="password" id="password" name="password" placeholder="Enter your password" required><br><br>
                <label for="dob">Date of Birth:</label>
                <input type="date" id="dob" name="dob" required><br><br>
                <label for="gender">Gender:</label>
                <input type="radio" id="male" name="gender" value="male"> Male
                <input type="radio" id="female" name="gender" value="female"> Female<br><br>
                <label for="course">Course:</label>
                <select id="course" name="course">
                    <option value="web">Web Development</option>
                    <option value="data">Data Science</option>
                    <option value="ai">Artificial Intelligence</option>
                </select><br><br>
                <label>Interests:</label>
                <input type="checkbox" name="interest" value="coding"> Coding
                <input type="checkbox" name="interest" value="design"> Design
                <input type="checkbox" name="interest" value="marketing"> Marketing<br><br>
                <button type="submit">Register</button>
            </form>
        </section>
    </main>
    <footer>
        <p>Contact us at: info@example.com</p>
    </footer>
</body>
</html>
