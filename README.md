# form-registration-<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Registration - XAMSE SCHOOL</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(to right, #00c6ff, #0072ff);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .container {
            width: 100%;
            max-width: 420px;
            background: #ffffff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .logo {
            width: 100px;
            height: auto;
            margin-bottom: 10px;
        }
        h2 {
            color: #333;
            margin-bottom: 10px;
        }
        .school-name {
            font-size: 18px;
            color: #555;
            margin-bottom: 20px;
            font-weight: bold;
        }
        .form-group {
            text-align: left;
            margin-bottom: 15px;
        }
        label {
            font-weight: bold;
            display: block;
            margin-bottom: 5px;
        }
        input, select {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 14px;
        }
        button {
            width: 100%;
            background: #0072ff;
            color: white;
            padding: 12px;
            border: none;
            font-size: 16px;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 10px;
            transition: 0.3s;
        }
        button:hover {
            background: #005bb5;
        }
    </style>
</head>
<body>

<div class="container">
    <img src="xamse-logo.png" alt="XAMSE SCHOOL Logo" class="logo">
    <div class="school-name">XAMSE SCHOOLS </div>
    <h2>Student form  Registration</h2>
    <form id="studentForm">
        <div class="form-group">
            <label for="studentID">Student ID:</label>
            <input type="text" id="studentID" name="studentID" required>
        </div>    <div class="form-group">
        <label for="fullName">Full Name:</label>
        <input type="text" id="fullName" name="fullName" required>
            <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Webpage</title>
</head>
<body>
    <h1>Welcome to My Webpage</h1>
    <p>This is a simple introduction to HTML.</p>
    <a href="https://www.w3schools.com/html/">Learn More about HTML</a>
</body>
</html>
    </div>
    <div class="form-group">
        <label for="telephone">Telephone:</label>
        <input type="tel" id="telephone" name="telephone" required>
    </div>
    <div class="form-group">
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
    </div>
    <div class="form-group">
        <label for="gender">Gender:</label>
        <select id="gender" name="gender" required>
            <option value="">Select</option>
            <option value="Male">Male</option>
            <option value="Female">Female</option>
        </select>
    </div>
    <div class="form-group">
        <label for="shift">Shift:</label>
        <input type="text" id="shift" name="shift" required>
    </div>
    <div class="form-group">
        <label for="faculty">Faculty:</label>
        <input type="text" id="faculty" name="faculty" required>
    </div>
    <div class="form-group">
        <label for="photo">Student Photo:</label>
        <input type="file" id="photo" name="photo" accept="image/*" required>
    </div>
    <button type="submit">Register</button>
</form>
        <div class="form-group">
            <label for="fullName">Full Name:</label>
            <input type="text" id="fullName" name="fullName" required>
        </div>
        <div class="form-group">
            <label for="telephone">Telephone:</label>
            <input type="tel" id="telephone" name="telephone" required>
        </div>
        <div class="form-group">
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
        </div>
      <div class="form-group">
            <label for="gender">Gender:</label>
            <select id="gender" name="gender" required>
                <option value="">Select</option>
                <option value="Male">Male</option>
                <option value="Female">Female</option>
            </select>
        </div>
        <div class="form-group">
            <label for="shift">Shift:</label>
            <input type="text" id="shift" name="shift" required>
        </div>
        <div class="form-group">
            <label for="faculty">Faculty:</label>
            <input type="text" id="faculty" name="faculty" required>
        </div>
        <div class="form-group">
            <label for="photo">Student Photo:</label>
            <input type="file" id="photo" name="photo" accept="image/*" required>
        </div>
        <button type="submit">Register</button>
    </form>
</div>

</body>
</html>
