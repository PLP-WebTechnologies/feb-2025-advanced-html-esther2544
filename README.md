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
    <meta esther="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Web Page</title>
</head>
<body>
    <!-- Ordered List with Roman Numerals -->
    <h2>Steps to Create a Website:</h2>
    <ol type="I">
        <li>Plan your content</li>
        <li>Design the layout</li>
        <li>Write the HTML</li>
        <li>Add styling with CSS</li>
        <li>Implement functionality with JavaScript</li>
    </ol>

    <!-- External Image from Pexels -->
    <h2>Sample Image:</h2>
    <img src="https://images.pexels.com/photos/268533/pexels-photo-268533.jpeg" 
         alt="Beautiful landscape" 
         width="500"
         style="border: 2px solid #333; border-radius: 8px;">

    <!-- Contacts Table -->
    <h2>Contact List:</h2>
    <table border="1" cellpadding="8" style="border-collapse: collapse; width: 100%;">
        <thead>
            <tr>
                <th>esther</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>esther</td>
                <td>123 Main St, Anytown</td>
                <td>555-123-4567</td>
                <td>nyamburae299@gmail.com</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>456 Oak Ave, Somewhere</td>
                <td>555-987-6543</td>
                <td>jane@example.com</td>
            </tr>
            <tr>
                <td>Bob Johnson</td>
                <td>789 Pine Rd, Nowhere</td>
                <td>555-456-7890</td>
                <td>bob@example.com</td>
            </tr>
            <tr>
                <td>Alice Brown</td>
                <td>321 Elm Blvd, Anywhere</td>
                <td>555-789-0123</td>
                <td>alice@example.com</td>
            </tr>
            <tr>
                <td>Charlie Wilson</td>
                <td>654 Maple Ln, Everywhere</td>
                <td>555-234-5678</td>
                <td>charlie@example.com</td>
            </tr>
        </tbody>
    </table>

    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form action="/submit" method="post">
        <!-- Text Input Fields -->
        <div style="margin-bottom: 15px;">
            <label for="name">Full Name:</label><br>
            <input type="text" id="name" name="name" 
                   placeholder="Enter your full name" 
                   required
                   minlength="3"
                   style="width: 300px; padding: 8px;">
        </div>

        <div style="margin-bottom: 15px;">
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" 
                   placeholder="Enter your email address" 
                   required
                   style="width: 300px; padding: 8px;">
        </div>

        <div style="margin-bottom: 15px;">
            <label for="password">Password:</label><br>
            <input type="password" id="password" name="password" 
                   placeholder="Create a password" 
                   required
                   minlength="8"
                   style="width: 300px; padding: 8px;">
        </div>

        <div style="margin-bottom: 15px;">
            <label for="dob">Date of Birth:</label><br>
            <input type="date" id="dob" name="dob" 
                   required
                   style="width: 300px; padding: 8px;">
        </div>

        <!-- Dropdown Menu -->
        <div style="margin-bottom: 15px;">
            <label for="country">Country:</label><br>
            <select id="country" name="country" required style="width: 320px; padding: 8px;">
                <option value="" disabled selected>Select your country</option>
                <option value="us">United States</option>
                <option value="ca">Canada</option>
                <option value="uk">United Kingdom</option>
                <option value="au">Australia</option>
                <option value="other">Other</option>
            </select>
        </div>

        <!-- Radio Buttons -->
        <div style="margin-bottom: 15px;">
            <label>Gender:</label><br>
            <input type="radio" id="male" name="gender" value="male" required>
            <label for="male">Male</label><br>
            
            <input type="radio" id="female" name="gender" value="female">
            <label for="female">Female</label><br>
            
            <input type="radio" id="other" name="gender" value="other">
            <label for="other">Other</label>
        </div>

        <!-- Checkboxes -->
        <div style="margin-bottom: 15px;">
            <label>Interests (select all that apply):</label><br>
            <input type="checkbox" id="tech" name="interests" value="technology">
            <label for="tech">Technology</label><br>
            
            <input type="checkbox" id="sports" name="interests" value="sports">
            <label for="sports">Sports</label><br>
            
            <input type="checkbox" id="music" name="interests" value="music">
            <label for="music">Music</label><br>
            
            <input type="checkbox" id="travel" name="interests" value="travel">
            <label for="travel">Travel</label>
        </div>

        <!-- Submit Button -->
        <div>
            <input type="submit" value="Register" 
                   style="padding: 10px 20px; background-color: #4CAF50; color: white; border: none; border-radius: 4px; cursor: pointer;">
        </div>
    </form>
</body>
</html>

