AutoCliker-Blum
AutoClicker Blum is an adapted and improved autoclicker for automating the process of collecting stars in Blum games. The software supports randomization of star collection and automatic launch of games until tickets run out.

Authorship
Discussion of the software and its operation takes place in Telegram . The initial code for revision was taken HERE .

AutoCliker Blum Script Launch Instructions
Step 1: Download and Install Python
Download and install the latest version of Python from [python.org]( https://www.python.org/ ). Make sure to check the "Add Python to PATH" option before installing.

Step 2: Check Python and pip installation
Open a command prompt and enter the following commands to verify that Python and pip are installed:

python --version
pip --version
Step 3: Download the AutoCliker Blum code from GitHub
CLICK

Step 4: Install Dependencies
In the command line, navigate to the folder with the project files and install the dependencies:

cd путь/к/вашей/папке
pip install -r requirements.txt
To launch the command line directly in the desired folder, you can enter cmd in the folder's address bar.

Step 5: Launch the bot in TelegramDesktop or Web version.
The script supports both versions.

Step 6: Run the script
Run the script with the command:

python main.py
Step 7: Select the window with the Blum open
Please indicate the suggested serial number

Step 8: Enter a value between 0 and 1 to randomize the star clicks, where 1 means collecting all stars.
The choice of value depends on many factors: screen size, window, etc. I choose values ​​of 0.04 - 0.06 to collect about 140-150 stars. You need to choose the necessary value yourself.

Step 9: Getting Started
Press F6 to start the script.

Additional recommendations for work:
Reduce the size of the game window so that there are no fields around it. The script can sometimes click past the game window and a window will appear with information about closing the game.
