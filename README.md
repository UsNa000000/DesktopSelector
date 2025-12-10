DesktopSelector: Your Seamless Multi-Desktop Manager
DesktopSelector is a powerful, lightweight utility for Windows that allows users to instantly swap between custom desktop environments. Perfect for professionals, developers, and students, the app ensures every project, client, or hobby has its own dedicated, clutter-free workspace, dramatically boosting organization and focus.

The application leverages native Windows Shell APIs to ensure reliable and fluid path switching, even when distributed as an MSIX package on the Microsoft Store.

**Key Features**
Instant Switching: Seamlessly switch between personalized desktop folders without the lag or visual disruption of manual explorer restarts.

Project Isolation: Assign specific local folders as unique desktops to isolate files, shortcuts, and working materials for different projects.

MSIX/Store Compatible: Built using the Desktop Bridge, ensuring robust, trusted system modifications while meeting strict Microsoft Store requirements.

Default Restore: Dedicated function to safely revert to the original Windows default desktop path.

Lightweight: Minimal memory usage and fast execution speed.

How to Use
Select a Folder: Click the "Add Desktop" button and choose any local folder (e.g., C:\Workspaces\Project_A).

Switch: Select the new workspace from the list and click "Apply." Your current desktop icons will be replaced instantly by the contents of the chosen folder.

Restore Default: Click "Restore Default Desktop" to instantly revert to the original Windows desktop path (%USERPROFILE%\Desktop). Note: This operation requires a temporary Explorer restart to ensure full system synchronization.

**Security & Permissions**
DesktopSwitcher is a local utility only.

The application does NOT require or use an internet connection.

No user data is collected, stored, or transmitted externally.

The application requires the runFullTrust restricted capability (for Store versions) to ensure it can modify the user's active desktop path, which is a required system operation.

**Installation**
Download the Installer

Go to the Releases page of this repository.

Download the file named FavoriteDesktopsSetup.exe.

2. Run the Installer

Double-click the downloaded .exe file.

Follow the installation steps.

A desktop shortcut will be created automatically (if selected during setup).

3. Launch the Application

Start Favorite Desktops from the desktop shortcut or from the Start Menu.

You can now create and switch between your custom desktop environments.


**Contribution**
Contributions are welcome! If you find a bug, have a feature request, or want to contribute code, please check our Contributing Guidelines (create this file later).

Fork the repository.

Create your feature branch (git checkout -b feature/AmazingFeature).

Commit your changes (git commit -m 'Add some AmazingFeature').

Push to the branch (git push origin feature/AmazingFeature).

Open a Pull Request.

**License**
Distributed under the MIT License. See LICENSE for more information. 
