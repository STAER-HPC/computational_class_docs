# Remote Access to Linux via SSH

## Accessing Linux Remotely Using SSH

> [!IMPORTANT]
> To access Linux remotely, ensure your device is connected to the Skoltech network or use the Skoltech VPN.

1. **Ensure Network Access**
   - Confirm that your device is connected to the Skoltech network or use a VPN if you're off-campus.

2. **Using SSH for Remote Access**

   ### On Windows:
   - **Step 1:** Download and install an SSH client like PuTTY from the official website.
   - **Step 2:** Open PuTTY and enter the IP address or hostname of the Linux server in the "Host Name" field.
   - **Step 3:** Ensure the connection type is set to "SSH" and click "Open" to initiate the connection.

   ### On Linux:
   - **Step 1:** Open a terminal window.
   - **Step 2:** Use the SSH command to connect, e.g., `ssh username@hostname`, replacing `username` with your Skoltech username and `hostname` with the server's address.

   ### On macOS:
   - **Step 1:** Open the Terminal application.
   - **Step 2:** Use the SSH command to connect, e.g., `ssh username@hostname`.

   > ![Screenshot Required](#) - **Insert a screenshot of the SSH setup or terminal command here for each operating system.**

3. **Log in with Your Credentials**
   - Enter your Skoltech account username and password when prompted.

4. **Session Management**
   - Once you're done, always **log out** by typing `exit` in the terminal to properly close your session.

   > [!IMPORTANT]
   > Properly logging out ensures the security of your session and allows others to connect without issues.

## Use of Shared Storage

> [!CAUTION]
> Local data on the machine will be deleted within 30 days. To save your data, transfer it to your folder on the shared storage system.

   Information regarding the location of the shared storage and access instructions should be provided.

## Continuing Processes in the Background

> [!IMPORTANT]
> You can continue running processes in the background and resume them later by reconnecting via SSH. However, ensure no critical processes are left unattended.
