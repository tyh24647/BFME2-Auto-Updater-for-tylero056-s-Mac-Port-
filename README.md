# The Lord of the Rings - The Battle for Middle-Earth II Auto-Updater (for tylero056's Mac Port)
Installs an auto-updater for my (tylero067) macOS port of "The Lord of the Rings - The Battle for Middle-Earth II". 

**Don't have the game?** Download the BFME2 Mac Port installer here: [BFME2 + ROTWK Installer](https://drive.google.com/file/d/1yxnUYsQhQoKZqEjV1D1q_9BTpO7dQPe3/view)

This package will attach an updater object which will run in the background when BFME2 is Launched, which checks my
update server to see if any updates are available.

If an update is available, it will prompt the user to install the update before the game opens.

You can view my (tylero056 is my other username) progress of my Mac port [here](https://github.com/tyh24647/Lord-of-the-Rings---Battle-for-Middle-Earth-II-Updater-Mac-OSX-Port-)

[Join the discussion/download the game on my Reddit!](https://www.reddit.com/r/Bfme2/comments/7e68bq/updated_mac_version_download_repostwas/)

--------------

### Latest update (from my post on [reddit.com/r/bfme2](https://www.reddit.com/r/Bfme2/comments/7e68bq/updated_mac_version_download_repostwas/))

Hey guys!

I updated my Mac port which fixes the auto-defeat issues, various graphics glitches, and stability issues. I also added support for macOS High Sierra, added WorldBuilder, the newer patches (BFME2 v1.6 and ROTWK v2.02) and now have separate launchers for BFME2 and ROTWK.

~~*I am still unable to get online play working*~~ Now that T3AOnline is working on BFME1 for Mac, I will be implementing this in the same way for BFME2/ROTWK. This will be my primary focus for the next update, and my other goal is to finally get Edain mod working--thanks for your patience!

NOTE: ~~*Make sure to delete the old version of the app, if you'd installed a previous build--otherwise the installer won't work.*~~ I've added the ability for future updates to just be small patches via the updater app, so in the future you won't have to re-download the whole application and lose your save files! :)

Please let me know either here or in a PM if you have any issues!

&nbsp;

**DOWNLOAD LINKS:** 

- ~~*Google Drive: https://drive.google.com/open?id=1yxnUYsQhQoKZqEjV1D1q_9BTpO7dQPe3*~~ &nbsp; <-- old version

- **[BFME2 + ROTWK Installer](https://drive.google.com/file/d/1yxnUYsQhQoKZqEjV1D1q_9BTpO7dQPe3/view)**: Online not working currently, but will be fixed in the next patch

- **[Updater/Patcher + Mods Launcher (Standalone)](https://drive.google.com/file/d/1ewBNH8erOQGyh3BaXGiP4TXrtaHjMJHQ/view)**: Works with BFME 1 and 2, and ROTWK

- **[BFME1 Installer w/ extras](https://drive.google.com/open?id=1PP6HgZkYzoorb7AKzsF91S1qeZWyma11)**: Full game with updater/mods manager, T3A, WorldBuilder, etc.

&nbsp;

***NOTE:***
*If any of the above installers freeze or the installation fails, force quit the installer, open Terminal, and enter the following command:*

    sudo spctl --master-disable 

*After this, rerun the installer and you'll be all set!*

&nbsp;

**EDIT:** Just a heads up for High Sierra users--this installer runs a script that allows it to be installed from an 'unidentified developer', because I didn't code-sign it with my Apple Dev license... I'm not EA games, nor will I pretend to be.

**EDIT 2:** I am currently finishing up an updater app so that the game doesn't have to be re-downloaded and reinstalled whenever there's a patch/update. 

**EDIT 3:** Launch day for my BFME1 port and updater app has arrived! Check them out, join the discussion, and download them here: https://www.reddit.com/r/Bfme2/comments/7pull0/bfme1_mac_port_installer_includes_online_play_t3a/
&nbsp;

-----------------

### My To-Do List (Upcoming features/bug fixes):

- [X] Edain Mod

- [X] HD Textures

- [X] Better shaders/lighting effects

- [ ] Server configuration for auto-updater

- [X] Attach auto-updater to the game

- [ ] Fix black screen/game crashes in 'evil' campaign during certain levels

