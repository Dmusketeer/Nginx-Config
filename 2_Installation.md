Here are the steps to `install` Nginx on a few commonly used Linux distributions. Depending on your server's operating system, you'll follow the appropriate instructions:

**On Ubuntu/Debian:**

1. Open a terminal window.

2. Update the package list to ensure you have the latest information about available packages:

   ```bash
   sudo apt update
   ```

3. Install Nginx:

   ```bash
   sudo apt install nginx
   ```

4. After the installation is complete, Nginx should start automatically. You can check its status with:

   ```bash
   sudo systemctl status nginx
   ```

   This command should show that Nginx is active and running.

**On CentOS/RHEL:**

1. Open a terminal window.

2. Update the package list:

   ```bash
   sudo yum update
   ```

3. Install Nginx:

   ```bash
   sudo yum install nginx
   ```

4. Start Nginx and enable it to start automatically at boot:

   ```bash
   sudo systemctl start nginx
   sudo systemctl enable nginx
   ```

5. Check the status to ensure Nginx is running:

   ```bash
   sudo systemctl status nginx
   ```

   It should indicate that Nginx is active and running.

**On CentOS/RHEL 8 (using dnf):**

If you are using CentOS/RHEL 8, you can use the `dnf` package manager instead of `yum`:

1. Open a terminal window.

2. Update the package list:

   ```bash
   sudo dnf update
   ```

3. Install Nginx:

   ```bash
   sudo dnf install nginx
   ```

4. Start Nginx and enable it to start automatically at boot:

   ```bash
   sudo systemctl start nginx
   sudo systemctl enable nginx
   ```

5. Check the status:

   ```bash
   sudo systemctl status nginx
   ```

Now, Nginx is installed and running on your server. You can access the default Nginx web page by entering your server's IP address or domain name in a web browser. For example, if your server's IP address is `your_server_ip`, you can access the Nginx welcome page by going to `http://your_server_ip` in your browser.

You've successfully installed Nginx! You can now proceed with configuring and using Nginx for your specific web hosting needs.