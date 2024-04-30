# Installing Python
1. Go to [https://www.python.org/downloads/](https://www.python.org/downloads/release/python-3115/) and download the python version 3.11.5

2. Scroll down to the bottom of the page and download the installer (should be called Windows installer (64-bit))

![image](https://github.com/RabbidTurkey/turkeyautofarmerdocumentation/assets/76893259/9dbc3720-a3a8-43cd-8b1d-d16e5bb23884)

3. Click on the downloaded installer and proceed with the installation process. EXTREMELY IMPORTANT: Make SURE to tick the `ADD TO PATH` checkbox before beginning installation.

# Getting your files ready
Upon your purchase of the product, you will be sent a one-time link where you can download all the required files. These are all the files that you will have. 

![image](https://github.com/RabbidTurkey/turkeyautofarmerdocumentation/assets/76893259/4471cc7c-849b-4771-8a3d-1241d15bd941)


# Setting up your autofarmer folder
1. Navigate to the directory where you have Python installed. This is usually located in some place like: `C:\Users\your_device_name\AppData\Local\Programs\Python\Python311`
2. Create a new folder in this directory. Feel free to name it whatever you want - something like `Autofarmer` works just fine. 
3. Place all the files downloaded from the link you've been sent, to this `Autofarmer` folder.

This is what the contents of your new folder should look like:

![image](https://github.com/RabbidTurkey/turkeyautofarmerdocumentation/assets/76893259/59214bd1-461e-4ee0-8f0a-d77ea2590f28)

# Download required modules
1. Stay in the directory. Right-clicking will give you many options - choose `Open in Terminal`
![image](https://github.com/RabbidTurkey/turkeyautofarmerdocumentation/assets/76893259/b5ca3358-07e7-40d7-8bcb-c64bd156490c)
2. Enter the following command into the terminal: `pip install -r requirements.txt`

A series of installations will begin - don't interrupt this process, and wait a few seconds until it completes.

# Setting up emulator
1. Open an emulator of your preferred choice (I would recommend LDPlayer the most for this), and head to your emulator settings
2. Make sure your emulator's dimensions are 1280x720 pixels
![image](https://github.com/RabbidTurkey/turkeyautofarmerdocumentation/assets/76893259/3f99e6e4-b49c-432b-aa33-0208198c11a3)

3. Go to `other settings` in emulator settings and enable ADB debugging (`open local connection`).
![image](https://github.com/RabbidTurkey/turkeyautofarmerdocumentation/assets/76893259/4b38f91a-e0a4-428e-90d5-41640cd75b16)

4. Click on Save - you're all done!

# Setting up game
1. Head to your army presets, and set a preset (between numbers 1-5) with what you want to farm with. For example - T2 Cavalry, or T4 Cavalry

# Customizing your autofarmer
To customize your autofarmer, you can modify the contents in the `settings.json` file. The contents are split into four sections:
1. Authorization: enter your license key in here (received on purchase)
2. User customization: enter your account's statistics such as travel speed, what kingdom you want to farm in, etc 
3. Bonus features: choose whether you want to activate bonus features such as gift collecting, and humanlike farming algorithms. (0 represents no, and 1 represents yes)
4. Lag delays: adjust your lag settings based on your PC's performance - each number is represented in seconds (s)

Each of the fields should be self-explanatory, but please ask me if you have any questions. This is an example of a `settings.json` file:

![image](https://github.com/RabbidTurkey/turkeyautofarmerdocumentation/assets/76893259/fe27c3bf-bfe0-4ac9-8140-14fdb6c1c43b)


# RUN THE AUTOFARMER
You're finally good to go!! You can create a shortcut for the `autofarmer.py` file and place it on your desktop. Follow the prompts once you run the file, and you should be up and running!

# SUPPORT
If you have any questions or concerns, feel free to contact me at any time. I'm more than happy to guide you through the process of setting up, or dealing with uncalled-for errors.


