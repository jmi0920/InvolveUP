# Setting Up Environment (Linux)

<h2>Installing Git</h2>
Based on your distribution of Linux you many already have Git installed
on your machine. To find out open a terminal and run

`git --version`. If the terminal returns `command not found` Git is not
installed on your system and you will have to install it.

Based on your Linux distribution have different options for how to
install Git.

<h5>Arch Linux and Derivatives</h5>

    `sudo pacman -S git`

<h5>Debian-based</h5>

    `sudo apt install git-all`

<h5>Fedora (or other RPM based distribution)</h5>

    `sudo dnf install git-all`

Verify that Git is installed by running `git --version`

<h2>Cloning The Repo</h2>
Once Git is installed you can clone the InvolveUP repository from GitHub
by running:

    `git clone https://github.com/jmi0920/InvolveUP`

This will clone InvolveUP to \InvolveUP in the current directory you
are in.

<h2>Installing Android Studio</h2>

To install Android Studio go to [their website](https://developer.android.com/studio/?gclid=Cj0KCQiAoo7gBRDuARIsANeJKUaO288xUg3HHl3nuK46pR_FARpDfL8ZvyhRVBjWafGJF19a6WWxMpYaAu-OEALw_wcB) and click on the download
button. This will download the current version of Android Studio
(181.5056338 at the time of this writing) as a zip file. Once the
download has finished, move
the .zip file to where you wish to unpack it and run:

    `unzip android-studio-ide-181.5056338-linux.zip`

To finalize the installation, navigate into the /bin directory of android
studio and run:

    `./studio.sh`

This will run the Android Studio installer. It is recommended that when
installing to click "Custom Install" to also install the
Android Emulator. By installing the emulator you can test out
applications on a virtual Android machine on your computer instead of
sending it to a physical Android device.

