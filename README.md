# F-ck Avgle's AntiAdblock
The intrusive ads on avgle.com (NSFW) are intolerable, especially on low-end devices.

This script is patched regularly until avgle gets it. Please share.

**PLEASE READ BELOW FOR UPDATES**

# Requirements
### Chrome
* [uBlock Origin](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm)
* [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) _(Recommended!)_ or [Violentmonkey](https://chrome.google.com/webstore/detail/violentmonkey/jinjaccalgkegednnccohejagnlnfdag)

### Firefox / Firefox Android
* [uBlock Origin](https://addons.mozilla.org/addon/ublock-origin/)
* [Tampermonkey](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/) _(Recommended!)_ or [Violentmonkey](https://addons.mozilla.org/en-US/firefox/addon/violentmonkey/)

### Safari
* [uBlock Origin](https://github.com/el1t/uBlock-Safari/releases/download/1.14.14/uBlock0.safariextz)
* [Tampermonkey](http://tampermonkey.net/?browser=safari)

# Instructions

**Important:** Disable any other adblocker you may have. Use **_only_** uBlock Origin for _ad blocking_. You'll still need Tampermonkey (see below).

## Step 1/2:
### uBlock Origin

1. Install uBlock Origin from above.

2. Add the following to your filters:

```
avgle.com###player_3x2_container
@@||avgle.com/avideos.php
```

![Screenshot](https://i.imgur.com/Bj2UXSE.png)

3. Click 'Apply changes'

## Step 2/2:
### Tampermonkey (Chrome / Firefox / Firefox Android / Safari) 

1. Install Tampermonkey from above.

2. Click https://github.com/mun3/F-ckAvgleAntiAdblock/raw/master/fu_antiadblock.user.js

3. Click 'Install' and enjoy!

Note: On Firefox Android, you'll instead need to go to `Dashboard` | `Utilities` | `URL` | `Import`.

### Violentmonkey (Chrome / Firefox)

1. Install Violentmonkey from above. 

2. Click https://github.com/mun3/F-ckAvgleAntiAdblock/raw/master/fu_antiadblock.user.js

3. Click 'Confirm installation' and enjoy!
