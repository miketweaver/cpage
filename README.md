cpage
=====
Created by Mike Weaver

CPage downloads and installs a very lightweight "Under Construction" Page.
It assumes you are running said functions in the site's root folder. 

This is a script built to be run in the terminal. It's best if you host it on your own server but if you don't want to, you can use GitHub to do so.

The command is:

. <(curl -sS https://raw.githubusercontent.com/miketweaver/cpage/master/cpage)

Self Hosted 
========

If you'd like to self host this script you'll need to download the "cpage" file from GitHub.

You'll also need to download the themes and extract them on your server. Don't extract the individual themes. They're tar.gz files. Leave them compressed.

You'll also need to edit the main cpage file.
At the very top you'll see:

siteurl="http://vpsilo.com/scripts/"

Change that URL to the location where the themes are saved. (leave the themes in the tar.gz format)

Download
========

To download our latest release, please visit the release page:

https://github.com/miketweaver/cpage/releases/latest
