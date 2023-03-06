## Unofficial guide for [Bing Rewards](https://bitbucket.org/bing-rewards/bing-rewards)
Made by Spoobie

If you still need help, join our [Discord server](https://discord.gg/VrbBG5bEwn).

This guide is designed to be accessible for anyone, regardless of their level of computer experience.. The following are instructions to get you a base level of the installation, including programs and tools to get started.

**__Installing Python and pip:__**
```
1. Go to the Python website and download the appropriate version of Python for your operating system. ``` 
Download page - https://www.python.org/downloads/
Windows (x64) - (https://www.python.org/ftp/python/3.11.2/python-3.11.2-amd64.exe)
```2. Once the download is complete, run the installer.
3. During the installation process, make sure to select the "Add Python to PATH" option, which will ensure that you can use Python from PowerShell and other command line interfaces.
4. Open the Command Prompt: Click the "Start" button and type "cmd" in the search bar. Click the "Command Prompt" option to open it.Type "python" to verify that Python has been installed correctly. If everything is working properly, you should see the Python version number printed to the console.    
5. Download the pip installer: Go to ```
https://bootstrap.pypa.io/get-pip.py 
```in your web browser and save the file to your computer.
6. Navigate to the location of the get-pip.py file: In the Command Prompt, type "cd " followed by the file path where the get-pip.py file is located on your computer, and press Enter. For example, if the file is saved in your Downloads folder, type: cd C:\Users<your username>\Downloads
7.Run the installer: Once you are in the directory containing the get-pip.py file, type "python get-pip.py" and press Enter. This will start the installation process.
8.Verify the installation: After the installation is complete, you can verify that pip has been installed by typing "pip" in the Command Prompt and pressing Enter. If you see a list of commands, then pip is successfully installed on your computer.```


**__Download the bot:__**
```
1. Go to the bot repo site and click the ... on the right of the screen, click Download Repository. Links below for ease. ```
Repo: https://bitbucket.org/bing-rewards/bing-rewards/src/master/
Direct Link: https://bitbucket.org/bing-rewards/bing-rewards/get/9ff614ed6b0403589f447c356c44554d1ae8ca2f.zip ```
2. Extract the zip file. (right click, 7-zip, extract here)
3. For the purposes of this tutorial we'll be using a file name of 'bing-rewards' so rename it if you need to.
4. Put the file in your C:\ directory. Your file path should look like C:\bing-rewards
```
**__Setup and Run:__**
My beautiful formatting breaks here because discords version of markup sucks. Partially copied from bitbucket.

1. Open cmd and type: `cd C:\bing-rewards\`
3. Install requirements.txt file included in the repo: `pip install -r BingRewards/requirements.txt`.
4. Create/update config file by running `python3 BingRewards/setup.py` or `python BingRewards/setup.py`
     -  **Please note**: Your credentials will be stored as base64 encoded text.
5. You must have signed onto your account using this machine before. Open Chrome or Edge and visit https://login.live.com. The site may ask to send you a verification email or text.

From here you technically have everything you need to continue. If you have problems I suggest you ask in <#1076121582637949089> or read the readme. (open readme.md with notepad++)

**__TO DO:__**
How to schedule a task.
How to run the script and different operators.
