## iDead-Saver
Save your bootlooped/out-of-memory iDevice while keeping the firmware version gracefully.

Imagine your old iPhone with a crack on the screen just bootlooped because a weird-ahh tweak, and you tried to un-bootloop it by putting it into the microwave oven for 60 seconds and things got worse. With frustration all over your body, what will you do?

A. Bye bye my iPhone, I'm sending you to your daddy Tim Apple (It's actually John)

B. Hello iTunes

C. 67

Well no longer today! With simple clicking and pressing, you're free to use your iPhone un-bootlooped -- without losing your current firmware version.

This project is based on Nathan (verygenericname)'s SSHRD_Script, please support him if you can!

# Caution

1. This tool will WIPE EVERYTHING on your device. Make sure that the data on it is not important.

2. This tool does NOT support Windows, though it's not Impossible. You need to use a Linux LiveCD to use this script for now. Simply Download a Linux distro (I recommend Ubuntu / Linux Mint), and flash it onto a USB stick (4G is enough) using Rufus, then download the script and run it.

3. Do not use it on devices above iOS 17. There will be consequences. (Most iOS 16 versions for Linux users)

4. A12/A13 devices is THEORETICALLY possible, but compatibility problems needs to be fixed. For A14 users and above, just keep your phone in your microwave isn't a bad idea.

# Usage

Simply clone the project to local, run the executable "sos" and wait for it to complete.

To be exact:

Step 1. Open the Terminal (If you don't know what's a terminal on macOS, Press Command + Space, search "Terminal", and press Enter, and don't make me if you don't know what's a terminal on Linux)

Step 2. Copy the command into it and run it:

`git clone https://github,com/noncodeguy/iDead-Saver.git && cd iDead-Saver && chmod +x * && ./sos && cd ..`

Step 3. Wait for it to continue the procedure. In the progress, you need to enter DFU mode for your device. (DFU tutorial is already included in the script)

Step 4. Fresh and clean.
