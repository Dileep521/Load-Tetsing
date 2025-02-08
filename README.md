✅ Steps to Push New Files in the JMeter Folder to GitHub**

**Step 1:** Open Git Bash / Command Prompt
Navigate to your local Git repository:
cd "D:/Dileep/ezSCM/Load Testing"

**Step 2:** Check the Status
See which files have been added or modified:
git status
This will show the new files in the JMeter folder.

**Step 3:** Add the Files
To add all files in the JMeter folder:
git add JMeter/
Or, if you want to add only a specific file:
git add JMeter/yourfile.jmx

**Step 4:** Commit the Changes
Run this command to save the changes:
git commit -m "Added new JMeter test files"

**Step 5:** Push to GitHub
Now, push the changes to your GitHub repository:
git push origin main

**Step 6:** Verify on GitHub
Go to your repository and check if the JMeter folder contains the new files.
