**1** - I'm using Kubuntu (or KDE), and ClamTk? won't start. There is an error message "Icon 'gtk-new' not present"

The solution to this is to do one of the following:

You can run
```
sudo apt-get install gnome-icon-theme-full
```

Or use a different icon theme.

**2** - I ran a scan and I'm seeing this now: "PUA.Win.Exploit.CVE\_2012\_0110"

This shows up on Ubuntu and the file "mime.cache" seems to be the trigger for it.  I believe it is a false positive and submitted it to ClamAV as such.  Here is the Virustotal link:

https://www.virustotal.com/en/file/4b57a93b9ecc8bff1a8bd917cfb873b6940a691b7eafc385c9f0e32d905ea98f/analysis/

I would leave this file in place for now, and I recommend you disable PUA scanning.