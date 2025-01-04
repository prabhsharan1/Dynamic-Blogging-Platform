# Dynamic Blogging Platform

Welcome to the **Dynamic Blogging Platform** project! This platform serves as a robust content management system where users can create, edit, and share their blogs effortlessly. Developed using **ASP.NET**, **C#.Net**, and **MS SQL**, this project is ideal for final-year students looking for a major project idea.

---

## 📝 Features

- **User Registration**: New users can register to create their own blogs.
- **Create and Edit Blogs**: Registered users can write, edit, and update their blogs with ease.
- **Anonymous Access**: Blogs can be read by any user without requiring registration.
- **User Profiles**: Users can update their profile information and change profile photos.
- **Search Functionality**: Search blogs by keywords for quick access.
- **Comments**: Engage with content through a comments section.

---

## 💻 Technologies Used

- **Backend**: ASP.NET, C#.Net
- **Frontend**: HTML, CSS, JavaScript
- **Database**: MS SQL Server
- **Themes and Styling**: ASP.NET Themes

---

## 📂 Project Structure

Below is the file structure for the project:

- **App_Code/**: Contains backend code files.
- **App_Data/**: Includes database-related files.
- **App_Themes/**: Houses theme-related assets.
- **Default.aspx**: Homepage of the application.
- **MasterPage.master**: Master layout for consistent UI across pages.
- **Web.config**: Application configuration file.
- **Web.sitemap**: Sitemap for navigation.

### Core Pages:

1. **addblog.aspx**: Page for adding new blogs.
2. **editblog.aspx**: Page for editing existing blogs.
3. **showblog.aspx**: Displays blogs to all users.
4. **register.aspx**: User registration page.
5. **login.aspx**: User login page.
6. **changepwd.aspx**: Change password functionality.
7. **changeprofile.aspx**: Update user profile information.
8. **changephoto.aspx**: Update user profile picture.
9. **comments.aspx**: Comments section for blogs.
10. **forgotpassword.aspx**: Password recovery page.
11. **searchblogs.aspx**: Search functionality for blogs.

---

## 🛠 Setup and Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/prabhsharan1/e-blogging-platform.git
   cd e-blogging-platform
   ```

2. **Set Up Database**:
   - Use the files in the `App_Data` folder to set up the MS SQL Server database.

3. **Configure Web.config**:
   - Update the database connection string in `Web.config` to match your local SQL Server setup.

4. **Run the Application**:
   - Open the project in Visual Studio.
   - Build and run the project.

---

## 🎉 Contributions

We welcome contributions to enhance this project! Please fork the repository, make your changes, and submit a pull request.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify it for your needs.


