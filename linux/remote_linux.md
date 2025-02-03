# Remote Access to Linux via SSH

## Accessing Linux Remotely Using SSH

> [!IMPORTANT]
> To access Linux remotely, ensure your device is connected to the Skoltech network.

1. **Ensure Network Access**
   - Confirm that your device is connected to the Skoltech network.

2. **Using SSH for Remote Access**

   To log in, use local account, NOT SKOLTECH data, for access for all the platforms. Choose your login from stud01 to stud30, for example, stud09. The password is the same for all accounts.

      ```
      login: stud[01-30]
      password: skolstud
      ```

   The hostname is given as
   b2007cel[01-05] for P5 machines [(link to the documentation)](https://sci.skoltech.ru/eng_class/software_and_infrastructure)
   b2007cel[06-21] for P3 machines [(link to the documentation)](https://sci.skoltech.ru/eng_class/software_and_infrastructure)

   ### On Windows:
   - **Step 1:** Download and install an SSH client like PuTTY from the official website.
   - **Step 2:** Open PuTTY and enter the hostname of the Linux machine in the "Host Name" field.
   - **Step 3:** Ensure the connection type is set to "SSH" and click "Open" to initiate the connection.

   ### On Linux:
   - **Step 1:** Open a terminal window.
   - **Step 2:** Use the SSH command to connect, e.g., `ssh stud[01-30]@b2007cel[01-21]`, replacing and `b2007cel[01-21]` with the machine address.

   ### On macOS:
   - **Step 1:** Open the Terminal application.
   - **Step 2:** Use the SSH command to connect, e.g., `ssh stud[01-30]@b2007cel[01-21]`.

   > ![Screenshot Required](#) - **Insert a screenshot of the SSH setup or terminal command here for each operating system.**

3. **Log in with Your Credentials**
   - Enter your Skoltech account username and password when prompted.


## Use of Shared Storage

> [!CAUTION]
> Local data on the machine will be deleted within 30 days. To save your data, transfer it to your folder on the shared storage system.

   Information regarding the location of the shared storage and access instructions should be provided.

## Continuing Processes in the Background

> [!IMPORTANT]
> You can continue running processes in the background and resume them later by reconnecting via SSH. However, ensure no critical processes are left unattended.


## Accessing Linux Remotely Using RDP (Graphical interface)

> [!IMPORTANT]
> To access Linux remotely, ensure your device is connected to the Skoltech network or use the Skoltech VPN.

1. **Ensure Network Access**
   - Confirm that your device is connected to the Skoltech network or use a VPN if you're off-campus.

2. **Using RDP for Remote Access**

To log in, use a local account, NOT SKOLTECH data, for access across all platforms. Choose your login from stud01 to stud30, for example, stud09. The password is the same for all accounts.

   ```
   login: stud[01-30]
   password: skolstud
   ```

The hostname is given as:
   b2007cel[01-05] for P5 machines [(link to the documentation)](https://sci.skoltech.ru/eng_class/software_and_infrastructure)
   b2007cel[06-21] for P3 machines [(link to the documentation)](https://sci.skoltech.ru/eng_class/software_and_infrastructure)

   ### On Windows:
   - **Step 1:** Open the Start menu and search for "Remote Desktop Connection."
   - **Step 2:** Click on "Remote Desktop Connection" to open the application.
   - **Step 3:** In the "Computer" field, enter the hostname provided:
     - `b2007cel[01-05]` for P5 machines
     - `b2007cel[06-21]` for P3 machines
   - **Step 4:** Click "Connect" to initiate the connection.
   - **Step 5:** Enter your data as `stud[01-30]` and password `skolstud`.

   ### On Linux:
   - **Step 1:** Install an RDP client, such as `Remmina`, using your package manager (e.g., `sudo apt install remmina`).
   - **Step 2:** Open the `Remmina` application.
   - **Step 3:** Click on "New Connection" or enter the hostname in the address bar:
     - `b2007cel[01-05]` for P5 machines
     - `b2007cel[06-21]` for P3 machines
   - **Step 4:** Configure the protocol as RDP and save the connection settings.
   - **Step 5:** Double-click on the saved connection to connect.
   - **Step 6:** Enter your data as `stud[01-30]` and password `skolstud`.

   ### On macOS:
   - **Step 1:** Download and install "Microsoft Remote Desktop" from the App Store.
   - **Step 2:** Open the Microsoft Remote Desktop application.
   - **Step 3:** Click on "Add PC" to create a new connection.
   - **Step 4:** Enter the hostname in the "PC Name" field:
     - `b2007cel[01-05]` for P5 machines
     - `b2007cel[06-21]` for P3 machines
   - **Step 5:** Click "Add" to save the connection.
   - **Step 6:** Double-click the saved PC to initiate the connection.
   - **Step 7:** Enter your data as `stud[01-30]` and password `skolstud`.


4. **Log in with Your Credentials**
   - Always **Log out** after your session.

   > [!WARNING]
   > Do not shut down the system!

   ![Log out Linux](https://github.com/STAER-HPC/computational_class_docs/blob/main/img/linux/log-out.png?raw=true)

## Use of Shared Storage

> [!CAUTION]
> Local data on the machine will be deleted within 30 days. To save your data, transfer it to your folder on the shared storage system.

   Information regarding the location of the shared storage and access instructions will be provided.

## Continuing Processes in the Background

> [!IMPORTANT]
> You can continue running processes in the background and resume them later by reconnecting via RDP. However, ensure no critical processes are left unattended.
