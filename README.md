Renpy-Launcher-POC
A proof of concept for launching exes on Renpy engine.
While this is a python-based program, the ability to other exes with privilage escalation is unknown for the time being.

To make changes on the progam to use your own exe, go to script.rpy which is available in the zip file and change the target exe in the brackets. The full source code 
is also in the zip file.
i.e.: subprocess.Popen("C:\Program Files\Google\Chrome\Application\chrome.exe")
