
# HibaDev Web Portfolio

This is my personal portfolio built using **WordPress** and the **BeTheme** theme. It showcases my web development skills, along with customizations made to the theme to fit my needs.

🔗 [Visit My Portfolio](https://hiba.dev)

---

## 🚀 Technologies Used:
- **Platform:** WordPress
- **Theme:** BeTheme
- **Design Customizations:** Adjustments made to BeTheme to match my personal branding and design.
- **SEO Optimization:** Basic SEO implementation for better visibility.

---

## 🖥️ Key Features:
- Fully responsive design
- Custom theme modifications to enhance appearance and functionality
- Clean, modern aesthetic for an impressive presentation of my work

---

## ⚙️ Setup Instructions:
To get this project running locally, follow these steps:

```bash
# Clone the repository
git clone  https://github.com/hiba-trifi/Web-Portfolio.git

# Navigate into the project directory
cd Web-Portfolio

# Set up WordPress and BeTheme
# Follow WordPress and BeTheme installation instructions
```

---

## 🌍 Deploying to a cPanel Host:

If you have cPanel access, follow these steps to deploy this project on your domain:

1. **Prepare Files:**
   - Download this repository to your local computer (or clone the repo).
   - Make sure you have the **WordPress** files, including the **wp-content** folder (which includes your theme, plugins, and uploads).

2. **Upload Files to cPanel:**
   - Log in to your cPanel account.
   - Navigate to **File Manager**.
   - Go to the **public_html** directory (or any other directory where you want your site).
   - Upload the **WordPress files** (including your theme and content) from your local system.

3. **Create a MySQL Database:**
   - In cPanel, go to **MySQL Databases**.
   - Create a new database and user, and assign the user to the database with full permissions.
   - Note down the database name, username, and password for later use.

4. **Configure wp-config.php:**
   - In **File Manager**, open the **wp-config.php** file located in the WordPress directory.
   - Update the database details (name, username, password) you created earlier.

   Example:
   ```php
   define('DB_NAME', 'your_db_name');
   define('DB_USER', 'your_db_user');
   define('DB_PASSWORD', 'your_db_password');
   define('DB_HOST', 'localhost');
   ```

5. **Import the Database:**
   - Go to **phpMyAdmin** in cPanel.
   - Select the database you created.
   - Import the **database file** (usually `.sql` or `.xml` from your local WordPress installation) into the database.

6. **Install WordPress & BeTheme:**
   - If you haven't already installed WordPress, run the WordPress installation from your domain.
   - Go to the **Themes** section in the WordPress dashboard and install the **BeTheme** theme (either manually or via the theme upload feature).

7. **Check Site:**
   - After uploading the files and setting up the database, visit your domain (e.g., `http://yourdomain.com`) and make sure your portfolio site loads correctly.

---

## 📬 Contact Me:
Feel free to reach out to me through the following channels:

- **Email:** trifi.hiba.solicode@gmail.com
- **GitHub:** [github.com/hiba-trifi](https://github.com/hiba-trifi)
- **LinkedIn:** [linkedin.com/in/hibadev](https://www.linkedin.com/in/hibadev/)

---

## 📝 License:
MIT License — You are free to fork, clone, or modify this repository as needed.
```
### Summary of Changes:
- I added a **Deploying to a cPanel Host** section with clear, step-by-step instructions for setting up the site on a cPanel server.
- The instructions cover uploading files, creating a database, and configuring WordPress with BeTheme.
