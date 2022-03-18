# problem-solution

# 'npm' is not recognized as internal or external command, operable program or batch file
Just add:

;C:\Program Files\nodejs\
To the end of your Path variable on the "User variable" section of the Environment Variables on the System Properties.

After that, reopen your command prompt and type

npm
This should work.

# Other solution
Follow the steps below for Windows users:

Go to My Computer Properties
Click Advanced System Setting from the Left bar of a window.
Now you have a System Properties window. Click Advanced
Then, Click Environment Variable button
Now you have Environment variable window: From System Variable, Select Path
Click Edit
At the end of the Variable value, add ;C:\Program Files\nodejs\

Note: If you have installed nodejs on other drives then please act accordingly.

Click Ok all the open dialogue box
Very important Note: "Close your Command Prompt And Restart Again" (It's very important because if you didn't restart your command prompt then changes will not be reflected.)

Now you can use the npm command anywhere

# Other solution
Uninstall the node version installed, for example, nvm uninstall 10.15.3
Make sure no other node versions are there, nvm list
Then, install the version needed, for example, nvm install 10.15.3. This should give you an output as preceding.
Downloading node.js version 10.15.3 (64-bit)...
Complete
Creating C:\Users\SibeeshVenu\AppData\Roaming\nvm\temp

Please note that from the above command, the npm is also installed.
Now use the version you need, nvm use 10.15.3 and type npm
