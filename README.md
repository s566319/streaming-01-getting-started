# streaming-01-getting-started

## Student: Inga Miller
## Class: 44-671 Streaming Dat

## Prerequisites

You should have these downloaded and installed on your machine:

1. Python 3.10 or higher
1. VS Code
1. VS Code Extension: Python
1. Git (configured with user.name and user.email - the same email you use for GitHub)

## Open Project Folder in VS Code

In VS Code, open just your project repository folder, e.g. Documents/streaming-01-getting-started.

## Verify Installations / Update Default Python

In VS Code, open a terminal window (View / Terminal) and verify your software is installed and configured.

- If Mac/Linux, the default terminal should work.
- If Windows, be sure you're using a PowerShell terminal (rather than cmd).

```shell
git --version
git config Inga Miller
git config s566319@nwmissouri.edu
python --version
python -m pip install --upgrade pip wheel
```
## Execute Utility Script (Diagnostics)

With your repo folder open in VS Code:

1. Click util_about.py.
1. If VS Code prompts, install the recommended Python extension.
1. Check the Python Interpreter: On the bottom-left status bar, you might see a version of Python indicated (e.g., Python 3.12.x).
1. If not, click on the bottom status bar where it should show the Python version or might say "Select Python Interpreter".
1. From the dropdown, choose your default Python version.

Use the terminal and the python command to execute the Python script. 

1. Use your VS Code terminal window from above or open a new terminal window (View / Terminal) in VS Code.

## Explore & Execute Project Scripts

With our project repository folder open in VS Code, and having confirmed that we can execute a Python script successfully, it's time to explore. 

Open, read, and run each project script (each file will have a .py extension) in order.

Read the code and try to figure out what each file is doing.

When you finish, you'll have an idea of some things possible using just the Python standard library. 
You'll have generated several new data files.
The streaming process will run continuously for quite a while. 
Read the comments in the file to learn how to stop the process.

- Wait for each script to finish. Did you generate a new datafile? What is the name?

```shell
python process_batch_A.py
```

```shell
python process_batch_B.py
```

```shell
python process_batch_C.py
```

```shell
python process_streaming_0.py
```
## Sync to GitHub

Now it's time to get the local work you did on your machine, 
back up to your cloud repo in GitHub.


### Option A: Use VS Code (Easy!)

1. On the VS Code side panel, click the source control icon (look for a blue bubble with an number in it).
1. Important! Above the Commit button, it will say "Message". 
1. You MUST include a commit message. 
1. In the commit message input box, type "initial results".
1. Click the down arrow on the blue "Commit" button to "Commit and Push" to your GitHub repo. 

Verify: Open a browser to your GitHub repo and verify the files have appeared. 
In addition to the original files, you should have one or more new files and an edited Markdown file. 
If not, return to VS Code and edit/execute files as needed. 
Then commit and push again.

## Additional Resources

1. For more information about Git in VS Code, see [Using Git source control in VS Code](https://code.visualstudio.com/docs/sourcecontrol/overview).
1. For more information about editing Markdown in VS Code, see [Markdown and Visual Studio Code](https://code.visualstudio.com/docs/languages/markdown).
