# autocompilegpg-offline
Offline version of https://github.com/mathwhiz1212/autocompilegpg. A script that automatically compiles and installs or upgrades GnuPG for linux in enviroments where there is unreliable or nonexistant internet.

This script installs GnuPG-1.4.19 or upgrades current version to GnuPG-1.4.19.

The goal of this script is to upgrade all of the GnuPG V.1.* to V.1.4.19 as there are many vulnerable versions floating around, even the last version is vulnerable.

Currently this script requires: A debian based linux distro, dpkg  and sha1sum.

Please check that the sha1sum checksums match that of the files e.g. sha1sum GnuPG1.4.19offlinesudo.sh and compare it with the .sha file.

This script has been tested to work on Linux mint. For operating systems that do not have sudo installed please use the nosudo version of the script, you need to run the nosudo script as root for it to run successfully.

