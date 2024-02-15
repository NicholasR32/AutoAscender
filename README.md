## Have you heard of [Cookie Clicker?](https://store.steampowered.com/app/1454400/Cookie_Clicker/)

- You bake cookies, to buy upgrades, to bake even more cookies.
- Once you reach a certain threshold of cookies baked, you can ["ascend"](https://cookieclicker.fandom.com/wiki/Ascension) to restart the run, but gain permanent boosts and heavenly upgrades.
- There is an [achievement](https://cookieclicker.fandom.com/wiki/Endless_cycle) for ascending **1000** times.
- At a certain point in progression, ascending a fresh run only takes maybe 10-20 seconds, or less if you are very strategic. But this can still add up to hours of grinding the same simple series of clicks repeatedly, so...

I learned [AutoHotkey](https://www.autohotkey.com/docs/v2/) at a basic level and wrote a script to automate this. Hooray.

## How it works
- Repeat the following for how many runs you need to reach 1000:
    - Buy this round of upgrades 5-6 times:
        - On a fresh ascension, move the mouse and click the "Buy All Upgrades" button.
        - Move the mouse to collapse the upgrade list.
        - Move the mouse to shift-buy as many cursors as possible.
        - Move down to buy as many grandmas as possible.
    - *Once enough upgrades and buildings have been bought, and enough CpS (cookies per second) has been reached, you should have gained a few prestige levels.*
    - Move the mouse to the Legacy button, and press Enter to ascend.
    - Press Esc to cancel the animation of the big cookie shattering, saving valuable seconds.
    - In the heavenly shop, click Reincarnate, and press Enter to confirm.
    - That's 1 out of 1000.

Notes:
- An ascension doesn't count towards this achievement if you don't gain at least one prestige level, hence why you must buy enough buildings and upgrades to reach the required CpS.
- I put brief 100ms delays between most inputs, just to make the overall system a little less janky, as sometimes the macro can be too fast for the game.
- This still takes several hours (around 5) to get the achievement, and is best done when AFK since you can't use your mouse at the same time. But at least you don't have to sit around and click the same buttons for 5 hours!

*Ta-da!*

![Auto Ascender in action.](https://github.com/NicholasR32/AutoAscender/blob/main/imgs/autoascender.gif)