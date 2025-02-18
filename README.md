# wwwolf's PHP Web Shell

**wwwolf's PHP web shell** is a lightweight and reliable PHP script designed to solve common issues encountered with various web shell tools. This tool is designed to provide initial access to the target system, offering a user-friendly and flexible interface.

![Screenshot_2](https://r00t-shell.com/wp-content/uploads/2025/02/wwwolf-php-webshell.png)

## Features

- Password-protected access.
- Compatible with UNIX and Windows systems without additional changes.
- Clears the PHP output buffer for stable and clean execution.
- Sends form data via POST requests, working without modifying the URL.
- Uses the current working directory by default, allowing easy identification of the system type.
- Offers additional features like file upload and remote file fetching.
- Quickly clears the command input field without JavaScript.

## Installation and Usage

> ⚠️ **Warning:** This tool is intended for security research and evaluation only. Unauthorized use is strictly prohibited!

### Step 1: Download the Script

Download the script from the GitHub repository:

```
https://raw.githubusercontent.com/RootShelll/wwwolf-php-webshell/refs/heads/main/wwwolf-php-webshell.php
```

### Step 2: Upload to the Server

Upload the downloaded `wwwolf-php-webshell.php` file to the target server's web directory. For example:

```
/var/www/html/wwwolf-php-webshell.php
```

### Step 3: Access via Web Browser

Open your browser and access the script as follows:

```
http://targetsite.com/wwwolf-php-wwwolf-php-webshell.php
```

### Step 4: Password Protection (Optional)

When you open the script, if password protection is enabled, you will be prompted to enter a password. To change the default password, open the script file and find the following line:

```
$password = 'default_password';
```

Replace `default_password` with a strong password of your choice and save the file.

### Step 5: Execute Commands

After accessing the script, enter the command you want to execute in the input field and click the "Submit" button. For example:

```
whoami
```

This command will show the current username.

### Step 6: File Upload

Use the script's file upload feature to upload files to the target server:

- **Local File Upload:** Click the "Choose File" button to select a file from your computer and press "Upload."
- **Remote File Fetch:** Enter the file's URL in the "Remote File URL" field and click "Fetch."

### Step 7: Change Working Directory

To change the current working directory, enter the new directory path in the "Change Working Directory" field and click "Change." For example:

```
/var/www/html/new_directory
```

## Security and Legal Disclaimer

> ⚠️ **Important:** This script is developed solely for security research and evaluation purposes. Using it for unauthorized access to systems is illegal and may lead to severe legal consequences. Please use this tool only for permitted and ethical purposes.

## Resources

- [GitHub Project](https://github.com/RootShelll/wwwolf-php-webshell)
- [Web Sites](https://r00t-shell.com/wwwolfs-php-web-shell/)
- [Official PHP Documentation](https://www.php.net/)

## Conclusion

wwwolf’s PHP Web Shell is a powerful PHP script for system management and security assessments. However, avoid unethical or illegal usage.

> 💡 **Tip:** To make the script more secure, you can add IP restrictions, strengthen password protection, or restrict access using htaccess.

---

Happy and safe testing!
