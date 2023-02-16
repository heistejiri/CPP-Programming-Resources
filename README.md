# CPP-Programming-Resources

## 📌 Tech Stack

[![CPP](https://img.shields.io/badge/cpp%20-%23E34F26.svg?&style=for-the-badge&logo=cpp&logoColor=white)](https://github.com/heistejiri)&nbsp;


<br>

### Tools Used :

#### Text Editor :
  * Visual Studio Code
  * Java 
  * SQLite database ( SQLiteOpenHelper )
#### Frontend :
  * XML



### Install Visual Studio Code :
1. Install the C/C++ extension for VS Code. You can install the C/C++ 
extension by searching for 'c++' in the Extensions view (Ctrl+Shift+X).

2. C/C++ extension

3. Get the latest version of Mingw-w64 via MSYS2, which provides up-to-date native builds of GCC, Mingw-w64, and other helpful C++ tools and libraries. You can download the latest installer from the MSYS2 page or use this link to the installer.

4. Follow the Installation instructions on the MSYS2 website to install Mingw-w64. Take care to run each required Start menu and pacman command.

5. Install the Mingw-w64 toolchain (pacman -S --needed base-devel mingw-w64-x86_64-toolchain). Run the pacman command in a MSYS2 terminal. Accept the default to install all the members in the toolchain group.

6. Add the path to your Mingw-w64 bin folder to the Windows PATH environment variable by using the following steps:

7. In the Windows search bar, type 'settings' to open your Windows Settings.

- Search for Edit environment variables for your account.
- Choose the Path variable in your User variables and then select Edit.
- Select New and add the Mingw-w64 destination folder path to the system path. The exact path depends on which version of Mingw-w64 you have installed and where you installed it. If you used the settings above to install Mingw-w64, then add this to the path: C:\msys64\mingw64\bin.
- Select OK to save the updated PATH. You will need to reopen any console windows for the new PATH location to be available.

### Check your MinGW installation
To check that your Mingw-w64 tools are correctly installed and available, open a new Command Prompt and type:

gcc --version
g++ --version
gdb --version

If you don't see the expected output or g++ or gdb is not a recognized command, make sure your PATH entry matches the Mingw-w64 binary location where the compilers are located. If the compilers do not exist at that PATH entry, make sure you followed the instructions on the MSYS2 website to install Mingw-w64.
If gcc has the correct output but not gdb, then you need to install the packages you are missing from the Mingw-w64 toolset.
Missing the mingw-w64-gdb package is one cause of the "The value of miDebuggerPath is invalid." message upon attempted compilation if your PATH is correct

## 📬 Connect With Me

- **LinkedIn** - [OgheneTejiri Agoro](https://www.linkedin.com/in/heistejiri/)
- **Twitter** - [@Heistejiri](https://www.twitter.com/heistejiri)

## 📌 Acknowledgments

- Icons Used For Tech Stack Section - [https://img.shields.io](https://img.shields.io)
- This ReadMe File Inspired From - [Jigar Sable](https://github.com/jigar-sable)
