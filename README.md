# Easy-qubes

> The Hitch Hikers Guide to Qubes OS, by Matt and Kieran.
> Qubes offers their own [Documentation](git@github.com:mattcoding4days/easy-qubes.git). Our guide
> begins at the initial setup [here](https://www.qubes-os.org/doc/installation-guide/#initial-setup)

## :warning: Things you should likely not do

1. **DO NOT** enable tor updates for Whonix, as who ever owns the majority of the nodes on TOR
   owns the network.    
   
2. One issue with Qubes is it only supports one desktop environment officially, which is Xfce.
   There is a KDE implementation but it is not officially supported and therefor we **DO NOT**
   reccomend using it.

## :keyboard: Generic linux commands to help you

> Do not type in the dollar sign, it represents the shell prompt.
> Directory is also called a `Folder`

```bash
# List absolute path to your present working directory
$ pwd

# move back one directory
$ cd ..

# cd into the home directory, the tilde `~` operator represents home in the unix world
$ cd ~

# if you are in your home directory cd into the Downloads directory
$ cd Downloads

# List the contents of your current directory
$ ls

# List the contents of your current directory and show the file permissions
$ ls -l

# List the contents and all hidden files (also known as dot files)
$ ls -a

# make a directory (new folder) called `Jorts`
$ mkdir Jorts

# Remove the folder called `Jorts`
$ rmdir Jorts

# Create a new file called `jorts.txt`
$ touch jorts.txt

# Remove the `jorts.txt`
$ rm jorts.txt
```

## :scroll: Whonix

> Informative blurb about whonix

<div align="Center">
  <img src="assets/whonix-overview.webp">
</div>

## Desktop Environment

> The desktop environemtn on Qubes is called [Xfce](https://github.com/mattcoding4days/easy-qubes)

1. Opening the settings manager application
   * click on the **start menu** in the top left
   * click on **System Tools**
   * click on **Settings Manager**
   * click on **Appearance**
   * click on **Fonts**
   * Adjust the **DPI** value `**Custom DPI settings: [92]`

## Templates

1. Arch linux

## Updates and System management

## 

### [Qubes Back up system](https://github.com/mattcoding4days/easy-qubes)

> Create the backups

```bash
# make the directories needed
$ mkdir -p ~/backup/etc/qubes && mkdir -p ~/backup/etc/qubes-rpc

# copy files from root space into the backup folders you just made
$ cp -a /etc/qubes/* ~/backup/etc/cubes/ && cp -a /etc/qubes-rpc/* ~/backup/etc/qubes-rpc/
```

## Vpn

## Obsidian

## Customized network programs

### Macchanger


