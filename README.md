# SpotifyNoAds

Remove ads on Spotify using hosts file (Windows only)

## How does it work ?

You block Spotify ads by blocking ad servers on your computer using a file called "hosts" (C: \ Windows \ System32 \ drivers \ etc): you give a fake IP address to a domain. However, this "trick" doesn't work with newest versions of Spotify. I recovered an old version of Spotify (Spotify 1.0.80.474.gef6b503e) on my oldest computer with wich it works.

## Installation

1. Uninstall Spotify
2. Run "setup_hosts.bat" (it will prompt admin permissions)
3. If you get a success message, go to "SpotifyFolder" and run "SpotifyLauncher.exe"

## Is that safe ?

Changing hosts file is totally safe, however it break access to some servers what can break some apps/websites (like Spotify Web Version at [http://open.spotify.com/](http://open.spotify.com/). Your totally free to remove hosts by launching "remove_hosts.bat" (it will prompt admin permissions). The Spotify version in the "Spotify" folder comes from Windows Store and was just never updated (because of the patch of this "trick" in newest versions)

## Donate !

A donation is always welcome (even $ 0.01) https://paypal.me/KyloRen3600 !