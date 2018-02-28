# F-ck Avgle's AntiAdblock
The intrusive ads on avgle.com (NSFW) are intolerable, especially on low/mid-end devices. The script provides 2 key features:
* Ad-blocking on avgle.com
* Display of direct links to videos. Tip: the 'Download' button! :)

Patches will be made until Avgle reverses its decision. Please share and let our voices be heard.

#### Note: Effort in releasing patches will be gradually reduced due to work commitments. From now on, patches will be released only when donation target (0.02 Bitcoin) is reached: ####

[1He9w4Qt2MSc5qjucHfBDXQzEAT866pmd4](https://blockchain.info/address/1He9w4Qt2MSc5qjucHfBDXQzEAT866pmd4)

You can also find us on Freenode IRC at #faaa

# Requirements | 必要なソフトウェア
### Chrome
* [uBlock Origin](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm)
* [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) _(Recommended!)_ or [Violentmonkey](https://chrome.google.com/webstore/detail/violentmonkey/jinjaccalgkegednnccohejagnlnfdag)

### Firefox / Firefox Android
* [uBlock Origin](https://addons.mozilla.org/addon/ublock-origin/)
* [Tampermonkey](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/) _(Recommended!)_ or [Violentmonkey](https://addons.mozilla.org/en-US/firefox/addon/violentmonkey/)

### Safari
* [uBlock Origin](https://github.com/el1t/uBlock-Safari/releases/download/1.14.14/uBlock0.safariextz)
* [Tampermonkey](http://tampermonkey.net/?browser=safari)

# Instructions | 説明

**Important:** Disable any other adblocker you may have. Use **_only_** uBlock Origin for _ad blocking_. You'll still need Tampermonkey (see step 2).

_**重要:** uBlock Origin以外の広告ブロックアドオンをすべて無効にしてください。Tampermonkey をインストールしてください（インストール手順は (2) を参照してください)_

## Step 1/2:
### uBlock Origin

1. Install uBlock Origin from "Requirements" | _uBlock Origin をインストールしてください。リンクは「必要なソフトウェア」を参照してください_

2. Add the following to your filters: | _ィルタに下記のルールを追加してください:_

```
avgle.com###player_3x2_container
@@||avgle.com/avideos.php
avgle.com#@#script:inject(abort-on-property-read.js, ExoDetector)
```

![Screenshot](https://i.imgur.com/Jbah0IS.png)

3. Click 'Apply changes' | _[Apply changes]を押してください_

Note: Do not change '3rd-party filters'.

## Step 2/2:
### Tampermonkey (Chrome / Firefox / Firefox Android / Safari) 

1. Install Tampermonkey from "Requirements" | _Tampermonkey をインストールしてください。リンクは「必要なソフトウェア」を参照してください_

2. Click https://github.com/mun3/F-ckAvgleAntiAdblock/raw/master/fu_antiadblock.user.js

3. Click 'Install' and enjoy! | _[Install] を押してください_

Note: On Firefox Android, you may instead need to go to `Dashboard` | `Utilities` | `URL` | `Import`.

### Violentmonkey (Chrome / Firefox)

1. Install Violentmonkey from "Requirements" | _Violentmonkey をインストールしてください。リンクは「必要なソフトウェア」を参照してください_

2. Click https://github.com/mun3/F-ckAvgleAntiAdblock/raw/master/fu_antiadblock.user.js

3. Click 'Confirm installation' and enjoy! | _[Install] を押してください_

## Thanks
These amazing people have contributed to this project:

* Junta
* Keita
* Momonari
