# Remote Access to Windows

## Accessing Windows Remotely

> [!IMPORTANT]
> To access Windows remotely, you must be connected to the Skoltech network.

1. **Ensure Network Access**
   - Confirm that your device is connected to the Skoltech network.

2. **Setting Up Remote Desktop Protocol (RDP)**

   ### On Windows:
   - **Step 1:** Open the Start menu and search for "Remote Desktop Connection."
   - **Step 2:** Click on "Remote Desktop Connection" to open the application.
   - **Step 3:** In the "Computer" field, enter the hostname provided:
     - `b2007cel[01-05]V` for P5 machines [(link to the documentation)](https://sci.skoltech.ru/eng_class/software_and_infrastructure)
     - `b2007cel[06-21]V` for P3 machines [(link to the documentation)](https://sci.skoltech.ru/eng_class/software_and_infrastructure)

   - **Step 4:** Click "Connect" to initiate the connection.
   - **Step 5:** Enter your data as `<skoltech.login>@skoltech.ru` and password.

   ### On Linux:
   - **Step 1:** Install an RDP client, such as `Remmina`, using your package manager (e.g., `sudo apt install remmina`).
   - **Step 2:** Open the `Remmina` application.
   - **Step 3:** Click on "New Connection" or enter the hostname in the address bar:
     - `b2007cel[01-05]V` for P5 machines
     - `b2007cel[06-21]V` for P3 machines
   - **Step 4:** Configure the protocol as RDP and save the connection settings.
   - **Step 5:** Double-click on the saved connection to connect.
   - **Step 6:** Enter your data as `<skoltech.login>@skoltech.ru` and password.

   ### On macOS:
   - **Step 1:** Download and install "Microsoft Remote Desktop" from the App Store.
   - **Step 2:** Open the Microsoft Remote Desktop application.
   - **Step 3:** Click on "Add PC" to create a new connection.
   - **Step 4:** Enter the hostname in the "PC Name" field:
     - `b2007cel[01-05]V` for P5 machines
     - `b2007cel[06-21]V` for P3 machines
   - **Step 5:** Click "Add" to save the connection.
   - **Step 6:** Double-click the saved PC to initiate the connection.
   - **Step 7:** Enter your data as `<skoltech.login>@skoltech.ru` and password.


3. **Log in with Your Credentials**
   - Enter your Skoltech credentials in the format `<username>@skoltech.ru` and your Skoltech account password when prompted.

4. **Session Management**
   - Always **log out** after your session. Do not shut down the system.

   > [!IMPORTANT]
   > Properly logging out keeps the system ready for the next user and maintains system stability.

## Use of Shared Storage

> [!CAUTION]
> Local data on the machine will be deleted within 30 days. To save your data, transfer it to your folder on the shared storage system.

   Information regarding the location of the shared storage and access instructions will be provided.

## Continuing Processes in the Background

> [!IMPORTANT]
> You can continue running processes in the background and even connect remotely later to continue your work. However, only one user can interact with the screen at a time. If you encounter a message indicating someone has declined your request to take control of Windows, please wait until they finish their work.

Instructions on how to log off properly should be included.
