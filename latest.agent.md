<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Student Data Collection Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        h2 {
            background-color: yellow;
            display: inline-block;
            padding: 5px 10px;
        }
        fieldset {
            margin-bottom: 20px;
            padding: 15px;
        }
        legend {
            font-weight: bold;
        }
        label {
            display: inline-block;
            width: 150px;
            margin-bottom: 10px;
        }
        input, select, textarea {
            margin-bottom: 10px;
        }
        .note {
            background-color: yellow;
            display: inline-block;
            padding: 3px;
            font-size: 14px;
        }
        .buttons {
            text-align: center;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<center>
    <h2>Student Data Collection Form</h2>
    <p><i>Please fill all the details carefully. All fields are mandatory. Make sure information is correct.</i></p>
</center>

<form>

    <!-- Personal Information -->
    <fieldset>
        <legend>Personal Information</legend>

        <label>Full Name:</label>
        <input type="text" placeholder="Enter your full name"><br>

        <label>Email:</label>
        <input type="email" placeholder="Enter your email"><br>

        <label>Password:</label>
        <input type="password" placeholder="Enter password"><br>

        <label>Age:</label>
        <input type="number"><br>

        <label>Date of Birth:</label>
        <input type="date"><br>

        <label>Upload Photo:</label>
        <input type="file"><br>
    </fieldset>

    <!-- Academic Information -->
    <fieldset>
        <legend>Academic Information</legend>

        <label>Branch:</label>
        <input type="radio" name="branch"> BCA
        <input type="radio" name="branch"> B.Tech
        <br><br>

        <label>Skills:</label>
        <input type="checkbox"> HTML
        <input type="checkbox"> CSS
        <input type="checkbox"> JavaScript
        <input type="checkbox"> Python
        <br><br>

        <label>Select Year:</label>
        <select>
            <option>--Select Year--</option>
            <option>1st Year</option>
            <option>2nd Year</option>
            <option>3rd Year</option>
            <option>4th Year</option>
        </select><br>

        <label>Portfolio URL:</label>
        <input type="url" placeholder="https://example.com"><br>

        <label>Study Time:</label>
        <select>
            <option>Select</option>
            <option>Morning</option>
            <option>Afternoon</option>
            <option>Evening</option>
        </select><br>

        <label>Preferred Week:</label>
        <select>
            <option>Select</option>
            <option>Weekdays</option>
            <option>Weekend</option>
        </select><br>

        <label>Preferred Month:</label>
        <select>
            <option>Select</option>
            <option>January</option>
            <option>February</option>
            <option>March</option>
        </select><br>

        <label>Date & Time of Admission:</label>
        <input type="datetime-local"><br>
    </fieldset>

    <!-- Feedback Section -->
    <fieldset>
        <legend>Feedback Section</legend>

        <label>Rate Your HTML Knowledge (0-10):</label>
        <input type="range" min="0" max="10"><br><br>

        <label>Write Your Feedback:</label><br>
        <textarea rows="4" cols="50" placeholder="Write your feedback here..."></textarea><br><br>

        <span class="note">Note: Range is between 0 to 10.</span>
    </fieldset>

    <!-- Buttons -->
    <div class="buttons">
        <input type="submit" value="Submit Form">
        <input type="reset" value="Reset Form">
    </div>

</form>

<center>
    <p><b>Thank you for registering!</b> <i>We will contact you soon.</i></p>
</center>

</body>
</html