**DISCLAIMER**

This is made on a debian based distro. Period. The commands will be for debian based distros, i am not doing the effort to
write commands for distros i am not using because im just too lazy to care.

This also uses part of Erlice's aperture os repository (hence the apertureosnew name) because it was last updated 8 years ago and also uses neofetch so that's not cool.

We will be using fastfetch, and making simple changes to the config file. This means that you have to generate a config.jsonc file. (if you dont know how to do this, the commands will be down below, or, just use my demonstration config :p)
Keep in mind that if you want to rice this as Erlice did, you should probably use the files in their repository, shown [here](https://github.com/Erlite/apertureos)

**Info**

tiny repository to make your pc look like this! ![this!](assets/desktop.jpg)


DE: Gnome

WM theme (only relevant if youre also on ubuntu) Yaru Dark

Distro: Ubuntu 24.04.4

**Prerequisites**

Recommended if you use ubuntu: use the orange theme in ubuntu so that the files on the desktop have an orange subcolor, adding to the vibe :p

Have atleast one braincell to know where stuff is

**Step 1: Install Conky and Conky Manager 2**

RUN:

sudo apt update AND sudo apt install conky-all (if you get an error you should probably set up the repository for it, but most distros come with the repository on it anyway)

Then for installing Conky Manager 2:

Add repository:

sudo add-apt-repository ppa:teejee2008/foss 

Then run:

sudo apt update AND sudo apt install conky-manager2

Then after doing all this you have to set up the windows to match mine. Im using conky seamod, gotham, the 4 core cpu panel, and the network + process panel. The network, gotham, and conky seamod widgets are on the second screen, and the 4 core cpu panel + process panel on the other screen.

****Note**

Some things are not going to work as expected, like seamod. You have to edit these manually, because the transparency breaks. Either use nano to set the own_window_type to desktop or a file editor. I also removed the ethernet part of seamod to fit my screen, you do this by manually tagging out the network data with # at the start so that the commands get ignored. Keep in mind that i havent found a way to remove the graph, so just hide it on a part of the screen thats not rendered.

