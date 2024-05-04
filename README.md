# streaming-01-getting-started

## Student: Inga Miller
## Class: 44-671 Streaming Dat

## Prerequisites

You should have these downloaded and installed on your machine:

1. Python 3.10 or higher
1. VS Code
1. VS Code Extension: Python
1. Git (configured with user.name and user.email - the same email you use for GitHub)

Remember:

- **Spacing, Spelling, Capitalization**: When programming, these are critical. Always double-check!

---

## Open Project Folder in VS Code

In VS Code, open just your project repository folder, e.g. Documents/streaming-01-getting-started.

## Verify Installations / Update Default Python

In VS Code, open a terminal window (View / Terminal) and verify your software is installed and configured.

- If Mac/Linux, the default terminal should work.
- If Windows, be sure you're using a PowerShell terminal (rather than cmd).

Important: 

- In Windows, you might try `py` instead of `python`, `python3` sometimes works for me
- Type each command rather than copy & paste for best results. 
- Wait for each command to complete before running the next command.

```shell
git --version
git config Inga Miller
git config s566319@nwmissouri.edu
python --version
python -m pip install --upgrade pip wheel
```

✔️ Make sure all commands complete successfully. 
If not, post your screenshots and the text of the error message in the discussion.
They all must run successfully before continuing.

## Execute Utility Script (Diagnostics)

With your repo folder open in VS Code:

1. Click util_about.py.
1. If VS Code prompts, install the recommended Python extension.
1. Check the Python Interpreter: On the bottom-left status bar, you might see a version of Python indicated (e.g., Python 3.12.x).
1. If not, click on the bottom status bar where it should show the Python version or might say "Select Python Interpreter".
1. From the dropdown, choose your default Python version.

Use the terminal and the python command to execute the Python script. 

1. Use your VS Code terminal window from above or open a new terminal window (View / Terminal) in VS Code.

✔️ Make sure your script runs successfully. 
If not, post your screenshots and the text of the error message in the discussion.
This script must run successfully before continuing. 
---


## Explore & Execute Project Scripts

With our project repository folder open in VS Code, and having confirmed that we can execute a Python script successfully, it's time to explore. 

Open, read, and run each project script (each file will have a .py extension) in order.

You don't need to fully understand the code yet. 
Instead, read the code and try to figure out what each file is doing.

When you finish, you'll have an idea of some things possible using just the Python standard library. 
You'll have generated several new data files.
The streaming process will run continuously for quite a while. 
Read the comments in the file to learn how to stop the process.

Important: 

- If Mac/Linux, change `python` to `python3` in the commands below.
- In Windows, you might try `py` instead of `python`.
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

✔️ Make sure your scripts complete successfully. 
If not, post screenshots and the text of any error messages in the discussion.
---

## Update Edit README

Edit this README.md file. It uses Markdown, a simple and easy markup language.

- Keep the prerequisites and task headings. 
- Within the task headings, record only the commands that worked on YOUR machine. 
- Remove unnecessary instructions once you've mastered them.
- Add any additional notes that will help you in the future.

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

Common Issue: If your computer hangs because you forgot the commit message, 
just enter your message in the top line of the file it shows in the editor.
Then click the checkmark in the upper right to close that file and save your commit message.
"Sync your changes" to push to GitHub. 

✔️ Make sure your git add / commit / push completes successfully. 
If not, post screenshots, error messages, and questions in the discussion.
We've all been there when first learning Git and we can help. 
---

## Additional Resources

1. For more information about Git in VS Code, see [Using Git source control in VS Code](https://code.visualstudio.com/docs/sourcecontrol/overview).
1. For more information about editing Markdown in VS Code, see [Markdown and Visual Studio Code](https://code.visualstudio.com/docs/languages/markdown).
