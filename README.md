# Initial Setup Of a Container for SteamCMD

Run the following commands
<pre> (sudo) apt update
  (sudo) apt upgrade
  (sudo) apt install software-properties-common
  (sudo) add-apt-repository multiverse
  (sudo) dpkg --add-architecture i386
  (sudo) apt update
  (sudo) apt install lib32gcc-s1
  (sudo) apt install steamcmd
  (sudo) adduser steam
  su - steam
  steamcmd
  quit
  
</pre>
