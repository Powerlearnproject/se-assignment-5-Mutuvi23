[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15287467&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

 Select Your Operating System (OS)
Download and Install Windows 11
Go to the Windows 11 download page
Instructions to Download and Install Windows 11

Step 1: Check System Requirements,
Before you start, ensure your PC meets the minimum system requirements for Windows 11:

Processor: 1 GHz or faster with at least 2 cores on a compatible 64-bit processor.
RAM: 4 GB or more.
Storage: 64 GB or larger storage device.
System firmware: UEFI, Secure Boot capable.
TPM: Trusted Platform Module (TPM) version 2.0.
Graphics card: DirectX 12 compatible graphics / WDDM 2.x.
Display: >9” with HD Resolution (720p).
Internet connection: Internet connectivity is necessary to perform updates and to download and take advantage of some features.

Step 2: Backup Your Data
Before making any changes to your operating system, back up your important files to an external hard drive or cloud storage service.

Step 3: Download Windows 11 Installation Media
Go to the Windows 11 download page.
Under "Create Windows 11 Installation Media," click Download now.

Step 4: Create Installation Media
Run the downloaded Media Creation Tool.
Accept the license terms.
Choose "Create installation media (USB flash drive, DVD, or ISO file) for another PC" and click Next.
Select the language, edition, and architecture (64-bit) for Windows 11.
Choose the media type:
USB flash drive: Plug in a USB drive with at least 8 GB of space.
ISO file: Save an ISO file to burn to a DVD later.

Step 5: Install Windows 11
Using USB Flash Drive:
Insert the USB flash drive into the PC where you want to install Windows 11.
Restart your PC and boot from the USB drive. (You may need to change the boot order in the BIOS/UEFI settings.)
Follow the on-screen instructions to install Windows 11.

Using ISO File:
Burn the ISO file to a DVD.
Insert the DVD into the PC where you want to install Windows 11.
Restart your PC and boot from the DVD. (You may need to change the boot order in the BIOS/UEFI settings.)
Follow the on-screen instructions to install Windows 11.

Step 6: Set Up Windows 11
After installation, follow the on-screen instructions to set up your preferences, including region, language, and keyboard layout.
Connect to a Wi-Fi network and sign in with your Microsoft account.
Customize settings, such as privacy settings and preferences.

Step 7: Install Updates and Drivers
Once Windows 11 is installed, go to Settings > Update & Security > Windows Update and check for updates.
Install all available updates, including drivers for your hardware components.

Step 8: Reinstall Applications and Restore Data
Reinstall your applications and restore your backed-up data to the new Windows 11 installation


2. Install a Text Editor or Integrated Development Environment (IDE)
Download and Install Visual Studio Code
Go to the Visual Studio Code download page.
Download the installer for your operating system.
Run the installer and follow the prompts to install Visual Studio Code.


2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

1. Basic Configuration
Open VS Code: Launch Visual Studio Code.
Theme: Choose a color theme.
Go to File > Preferences > Color Theme (or Ctrl+K Ctrl+T).
Select a theme that you find comfortable for coding. Popular choices are Dark+ (default dark) or Light+ (default light).
2. Key Settings
Auto Save:

Go to File > Preferences > Settings (or press Ctrl+,).
Search for Auto Save and set it to afterDelay or onWindowChange based on your preference.
Font Size:

Search for Font Size and adjust it to a comfortable size (e.g., 14).
Tab Size:

Search for Tab Size and set it to 4 or your preferred number of spaces per tab.
Word Wrap:

Search for Word Wrap and enable it by setting it to on.
3. Essential Extensions
Python:

Go to the Extensions view by clicking the Extensions icon in the Sidebar or pressing Ctrl+Shift+X.
Search for Python by Microsoft and install it. This extension provides rich support for the Python language, including IntelliSense (Pylance), linting, debugging, and more.
Prettier - Code formatter:

Search for Prettier - Code formatter and install it. This extension helps in formatting code consistently.
GitLens:

Search for GitLens and install it. This extension provides Git superpowers inside VS Code, such as inline blame, history, and more.
Live Server:

Search for Live Server and install it. This extension launches a local development server with a live reload feature for static and dynamic pages.
Bracket Pair Colorizer:

Search for Bracket Pair Colorizer and install it. This extension allows matching brackets to be identified with colors.
4. Configure Python Environment
Set Python Interpreter:
Press Ctrl+Shift+P to open the Command Palette.
Type Python: Select Interpreter and select the appropriate Python interpreter from the list.
5. Configure Prettier
Set Prettier as Default Formatter:
Go to File > Preferences > Settings (or press Ctrl+,).
Search for Default Formatter and set it to Prettier - Code formatter.
Search for Format On Save and enable it to automatically format your code when you save a file.
6. Configure GitLens
Basic Setup:
After installing GitLens, you can configure it by going to File > Preferences > Settings and searching for GitLens.
Adjust settings like GitLens: Current Line to display blame information inline.
7. Configure Live Server
Auto Save Configuration:
If using Live Server, it’s often useful to enable Auto Save. Go to File > Preferences > Settings and search for Auto Save.
8. Optional Extensions
ESLint (for JavaScript/TypeScript):
Search for ESLint and install it. This extension integrates ESLint into VS Code to find and fix problems in your JavaScript/TypeScript code.
Docker:
Search for Docker and install it if you are using Docker. This extension makes it easy to create, manage, and debug containerized applications.
9. Customize Workspace Settings
Project-specific Settings:
You can create a .vscode folder in your project directory and add settings.json for project-specific settings.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

   1. Activity Bar
The Activity Bar is located on the far left side of the VS Code window. It provides quick access to different views and features of the editor. The icons on the Activity Bar represent different activities and can be customized or extended with additional extensions. The default icons include:
Explorer: Displays the file and folder structure of your workspace.
Search: Allows you to search for files, text, or symbols within your project.
Source Control: Integrates version control systems like Git, showing changes, commits, and branches.
Run and Debug: Provides access to debugging configurations and tools.
Extensions: Lets you search for, install, and manage extensions to enhance VS Code functionality.

2. Side Bar
The Side Bar is adjacent to the Activity Bar and changes its content based on the selected activity. Its purpose is to provide more detailed views and functionality for the selected activity. For example:
Explorer View: Displays a tree view of your project's files and folders, allowing you to open, create, delete, and manage them.
Search View: Shows search results and allows you to refine your searches and replace text across files.
Source Control View: Displays the status of your source control, including staged and unstaged changes, commit history, and more.
Run and Debug View: Provides controls and settings for running and debugging your code.
Extensions View: Lists installed extensions and recommendations, and allows you to manage them.

3. Editor Group
The Editor Group is the central area of VS Code where you edit your code. You can open multiple files simultaneously, and they will be displayed in tabs within the Editor Group. Key features of the Editor Group include:
Tabs: Represent open files or documents. You can switch between them, reorder them, or close them.
Split Editors: Allows you to split the editor into multiple columns or rows to view and edit multiple files side by side.
Breadcrumbs: Located at the top of the Editor Group, they help you navigate through your code structure, such as symbols, functions, and files.
Minimap: A high-level overview of your code, displayed on the right side of the editor, allowing you to quickly navigate large files.

4. Status Bar
The Status Bar is located at the bottom of the VS Code window and provides information about the current state of your workspace and editor. Key elements of the Status Bar include:
Current Line and Column: Displays the cursor's current line and column position in the active file.
Language Mode: Shows the programming language of the currently active file. Clicking on it allows you to change the language mode.
Encoding: Displays the character encoding of the active file.
EOL (End of Line): Shows the line-ending format (e.g., LF, CRLF) of the active file.
Indentation: Displays the indentation size and type (e.g., spaces, tabs) for the active file.
Git Branch and Status: If you have a Git repository open, it shows the current branch and the status of your working directory.
Notifications and Warnings: Displays icons and messages for errors, warnings, and notification

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

The Command Palette in Visual Studio Code (VS Code) is a powerful tool that provides quick access to various commands, settings, and features within the editor. It allows you to execute commands and perform tasks without navigating through menus or using keyboard shortcuts.

Accessing the Command Palette
Keyboard Shortcut: Press Ctrl+Shift+P (Windows/Linux) or Cmd+Shift+P (Mac).
Menu Access: You can also access the Command Palette by clicking on View in the top menu and selecting Command Palette.


Common Tasks Using the Command Palette
Here are some examples of common tasks that can be performed using the Command Palette:

Opening Settings

Command: Preferences: Open Settings (UI)
Description: Opens the settings user interface where you can adjust various settings and preferences.
Changing the Color Theme

Command: Preferences: Color Theme
Description: Opens a list of available color themes, allowing you to select and apply a new theme.
Running a Build Task

Command: Tasks: Run Build Task
Description: Executes a predefined build task for your project, such as compiling code.
Git Commands

Command: Git: Clone
Description: Clones a Git repository from a remote source to your local machine.
Command: Git: Commit
Description: Commits staged changes with a commit message.
Opening Files

Command: File: Open File
Description: Opens a file from your filesystem.
Command: File: Open Recent
Description: Opens a list of recently opened files and folders.
Terminal Commands

Command: Terminal: Create New Integrated Terminal
Description: Opens a new integrated terminal within VS Code.
Extensions

Command: Extensions: Install Extensions
Description: Opens the Extensions view where you can search for and install new extensions.
Running and Debugging

Command: Debug: Start Debugging
Description: Starts a debugging session based on the currently active debug configuration.
Command: Debug: Add Configuration
Description: Adds a new debug configuration to your project.
Snippets

Command: Insert Snippet
Description: Allows you to insert predefined code snippets into your code.
View and Toggle Features

Command: View: Toggle Sidebar Visibility
Description: Shows or hides the sidebar.
Command: View: Toggle Full Screen
Description: Toggles full-screen mode for the VS Code window.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

   
   Role of Extensions in VS Code
Extensions in Visual Studio Code (VS Code) play a crucial role in enhancing the functionality and usability of the editor. They allow users to customize their development environment, add new features, and improve productivity by supporting a wide range of programming languages, frameworks, tools, and workflows.

Finding, Installing, and Managing Extensions
Finding Extensions:

Extensions View: Click on the Extensions icon in the Activity Bar on the side of the window or press Ctrl+Shift+X (Windows/Linux) or Cmd+Shift+X (Mac) to open the Extensions view.
Marketplace: You can also visit the Visual Studio Code Marketplace to browse and search for extensions online.
Installing Extensions:

Search for Extensions: In the Extensions view, use the search bar to find extensions by name, category, or keywords.
Install Extension: Click on the Install button next to the extension you want to install. The installation process will begin, and the extension will be added to your VS Code.
Managing Extensions:

Enable/Disable Extensions: Right-click on an extension in the Extensions view and select Enable or Disable. Disabling an extension will turn off its functionality without uninstalling it.
Update Extensions: When updates are available, an update button will appear next to the extension. Click on Update to get the latest version.
Uninstall Extensions: Right-click on an extension and select Uninstall to remove it from VS Code.
Extension Settings: Many extensions have configurable settings. Click on the gear icon next to an extension and select Extension Settings to customize its behavior.

Essential Extensions for Web Development
Here are some essential extensions for web development in VS Code:

Prettier - Code formatter
Description: Prettier is an opinionated code formatter that supports many languages. It enforces a consistent style by parsing your code and re-printing it with its own rules.
Usage: Automatically format your code on save to maintain a consistent code style.
Installation: Search for Prettier - Code formatter and install it.

ESLint
Description: ESLint is a linting tool for JavaScript and TypeScript that identifies and reports on patterns in the code, helping to maintain quality and consistency.
Usage: Integrates ESLint into VS Code to find and fix problems in your JavaScript/TypeScript code.
Installation: Search for ESLint and install it.

Live Server
Description: Live Server launches a local development server with a live reload feature for static and dynamic pages.
Usage: Automatically refreshes your browser when you save changes to your HTML, CSS, or JavaScript files.
Installation: Search for Live Server and install it.

HTML CSS Support
Description: Provides CSS support for HTML documents.
Usage: Adds IntelliSense for CSS class names in HTML files.
Installation: Search for HTML CSS Support and install it.

JavaScript (ES6) code snippets
Description: Provides a collection of JavaScript (ES6) code snippets.
Usage: Quickly insert commonly used JavaScript snippets into your code.
Installation: Search for JavaScript (ES6) code snippets and install it.

Debugger for Chrome
Description: Debug your JavaScript code in the Google Chrome browser, or any other target that supports the Chrome Debugger protocol.
Usage: Set breakpoints, step through your code, and inspect variables directly in VS Code.
Installation: Search for Debugger for Chrome and install it.

Path Intellisense
Description: Provides path completion for import statements and file paths in your project.
Usage: Auto-completes file paths as you type, saving time and reducing errors.
Installation: Search for Path Intellisense and install it.

IntelliSense for CSS class names in HTML
Description: Provides IntelliSense for CSS class names in HTML.
Usage: Auto-completes CSS class names based on the project's CSS files.
Installation: Search for IntelliSense for CSS class names in HTML and install it.

Bracket Pair Colorizer
Description: This extension allows matching brackets to be identified with colors.
Usage: Helps to easily identify matching brackets, improving code readability.
Installation: Search for Bracket Pair Colorizer and install it.

Auto Rename Tag
Description: Automatically rename paired HTML/XML tags.
Usage: Automatically updates the closing tag when you change the opening tag, reducing the chance of mismatched tags.
Installation: Search for Auto Rename Tag and install it.



6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

Opening and Using the Integrated Terminal in VS Code
Opening the Integrated Terminal

Using the Menu Bar:
Navigate to the top menu and click on Terminal.
Select New Terminal from the dropdown menu.

Using Keyboard Shortcuts:
Windows/Linux: Press Ctrl + (backtick) or Ctrl + Shift + (backtick)`.
Mac: Press Cmd + (backtick) or Cmd + Shift + (backtick)`.

Using the Command Palette:
Press Ctrl + Shift + P (Windows/Linux) or Cmd + Shift + P (Mac) to open the Command Palette.
Type Terminal: Create New Integrated Terminal and select the command from the list.
Using the Integrated Terminal

Basic Commands:
You can run any terminal command in the integrated terminal just as you would in an external terminal. For example, ls (or dir on Windows) to list directory contents, cd to change directories, npm install to install Node.js packages, etc.

Managing Multiple Terminals:
New Terminal: Click the + icon in the terminal panel to open a new terminal instance.
Switching Terminals: Click on the dropdown menu on the right of the terminal panel to switch between multiple open terminals.
Split Terminal: Click the split terminal icon to open another terminal in the same panel, allowing side-by-side terminals.

Terminal Settings:
You can customize the integrated terminal settings by navigating to File > Preferences > Settings and searching for terminal. Here, you can change the default shell, font size, and other terminal preferences.

Running Tasks:
You can run predefined tasks directly from the terminal. For example, build scripts, test scripts, etc., configured in tasks.json can be executed using the terminal.
Advantages of Using the Integrated Terminal

Context Awareness:
The integrated terminal opens in the context of the current workspace. This means it automatically starts in the root directory of your project, reducing the need to navigate to the project directory manually.

Convenience:
Having the terminal integrated into VS Code eliminates the need to switch between separate applications. This can streamline your workflow and save time, as you can run terminal commands without leaving the editor.

Synchronization:
The integrated terminal and the editor are synchronized. For example, when you run build or compile commands, any resulting errors or warnings can be clicked directly within the terminal to navigate to the corresponding line in the code.

Customization:
The integrated terminal can be customized to match your development needs. You can change the shell (e.g., bash, zsh, PowerShell), adjust the appearance, and set up tasks and commands to run automatically.

Split View:
The ability to split the terminal into multiple panes allows you to run and monitor several commands simultaneously without cluttering your screen with multiple terminal windows.

Environment Management:
Integrated terminals can inherit the environment variables from your VS Code workspace settings, ensuring consistency across your development tools and scripts.

Extensions Integration:
Some VS Code extensions provide additional functionality that integrates directly with the terminal. For example, the GitLens extension adds Git blame and other features directly into the terminal output.

Ease of Use:
Opening and managing terminals in VS Code is simple and intuitive, often requiring just a single click or keypress. This ease of use can make you more productive, especially during complex development tasks that require frequent terminal use.

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

   Creating, Opening, and Managing Files and Folders in VS Code
Creating Files and Folders
Using the Explorer View:

Create a New File:

Click on the Explorer icon in the Activity Bar to open the Explorer view.
Right-click on the folder where you want to create the new file.
Select New File from the context menu.
Enter the name of the file and press Enter.

Create a New Folder:
In the Explorer view, right-click on the parent folder.
Select New Folder from the context menu.
Enter the name of the folder and press Enter.

Using Keyboard Shortcuts:
Create a New File:
Press Ctrl + N (Windows/Linux) or Cmd + N (Mac) to create a new untitled file.
Save the file by pressing Ctrl + S (Windows/Linux) or Cmd + S (Mac) and specify the file name and location.

Using the Command Palette:
Press Ctrl + Shift + P (Windows/Linux) or Cmd + Shift + P (Mac) to open the Command Palette.

Type File: New File or File: New Folder and select the command.

Opening Files and Folders

Using the Explorer View:
Click on the Explorer icon in the Activity Bar.
Navigate to the file or folder you want to open and click on it.

Using Keyboard Shortcuts:
Open File: Press Ctrl + O (Windows/Linux) or Cmd + O (Mac) and select the file from the dialog.
Open Folder: Press Ctrl + K, Ctrl + O (Windows/Linux) or Cmd + K, Cmd + O (Mac) and select the folder from the dialog.

Drag and Drop:
Drag a file or folder from your file explorer (e.g., Windows Explorer, Finder) and drop it into the VS Code window.

Managing Files and Folders

Renaming Files and Folders:
In the Explorer view, right-click on the file or folder you want to rename.
Select Rename from the context menu.
Enter the new name and press Enter.

Deleting Files and Folders:
In the Explorer view, right-click on the file or folder you want to delete.
Select Delete from the context menu.
Confirm the deletion if prompted.

Moving Files and Folders:
In the Explorer view, drag the file or folder to the desired location.
Navigating Between Files and Directories Efficiently

Quick Open:
Press Ctrl + P (Windows/Linux) or Cmd + P (Mac) to open the Quick Open feature.
Type the name of the file you want to open and select it from the list.

File Tabs:
Open files are displayed in tabs at the top of the Editor Group.
Click on a tab to switch to that file.

Breadcrumbs:
Breadcrumbs show the file path and symbols in the active file.
Enable Breadcrumbs by clicking on the View menu and selecting Show Breadcrumbs or by clicking the breadcrumbs icon in the Editor Group.
Click on a breadcrumb to navigate to a different part of your project.
Go to Definition:

Right-click on a symbol (e.g., function, variable) and select Go to Definition or press F12.
This navigates to the definition of the symbol in your project.
Go to File/Go to Symbol:

Press Ctrl + T (Windows/Linux) or Cmd + T (Mac) to open the Go to File/Symbol feature.
Type the name of the file or symbol and select it from the list.
Explorer View:

Use the file and folder tree in the Explorer view to navigate your project structure.
Click on folders to expand or collapse them.
Keyboard Shortcuts:

Switch Editor Group: Ctrl + 1, Ctrl + 2, etc., to switch between multiple editor groups.
Navigate Back/Forward: Ctrl + - (back) and Ctrl + Shift + - (forward) on Windows/Linux, or Cmd + - and Cmd + Shift + - on Mac, to navigate between recently opened files.

Integrated Terminal:
Use the integrated terminal to navigate the file system and open files directly from the command line.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

   Finding and Customizing Settings in VS Code
Accessing Settings
Settings via the Menu Bar:

Click on File (or Code on Mac) in the top menu.
Select Preferences and then Settings.
Settings via Command Palette:

Press Ctrl + Shift + P (Windows/Linux) or Cmd + Shift + P (Mac) to open the Command Palette.
Type Preferences: Open Settings and select it.
Settings Icon:

Click on the gear icon in the bottom left corner of the VS Code window.
Select Settings.
Customizing Settings
Settings View:

The Settings UI will open, displaying a user-friendly interface for managing settings.
You can switch between the user settings (global across all workspaces) and workspace settings (specific to a particular project).
Settings JSON:

If you prefer to edit the settings as JSON, click on the {} icon in the top right corner of the Settings view.
This will open the settings.json file, where you can manually add or modify settings.
Examples of Common Customizations
Changing the Theme:

Via Settings UI:
Open the Settings UI.
In the search bar, type Color Theme.
Click on Color Theme under Appearance.
Select your desired theme from the list.
Via Command Palette:
Press Ctrl + Shift + P (Windows/Linux) or Cmd + Shift + P (Mac).
Type Preferences: Color Theme and select it.
Choose your desired theme from the list.
Changing the Font Size:

Via Settings UI:
Open the Settings UI.
In the search bar, type Font Size.
Under Editor: Font Size, enter your desired font size.
Via Settings JSON:
Open settings.json.
Add or modify the following line:
json
Copy code
"editor.fontSize": 16
Replace 16 with your desired font size.
Changing Keybindings:

Via Keybindings UI:
Click on the gear icon in the bottom left corner and select Keyboard Shortcuts.
Alternatively, press Ctrl + K, Ctrl + S (Windows/Linux) or Cmd + K, Cmd + S (Mac).
The Keybindings UI will open, showing all available keybindings.
To change a keybinding, find the command you want to modify, click on the pencil icon next to it, and press the new key combination.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?


Let's consider a simple Python program as an example:

Install Necessary Extensions:

Install the Python extension for VS Code if it's not already installed.
Click on the Extensions icon in the Activity Bar, search for "Python", and install the extension by Microsoft.
Create a New Python File:

Open VS Code and create a new file (Ctrl + N or Cmd + N).
Save the file with a .py extension, for example, app.py.
Write a Simple Python Program:

#python

def greet(name):
    return f"Hello, {name}!"

if __name__ == "__main__":
    name = input("Enter your name: ")
    print(greet(name))

Open the Debug Panel:
Click on the Debug icon in the Activity Bar to open the Debug view.
Click on the gear icon or select "create a launch.json file" to configure the debugger.
Configure the Debugger:

When prompted to select a debug configuration, choose "Python File".
A launch.json file will be created in a .vscode folder in your workspace. It should contain a configuration similar to this:

#json
{
    "version": "0.2.0",
    "configurations": [
        {
            "name": "Python: Current File",
            "type": "python",
            "request": "launch",
            "program": "${file}",
            "console": "integratedTerminal"
        }
    ]
}

Set Breakpoints:
Click on the left margin next to the line numbers in your code to set breakpoints. A red dot will appear, indicating a breakpoint.
Start Debugging:

Click the green play button in the Debug panel or press F5 to start debugging.
The program will run and stop at the first breakpoint you set.
Key Debugging Features in VS Code
Breakpoints:

Set Breakpoints: Click on the left margin next to the line number.
Conditional Breakpoints: Right-click on a breakpoint and select "Edit Breakpoint" to add conditions.
Logpoints: Right-click on a line and select "Add Logpoint" to log messages without stopping execution.
Watch Variables:

In the Debug view, under the "WATCH" section, you can add expressions or variables to monitor their values as you step through the code.
Call Stack:

The "CALL STACK" section shows the call stack of your program, allowing you to see the sequence of function calls that led to the current point of execution.
Variable Inspection:

Hover over variables in the editor during a debug session to see their current values.
The "VARIABLES" section in the Debug view shows local, global, and environment variables.

Step Controls: 
Continue (F5): Continue execution until the next breakpoint.
Step Over (F10): Execute the next line of code, but don't step into functions.
Step Into (F11): Step into functions to see their execution.
Step Out (Shift + F11): Step out of the current function and return to the caller.
Debug Console:

The Debug Console allows you to evaluate expressions and execute commands in the context of the debug session. You can access it from the bottom panel.
Inline Values:

Display variable values inline with the code during debugging sessions for quick reference.
Conditional Breakpoints and Hit Counts:

Add conditions to breakpoints to pause execution only when certain conditions are met.
Set hit counts to break only after a breakpoint has been hit a specified number of times


10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
Install Git: If Git is not already installed on your system, download and install it from the Git website.

Set Up GitHub Account: If you don't have a GitHub account, create one at GitHub.

Initializing a Repository
Open a Folder in VS Code:

Open VS Code and click on File > Open Folder....
Select the folder where you want to initialize the Git repository and click Open.
Initialize Git Repository:

Press Ctrl + Shift + P (Windows/Linux) or Cmd + Shift + P (Mac) to open the Command Palette.
Type Git: Initialize Repository and select the option.
Select the folder you opened in VS Code to initialize the repository.
Making Commits
Stage Changes:

Open the file you want to commit.
Click on the + icon next to the file name in the Source Control view (Ctrl + Shift + G) to stage the changes.
Commit Changes:

Click on the checkmark icon in the Source Control view to open the commit message input box.
Enter a commit message describing your changes and press Ctrl + Enter to commit.
View and Manage Commits:

Click on the clock icon in the Source Control view to view the commit history.
Right-click on a commit to view details, revert changes, or create a new branch from that commit.
Pushing Changes to GitHub
Add Remote Repository:

In the Terminal (Ctrl + ), type git remote add origin <repository_url>` to add your GitHub repository as the remote origin.
Replace <repository_url> with the URL of your GitHub repository.
Push Changes:

In the Terminal, type git push -u origin master to push your changes to the remote repository.
You may be prompted to log in to your GitHub account if you haven't already.
View Changes on GitHub:

Visit your GitHub repository in a web browser to view the changes you've pushed.




 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

