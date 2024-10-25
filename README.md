# ZeroTrace: Windows Uninstaller and Leftover Cleaner

**ZeroTrace** is a user-friendly Windows application designed for efficiently uninstalling programs and cleaning up leftover files. This tool helps users reclaim disk space and maintain system performance by ensuring that all remnants of uninstalled applications are thoroughly removed.

## Features

- **Program Uninstallation:** Easily select and uninstall installed applications from your system.
- **Leftover File Detection:** Automatically scans common directories for leftover files and folders related to uninstalled programs.
- **Cleanup Functionality:** Efficiently deletes leftover files and directories to free up disk space.
- **Admin Rights Request:** Automatically requests admin privileges when necessary, ensuring smooth execution of uninstallation tasks.
- **Error Reporting:** Comprehensive logging system that records application events and errors, providing insights into operations.
- **Discord Webhook Integration:** Sends error logs and crash reports to a specified Discord webhook, enabling real-time monitoring and support.

## Technologies Used

- Python
- Tkinter (for GUI)
- WinReg (to access Windows registry)
- Requests (for HTTP requests)

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/ZeroTrace.git
   cd ZeroTrace
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   python main.py
   ```

## Usage

- Launch the application.
- Select a program from the list of installed applications.
- Confirm uninstallation and choose whether to scan for leftover files.
- Follow the prompts to complete the cleanup process.

## Logging and Error Handling

All application logs are stored in the `Logs` directory. In the event of an error, relevant logs are sent to a designated Discord webhook for monitoring and troubleshooting.

## Contribution

Contributions are welcome! Feel free to submit issues or pull requests.

## Note

The files for the user interface (UI) will be uploaded soon.

## How to Upload Files

To upload files to your GitHub repository later, follow these steps:

1. **Navigate to your repository on GitHub.**
2. **Click on the "Add file" button.**
3. **Select "Upload files".**
4. **Drag and drop your files or choose them from your file explorer.**
5. **Add a commit message describing the changes.**
6. **Click the "Commit changes" button.**

Alternatively, you can use Git on your local machine:

1. **Make sure you are in your local repository directory.**
2. **Add the files you want to upload:**
   ```bash
   git add .
   ```
3. **Commit your changes:**
   ```bash
   git commit -m "Add initial files for ZeroTrace"
   ```
4. **Push to the remote repository:**
   ```bash
   git push origin main
   ```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
