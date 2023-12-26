## 3AM 🌙

Just a quick heads-up: The 3AM Plugin has been released, introducing custom fonts, animation toggles, and a privacy blur—all configurable within the Discord app. This also means that the original 3AM theme and support for other modded clients will be depreceated. I'm shifting my focus from heavily documenting the code, to a simpler, user-friendly setup from within the plugin.

### Planned Or Potential Features

#### Ideas
- Making small adjustments to Spotify Listen Along invites for a cleaner look
- Improving selectors for more reliable updates
- Automatically reinject the css instead of relying on a button
- Clean up the plugin code potentially, its very messy since the whole css is stored from within the .tsx

#### Bugs
- Adding comments to some class recolor lines
- Adjusting online status indicators that appear stretched (seemingly fixed, maybe?? I'm not sure, lol)
- Fixing the color of the Soundmoji experiment search button
- Maxwell's loading screen still sometimes shows keybind indicators

### Instructions

#### Vencord Installation

To get 3AM vibes on your Vencord:

1. Follow the [vencord plugin guide](https://github.com/Vendicated/Vencord/blob/main/docs/1_INSTALLING.md) if you havent already.
2. Download the index.tsx file from the 3AM repository and drag it into `Vencord\Vencord\src\userplugins\3AM`.
3. Run `pnpm build` from the cmd in your vencord directory.
4. Restart your discord.
5. Navigate to your plugins menu and enable the 3AM Plugin. To configure, press the cog icon.

#### Other Client Installation

There is no longer support for other modded Discord clients. 3AM only supports Vencord.

---