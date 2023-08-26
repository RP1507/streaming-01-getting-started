# streaming-01-getting-started

Ryan Smith - Updating the ReadMe file

> Get started with Python for streaming analytics

Set yourself up for productivity and collaboration.
We assume no prior programming experience and that you want to 
get productive as quickly as possible.

## Prerequisites

1. Python 3.10 or higher
2. VS Code
3. VS Code Extension: Python
4. Git (configured)

Remember:

- **Spacing, Spelling, Capitalization**: With computers, these are critical. Always double-check!

---

## Verify Installations / Update Default Python - Verified

In VS Code, open a terminal window (View / Terminal).
If macOS/Linux, change `python` to `python3` in the commands below.

```shell
git --version
python --version
python -m pip install --upgrade pip wheel
```

## Execute Utility Script (Diagnostics) - Script was executed

With your repo folder open in VS Code: Able to run this, saved int he util_about.txt file.
This was the first time that I have used VS code for python. I have used it for other languages, but not python. I was used to using a shell or notebooks.
I did have to install the python extension. 

1. Click util_about.py.
2. If VS Code prompts, install the recommended Python extension.
3. Check the Python Interpreter: On the bottom-left status bar, you might see a version of Python indicated (e.g., Python 3.10.x).
4. If not, click on the bottom status bar where it should show the Python version or might say "Select Python Interpreter".
5. From the dropdown, choose your default Python version.
6. In VS Code, open a terminal window (View / Terminal).
7. If macOS/Linux, change `python` to `python3` below.

```shell
python util_about.py
```
---


## Explore & Execute Project Scripts - Looked through the multiple scripts and the executed.

Running though the different batch scripts. 

With your repo folder open in VS Code, start exploring.
Open, read, and run each project script (each file will have a .py extension) in order.
You don't need to fully understand the code yet. 
Instead, try to figure out what each file is doing.

When you finish, you'll have an idea of some things possible using just the Python standard library. 
You'll have generated several new data files.
The streaming process will run continuously for quite a while. 
Read the comments in the file to learn how to stop the process.

## Update Edit README  - Edited by Ryan Smith

Edit this README.md file. It uses Markdown, a simple and easy markup language.

- Keep the prerequisites and task headings. 
- Within the task headings, keep only the commands that worked on YOUR machine. 
- Remove unnecessary instructions once you've mastered them.
- Add any additional notes that will help you in the future.

## Sync to GitHub

Now it's time to get the local work you did on your machine, 
back up to your cloud repo in GitHub.


### Option A: Use VS Code (Easy!) - This was quite handy. 

1. On the VS Code side panel, click the source control icon (look for a blue bubble with an number in it).
2. Important! Above the Commit button, it will say "Message". 
3. You MUST include a commit message. 
4. In the commit message input box, type "initial results".
5. Click the down arrow on the blue "Commit" button to "Commit and Push" to your GitHub repo. 

Verify: Open a browser to your GitHub repo and verify the files have appeared. 
In addition to the original files, you should have one or more new files and an edited Markdown file. 
If not, return to VS Code and edit/execute files as needed. 
Then commit and push again.

Common Issue: If your computer hangs because you forgot the commit message, 
just enter your message in the top line of the file it shows in the editor.
Then click the checkmark in the upper right to close that file and save your commit message.
"Sync your changes" to push to GitHub. 

### Option B: Use Git Bash or Terminal Commands (Easy as well): - The way I was previously used to doing the commits as well as using TortoiseGit

Open a new `Git Bash` or Terminal window. Run the following commands one at a time.
They will first add all the files (add "dot"). 
Then they will commit the changes with a message. 
Finally, they will push the changes up to GitHub.

```
git add .
git commit -m "initial results"
git push origin main
```


-----

Did not run into any issues through this part. Updating the file to Kelvin next.

## General Recommendations and Troubleshooting

The following are general recommendations and troubleshooting tips.

### Issue: VS Code - No Source Control Icon

Suggestion: If you're in VS Code, and you don't see the Source Control icon with a blue bubble, right-click on the sidebar icons, and make sure "Source Control" is checked.  

### Issue: VS Code wants to install an extension

If VS Code suggests an extension, it's often good to go ahead and try it. 
Do a search on the extension to learn more. VS Code suggestions are usually helpful. 

## Additional Resources

1. For more information about Git in VS Code, see [Using Git source control in VS Code](https://code.visualstudio.com/docs/sourcecontrol/overview).
2. For more information about editing Markdown in VS Code, see [Markdown and Visual Studio Code](https://code.visualstudio.com/docs/languages/markdown).
