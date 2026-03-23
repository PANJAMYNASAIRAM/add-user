##Project Description

This project is a simple User Details Form Validation built using JavaScript. It validates user inputs such as Name and Email to ensure that required fields are not left empty.

The form provides instant feedback to users by displaying error messages when fields are left blank, improving overall user experience and preventing invalid submissions.

##Features

🧑‍💻 Name Field Validation
Displays an error message if the name field is empty 

📧 Email Field Validation
Ensures the email field is not empty
Shows error message if left blank 

⚡ Real-time Validation
Validation occurs when the user leaves the input field (blur event) 

🚫 Prevents Form Submission
Stops form submission if required fields are empty 

📢 User-friendly Error Messages
Simple and clear validation messages

##Technologies Used

HTML5 – Form structure 

CSS3 – Styling 

JavaScript (ES6) – DOM manipulation and validation logic 

##Installation Steps

1. Clone the repository git clone https://github.com/PANJAMYNASAIRAM/add-user.git
2. Go to project folder "cd add-user"
3. Install dependencies "npm install"
4. Start the project "npm start"

##Live Demo

https://PANJAMYNASAIRAM.github.io/add-user 



##How It Works
User enters name and email
When the user leaves a field:
Checks if the field is empty
Displays error messages if validation fails
Prevents form submission using event.preventDefault() 

##📂 Project Structure
project-folder/
│
├── index.html
├── style.css
└── script.js
📸 Use Case

This project can be used in:

Registration forms
Contact forms
User onboarding forms
💡 Future Enhancements
Add email format validation (e.g., user@example.com
)
Add required field indicators (*)
Add success message after submission
Integrate with backend (API)
⚠️ Note (Small Fix Needed)

Your code is missing a declaration for:

let nameEl = document.getElementById("name");
let addUserFormEl = document.getElementById("addUserForm");
