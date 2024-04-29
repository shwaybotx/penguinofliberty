# Penguin-of-Liberty theme version 1.52

This is an animated sddm theme with mood music, city and penguin sounds with dark humor. In the background image there is an image of the statue of liberty turned penguin, with a penguin login officer asking for a password. The sound track that plays in the background has sounds like ocean waves, gun shots, emergency vehicles and other city sounds.

# Download, Extract and Change Permission

Download the *.zip file and move it into any temporary directory on your linux computer. Once you have completed that, unzip it with this command:

    unzip penguinofliberty-master.zip

This command will extract the contents of the zip file into the current directory. If you want to extract the files into a specific directory, you can specify the directory with the -d option, like this:

    unzip penguinofliberty-master.zip -d /path/to/destination

Replace /path/to/destination with the path where you want the files to be extracted. If the directory does not exist, unzip will create it for you.

Make sure you are in the temporary folder where penquinofliberty-master.zip exists and change permissions with this command:

    chmod -R 775 penguinofliberty-master
    
# Installation

To install, copy the extracted directory with this command.
    
    sudo cp -r ./penguinofliberty-master /usr/share/sddm/themes/

# You can test it with

    sddm-greeter --test --theme /usr/share/sddm/themes/penguin-of-liberty

Lately, I've been getting errors at this point. I haven't fooled with this code for years, literally. I don't get on Github very much. I am working to fix it.

# Select as your SDDM theme

In KDE Plasma 5 or 6, click on Settings and searh for SDDM, the Login Screen settings. In there you will now see Penguin of Liberty as one of the options. Select it and click "Apply" at the bottom of the Login Screen (SDDM) System Settings. You will be prompted to enter your password.

To select your new theme for login and logout screens, open your KDM menu and search for <code>login screen</code>. Open 
Login Screen (SDDM) manager. Under themes on the left of the screen, scroll down to "Penguin of Liberty" and click it. You will need to enter your password.

# Logout

By either starting the computer, rebooting (if you have auto-login disabled) or logging out from your desktop you will come to the SDDM greeter. Enjoy your new SDDM theme!

# You can change the files

Logo:

    resources/logo.png

Background image:

    background.png
    
The particles:

    resources/lightparticle.png
    
The background music:

    resources/pol.ogg
    
# Screenshot
    
[screenshot](screenshot.jpg)

