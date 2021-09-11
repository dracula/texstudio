### [TeXstudio](https://www.texstudio.org/)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

    git clone git@github.com:dracula/texstudio.git

#### Install manually

Download using the [GitHub .zip download](https://github.com/dracula/texstudio/archive/refs/heads/master.zip) option and unzip them.

#### Activating theme

1. Backup your previous TeXstudio settings: `Options` > `Save Profile`
2. Create a copy of the backup file and rename it to `dracula.txsprofile`.
3. Open dracula.txsprofile file in your text editor and replace the [formats] section with the content found in `dracula.formats`. 
4. Open Texstudio: `Options` > `Load Profile` and load the edited dracula.txsprofile.
5. (Optional) Works better with Adwalta Dark: `Options` > `Configure TeXstudio` and change the Style.
6. Restart and boom! It's working!
