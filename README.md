# blocklists
This repository is meant for only my own personal use, to synchronize my customizations between browser instances.

You are welcome to use them, but if you do, be sure you understand the security implications of giving me control over how your adblocker filters elements.
(It is recommended that you do not use my lists directly; instead, fork this repository and use the copies in your fork so they are fully under your own control.)

## List URLs
```
https://raw.githubusercontent.com/AJMansfield/blocklists/refs/heads/main/discord.txt
https://raw.githubusercontent.com/AJMansfield/blocklists/refs/heads/main/youtube.txt
```

## Trusted Rules
Some types of blocklist rules have the potential to run arbitrary code or to instruct your browser to send sensitive information to arbitrary remote servers.
UBlock and other blockers wisely choose to block all rules of these potentially-harmful types from untrusted sources.
I am able to trust my own rules lists to contain only uses of these rules types that I personally am comfortable with.
You, on the other hand, _should not_.

The following directions, therefore, are meant ONLY as a reminder for my own use:

To enable my trusted rules in ublock, modify the `trustedListPrefixes` setting in the advanced settings config to include `https://raw.githubusercontent.com/AJMansfield/blocklists/refs/heads/main/`. i.e. 
```
             trustedListPrefixes ublock- https://raw.githubusercontent.com/AJMansfield/blocklists/refs/heads/main/
```
