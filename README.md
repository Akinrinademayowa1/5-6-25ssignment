📄 Documentation🖥️
Overview 🌐
The Enhanced Index Page provides an authentication system for both admin and regular users. It features login, registration, and a dashboard with dynamic routing and user-specific functionality. Admins have the ability to manage user accounts, while users have their own personalized pages after logging in. Local storage is used for secure verification during the login and registration process.

Features 🛠️
1. Login Form 🔑
Username Field: Allows users to input their username.

Password Field: Secure input field for users to enter their password.

Submit Button: Submits the login credentials for authentication.

Admin Login:
Static Admin Credentials:

Email: admin@admin.com 📧

Password: admin123 🔒

Admin users with these static credentials can access the admin control panel.

2. Create Account Page (User Registration) 📝
Users can create their own accounts through a separate registration page.

Input Fields:

Username 🧑‍💻

Password (Secure input field) 🔑

Confirm Password 🔄

On submission, user credentials are stored in local storage and used for future logins.

3. Routing 🚀
User-Specific Pages: Once a user is logged in, they are directed to their personalized dashboard or user page, where they can manage their settings.

Admin Panel: The admin has access to a control panel where they can manage users, view reports, and make administrative changes.

4. Sidebar 🧭
A sidebar is available for easy navigation between pages for both admins and users.

Admin Sidebar: Includes options like "Manage Users," "Change Password," and "Logout."

User Sidebar: Includes options like "User Dashboard," "Change Password," and "Logout."

5. Admin Functionality 🛠️
Remove Users: Admin can remove users from the system. ❌

Change User Password: Admin has the ability to change the password for any registered user. 🔄

6. User Functionality 👤
Users can manage their personal settings, including changing their password and viewing their profile. 💼

Upon logging in, users are redirected to their own personalized page or dashboard.

7. Local Storage Verification 💾
Login: When users log in, their credentials are verified against the stored values in local storage for secure access. 🔑

Create Account: User credentials are saved in local storage upon successful registration for easy future login. 📥

The system ensures that only registered users can access their personalized pages.

8. Dark Mode Toggle 🌙
Toggle Button: Allows users to switch between light and dark themes for better readability and a personalized experience. 🌞🌙

9. Logout Option 🚪
Admin Logout: Admin users can log out of the system by clicking the "Logout" option in the sidebar. This will end the admin session and redirect to the login page.

User Logout: Regular users can log out of their personalized pages by clicking the "Logout" option in their sidebar. This will end the user session and redirect to the login page.

User Flow 🏃‍♂️
Login:

Admin users can log in using the static credentials: admin@admin.com (email) and admin123 (password). 🧑‍💻🔑

Regular users log in using the credentials they created on the registration page. 👤🔑

Registration:

Users without an account can click the "Register" link to navigate to the registration page and create a new account. 📝

Routing:

After login, users are directed to their personalized dashboard or user page. 🏠

Admin users are redirected to the admin control panel where they can manage users. ⚙️

Sidebar Navigation:

Admins and users can navigate through different sections of the application via the sidebar. 🧭

Local Storage Verification:

The system stores user credentials and login status in local storage to verify authenticity for future sessions. 💾🔒

Logout:

Both admins and users have the option to log out by clicking the "Logout" option in the sidebar. 🚪

Technologies Used 💻
HTML: Structure of the page. 🏗️

CSS: Styling of page elements, including theme toggling. 🎨

JavaScript: Functionality for login verification, local storage handling, routing, and user authentication. ⚙️

Accessibility Considerations ♿
Keyboard Navigation: Ensure all interactive elements are accessible via keyboard. ⌨️

Screen Reader Support: Provide appropriate labels and roles for screen readers. 🦻

Color Contrast: Maintain sufficient contrast ratios for readability in both light and dark modes. 🎨

Static Admin Credentials ⚙️
Admin Email: admin@admin.com 📧

Admin Password: admin123 🔑

These credentials provide access to the admin dashboard where admin users can manage user accounts, view settings, and perform administrative tasks.

Admin Privileges 🛠️
Remove Users: Admins can remove any user from the system. ❌

Change User Password: Admins can reset or change passwords for any registered user. 🔄

Local Storage Verification 💾
User Authentication: Credentials are stored in local storage after a successful registration, and login requests are verified against the stored data. 🔒

Session Persistence: The user remains logged in even after page reloads or browser restarts, as long as their session is stored in local storage. 🔄

This updated documentation now includes the Logout Option for both users and admins, allowing them to end their sessions securely. Let me know if you need any further adjustments!









