# (Under Construction) Ansible Ubuntu Desktop Setup

Ansible scripts for building ubuntu desktop.

This is an opinionated version including among others:

0.  [X] [Terminator](https://gnometerminator.blogspot.com/p/introduction.html)
1.  [ ] [Oracle JDK8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
2.  [ ] [Maven](https://maven.apache.org/)
3.  [ ] [Subversion](https://subversion.apache.org/)
4.  [ ] [KDiff3](http://kdiff3.sourceforge.net/)
5.  [ ] [Meld](http://meldmerge.org/)
6.  [ ] [SublimeText3](https://www.sublimetext.com/3)
7.  [ ] [DBeaver](https://dbeaver.io/)
8.  [ ] [Chromium](https://www.chromium.org/)
9.  [X] [Chrome](https://www.chromium.org/)
10. [X] [Docker](https://www.docker.com/)
11. [ ] [NodeJs](https://nodejs.org/en/)
12. [ ] [NPM](https://nodejs.org/en/)
13. [ ] [Bower](https://bower.io/)
14. [ ] [Remmina](https://remmina.org/)
15. [X] [Skype](https://www.skype.com/en/)
16. [ ] [Dropbox](https://www.dropbox.com)
17. [X] [Gimp](https://www.gimp.org/)
18. [X] [Spotify](https://www.spotify.com)
19. [X] [VLC](https://www.videolan.org/index.html)
20. [X] Several tools like: curl, make, htop, vim...

## Installation

First, you need to install Git:

```sh
sudo apt update
sudo apt install git
```

Then use this repo script to install ansible:

```sh
git clone https://github.com/ReginaldoSantos/ansible-ubuntu-desktop.git
cd ansible-ubuntu-desktop
./install.sh
```

Then you can customize the playbook ansible-ubuntu-desktop.yml (or use as is) and run ansible:

```sh
ansible-playbook ansible-ubuntu-desktop.yml
```


I'm still learning ansible, so I'm afraid this isn't a good start for anyone.
If looking for robust stuff, give [this project](https://github.com/lvancrayelynghe/ansible-ubuntu) a try ;-)


