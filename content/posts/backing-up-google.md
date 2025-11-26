+++
title = "Backing Up Google for Transfer"
date = "2025-11-26T13:22:05-08:00"
#dateFormat = "2006-01-02" # This value can be configured for per-post date formatting
author = "Chris"
authorTwitter = "" #do not include @
cover = ""
tags = ["Google"]
keywords = ["Google", "Takeout"]
description = "Backing up my Google Information for Transfer"
showFullContent = false
readingTime = false
hideComments = false
+++

# Backing up Google

I use a lot of Google Services:  Drive, Photos, Youtube, Messages, Home, etc.
They are pretty ubiquitous nowadays.  It's also a lot of information to move
over to a new account.

Having created my account for google services, I started the arduous task of
backing up my data so it doesn't get lost.  For nearly everything, there's
[Google Takeout](https://takeout.google.com/), which lets you make a backup of
*some* or *all* of your Google Account data, with some caveats.  Doing so is
easy, just go to the Google Takeout page linked above, and you'll be given a
huge list of services you can back up.  It's quite a lot (I didn't know that
Google offered a service for a Journal or for Assignments).  Fortunately, you
can just select the critical ones you need.  You can also specify the following:

 * Whether to use `*.tgz` or `*.zip` format
 * How large each individual back up file will be.

Depending on how much data you have selected, for instance a large number of
files in Drive or Photos, this can take several hours or even days.  Once I got
an email notification that my files had finished backing up, I went to the link
they offered and had to download 130 tarballs with a combined 189 GB of
compressed data in them.  Wowzers!

I then uncompressed each file via a quicky shell script and copied everything
over to a Synology NAS I had (`rsync` to the rescue!).  Since Synology provides
a Cloud Sync tool that lets you sync a number of storage providers (Google
Drive, OneDrive, Dropbox, Box, .etc,), I set up my destination account in a new
directory and then, after logging into the web interface, copied all my drive
folders over.

Here, I made a mistake.  I did a basic cut-n-paste of the files so that
everything from my "old" Drive account was deleted.  There are a number of
problems with this:

1. I lost all my starred favorites
2. A Google Sheets file got lost

I wasn't able to recover my starred favorites, but, thanks to my Takeout, I was
able to restore all sheets.  *phew!*

## Caveats

The one thing you can't back up is purchased TV shows & movies from Google
Play/TV/Youtube, so be prepared for that.  For that reason, I'll be keeping my
old Google account around in the event I'd like to watch something.  For any
music uploaded to Youtube Music, you *will* be able to download those as part of
Takeout.

Next up, my experience signing up for [US Mobile](https://usmobile.com)!
