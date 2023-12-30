# 🚀 Setting Up Visual Studio Code for C++ Development on Windows

Welcome to the guide that will help you set up Visual Studio Code for C & C++ development on Windows. Let's make coding a delightful experience!

![](https://github.com/Monika3002/Monika3002/blob/main/192114009-0830321a-d227-4a4d-8411-6c03b54d7ce6.png](https://github.com/Monika3002/VScode-C-cpp-guide/blob/main/Reference%20Images/code-runner.jpeg)



## Step 1: Install Visual Studio Code

1. **Download VSCode:** Visit the [official Visual Studio Code website](https://code.visualstudio.com/) and grab the installer for Windows.
2. **Run Installer:** Execute the downloaded installer and follow the on-screen instructions to complete the installation.

## Step 2: Install Mingw-w64

1. **Download Mingw-w64 Installer:** Visit the [Mingw-w64 download page](https://sourceforge.net/projects/mingw/) and get "mingw-w64-install.exe."
2. **Run the Installer:** Run the installer, customize your preferences, and set the installation directory (e.g., `C:\mingw-w64`).
3. **Add to System Path:** During installation, ensure that you select the option to add Mingw-w64 to the system PATH.

## Step 3: Update System Path Variable

1. **Find System Properties:** Right-click on "This PC" or "Computer" and select "Properties."
2. **Open Advanced System Settings:** Click on "Advanced system settings."
3. **Open Environment Variables:** Click on the "Environment Variables" button.
4. **Edit Path Variable:** In the "System variables" section, select the "Path" variable, then click "Edit."
5. **Add Mingw-w64 to Path:** Click "New" and add the path to the `bin` directory of Mingw-w64 (e.g., `C:\mingw-w64\mingw64\bin`).
6. **Save Changes:** Click "OK" to close each of the dialog boxes.

## Step 4: Install C/C++ Extension in Visual Studio Code

1. Open VSCode.
2. **Open Extensions View:** Click on the Extensions icon or use `Ctrl+Shift+X`.
3. **Search for C/C++ Extension:** Type "C/C++" in the search bar and install the one provided by Microsoft.

## Step 5: Create a C++ File and Install Code Runner Extension

1. **Open a Folder:** Open a folder where you want to save your C++ files.
2. **Create a New File:** Right-click and choose "New File." Name it with a `.cpp` extension, e.g., `main.cpp`.
3. **Write Some Code:** Open `main.cpp` and write a simple C++ program.
4. **Install Code Runner:** Search for "Code Runner" in Extensions View and install the one provided by Jun Han.

## Step 6: Run Your C++ Code

1. Open your `main.cpp` file.
2. Right-click anywhere in the editor.
3. Select "Run Code" to execute your C++ program.

Now, you have Visual Studio Code set up for C++ development on Windows! Happy Coding! 🎉
