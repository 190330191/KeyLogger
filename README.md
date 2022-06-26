# A simple keylogger for Windows.

Welcome to the simple keylogger repo! A keylogger is a program that records your keystrokes, and this program saves them in a log file on your local computer.

Check out below to learn how to install them. These keyloggers are simple and bare bones, however they work great! Feel free to fork and improve it if you want.

Currently, there are three keylogger programs for the major operating systems; Windows, Mac and Linux.

## Contents
- [Windows installation guide](https://github.com/190330191/KeyLogger/blob/main/README.md)

Or, view the `README.md` file in each programs folder for more up to date information.

## Windows
To change visibility of the window set the `#define` in line 9 to `visible` or `invisible`.

Simply compile into an .exe, and then run. Visual Studio is good for this.

- `invisible` makes the window of the logger disappear, and it also starts up hidden from view. Note that it is still visible in the task manager.
- `visible` is visible, and the window does not close when typing. Great for testing it out.

Both of these save the keystrokes to a .txt file when closed.

> Note that sometimes your compiler may through up errors. If it does, keep compiling - the program still works. As always, please create an issue if you have a problem.

---
#### Uses

Some uses of a keylogger are:

- Business Administration: Monitor what employees are doing.
- School/Institutions: Track keystrokes and log banned words in a file.
- Personal Control and File Backup: Make sure no one is using your computer when you are away.
- Parental Control: Track what your children are doing.
- Self analysis

---
