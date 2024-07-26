# pihole-regex-wildcard-blocking

Quick personal blocking reference.

Pi-hole does not currently have a way to mass-import regex white/black-listing the way it does for Adlists, so for now, you'll need to copy-paste whatever you want. jfb and DL6ER discuss it here: https://discourse.pi-hole.net/t/collection-of-regex-for-blacklisting/43178/9

I will be segmenting these into a tree structure to make it as organized as possible, just in case the feature ever gets added and people don't want to block everything - you'll be able to pick and choose later.

In the meantime, you'll need to add things manually.

## If you receive death threats

If your wife threatens to kill you for blocking BookFace or your kids threaten to kill you for blocking Instagram, reminder: 

1) Create a Group (eg. "Boss-Lady")
2) Add their devices by MAC in Clients
3) Create a double entry of the regex but whitelist it
4) Choose the group you want it to apply to (don't forget to remove the "Universal" group so you don't whitelist it on the entire network)

https://github.com/borthick/pihole-regex-wildcard-blocking
