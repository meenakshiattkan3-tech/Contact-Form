# Contact-Form
This project is a simple and stylish Contact Form built with HTML5 &amp; CSS3. It follows specific user stories to ensure accessibility, responsiveness, and a clean UI.
** start of index.html **

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Contact Form</title>
  <style>
    .form-container {
      background-color: #ffffff; /* ✅ background color */
      border-radius: 10px;      /* ✅ border radius */
      padding: 20px;            /* ✅ padding */
      width: 350px;             /* ✅ width */
    }

    label {
      display: block;
      margin: 10px 0 5px;       /* ✅ margin */
      color: #333333;           /* ✅ font color */
    }

    input,
    textarea {
      width: 100%;              /* ✅ width */
      padding: 10px;            /* ✅ padding */
      margin-bottom: 15px;      /* ✅ margin-bottom */
      border: 1px solid #ccc;
      border-radius: 5px;
      font-size: 14px;
    }

    textarea {
      min-height: 80px;
      resize: vertical;
    }

    button {
      background-color: #4CAF50; /* ✅ background color */
      font-size: 16px;           /* ✅ font size */
      padding: 12px;
      width: 100%;
      border: none;
      border-radius: 6px;
      color: white;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    button:hover {
      background-color: #45a049; /* ✅ hover effect */
    }
  </style>
</head>
<body>
  <div class="form-container">
    <form>
      <h2>Contact Us</h2>
      
      <label for="name">Full Name:</label>
      <input type="text" id="name" name="name" required />

      <label for="email">Email Address:</label>
      <input type="email" id="email" name="email" required />

      <label for="message">Your Message:</label>
      <textarea id="message" name="message" required></textarea>

      <button type="submit">Submit</button>
    </form>
  </div>
</body>
</html>



** end of index.html **

** start of styles.css **

.form-container {
  background-color: #ffffff; /* ✅ background color */
  border-radius: 10px;      /* ✅ border radius */
  padding: 20px;            /* ✅ padding */
  width: 350px;             /* ✅ width */
}

label {
  display: block;
  margin: 10px 0 5px;       /* ✅ margin */
  color: #333333;           /* ✅ font color */
}

input,
textarea {
  width: 100%;              /* ✅ width */
  padding: 10px;            /* ✅ padding */
  margin-bottom: 15px;      /* ✅ margin-bottom */
  border: 1px solid #ccc;
  border-radius: 5px;
  font-size: 14px;
}

textarea {
  min-height: 80px;
  resize: vertical;
}

button {
  background-color: #4CAF50; /* ✅ background color */
  font-size: 16px;           /* ✅ font size */
  padding: 12px;
  width: 100%;
  border: none;
  border-radius: 6px;
  color: white;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

button:hover {
  background-color: #45a049; /* ✅ hover effect */
}

 



** end of styles.css **

