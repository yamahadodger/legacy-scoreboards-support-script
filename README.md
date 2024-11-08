<img alt="GameBanana" src="https://images.gamebanana.com/static/img/banana.png" style="width: 13px"/></a> [**GameBanana page**](https://gamebanana.com/scripts/10691)

# Legacy Scoreboards Support Script
A fix for older HUDs' scoreboards which were made before Tough Break Update.

# What it does exactly?
It disables 3D character model in scoreboard while keeping it on in HUDPlayerClass (when playing, with scoreboard disabled).

You can also disable 3D model entirely by following the `How to use it?` section below.

# How to use it?
To utilize the config entirely, make sure to download all config files.

To make this config function, use the following game launch parameter: `+exec sbo`

You can exclude certain files from execution by commenting them out. To disable 3D model entirely, edit the [sbo.cfg](https://github.com/yamahadodger/legacy-scoreboards-support-script/blob/master/yamahadodger/sbo.cfg) file, then comment out the line: `exec sbo/conf2`

The 3D model should be gone and the config is ready to be reloaded. To reload the config, type in the game console prompt: `sbo.reload`

# License:
This work is marked with <a href="https://creativecommons.org/publicdomain/zero/1.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer">CC0 1.0 Universal <span data-v-a0d4e8a8="" class="icon"><img data-v-a0d4e8a8="" width="20" height="20" src="https://chooser-beta.creativecommons.org/img/cc-logo.f0ab4ebe.svg"><img data-v-a0d4e8a8="" width="20" height="20" src="https://chooser-beta.creativecommons.org/img/cc-zero.f5450231.svg"></span></a>
