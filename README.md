# Role-Based-Access-Control
This project implements a Role-Based Access Control (RBAC) system that allows users to log in based on different roles: Admin, Editor, and Viewer.

Key Features
  Responsive Design: The system is designed to be accessible across devices of all screen sizes (desktops, tablets, and mobile phones).
  Error Handling: Provides error messages for incorrect username or password and ensures proper role-based access.
  Role-Specific Pages: Users are redirected to different pages based on their roles (Admin, Editor, or Viewer).
  Navigation: Seamless flow between the Home Page, Login Page, and Role-Specific Pages with a "Back to Home" button.
  Static Credentials for Testing: Static usernames and passwords are provided for each role for testing login functionality.

Technologies Used:
  HTML: Used for structure and layout.
  CSS: Used for styling, including responsive design using basic media queries.
  JavaScript: Used for logic (role selection, login validation, and redirection).
  Font Awesome: Used for icons (e.g., for buttons).

PROJECT STRUCTURE:
/project-directory
    /index.html       # Home Page with role selection
    /login.html       # Login Page for user authentication
    /admin.html       # Admin Page with admin functionalities
    /editor.html      # Editor Page with editor functionalities
    /viewer.html      # Viewer Page with viewer functionalities
    /login.css        # Styling for the login page
    /styles.css       # General styling (including responsive design)
    /images/           # Optional images (e.g., icons or background)


WORKING:
  Home Page (index.html):
    The user can select a role (Admin, Editor, or Viewer) using buttons on the homepage. After selecting a role, they are redirected to the login.html page.
  
  Login Page (login.html):
    The user enters their username and password.
    The system validates the credentials based on the selected role from the URL.
    If the credentials match the role, the user is redirected to their respective role page (Admin, Editor, or Viewer).
    If the credentials are incorrect, an error message is displayed: "Wrong username or password."
  
  Role-Specific Pages:
    Admin Page (admin.html): Includes functionalities such as viewing reports, managing users, and configuring settings.
    Editor Page (editor.html): Includes functionalities such as editing content, managing articles, and previewing drafts.
    Viewer Page (viewer.html): Allows users to view content and reports.
  
  Static Credentials for Testing:
    The login system uses the following static credentials for testing purposes:
    
    Admin:
    Username: admin
    Password: admin123
    
    Editor:
    Username: editor
    Password: editor123
    
    Viewer:
    Username: viewer
    Password: viewer123
    
  These credentials are hardcoded into the JavaScript for simplicity. Users must enter the correct credentials based on the role they selected on the Home Page.
  Error Handling
  If the username or password entered is incorrect, the system will display an error message:
  "Wrong username or password."
  If the user tries to access a role page without valid credentials, they will be redirected back to the login page with the error message.

Responsive Design
  The project uses CSS to ensure that the interface adjusts based on the device's screen size. Whether accessed from a desktop, tablet, or mobile phone, the layout will adjust to provide a smooth user experience.

Known Issues
  Currently, the login system uses static credentials. In a real-world application, credentials would typically be checked against a backend database.
To Do / Future Enhancements
  Implement dynamic backend authentication (using a server or database) to manage user credentials.
  Add password recovery functionality for users.
  
THANK YOU
