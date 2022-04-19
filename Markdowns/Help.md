# ⭐ 01 - Patreon | Getting Started 
---

<info>
Last updated (4/18/2022) - (MM/DD/YYYY)
</info>

<critical>
If your patreon subscription got cancelled, the current server over-limit anime list will be scale down to default limit size without any warning instantly. But member's over-limit subscribe list will stays the same.
</critical>

## 📕 Instructions steps
---
- 🎉 1. Visit our <a href="https://patreon.com/anitrack" target="_blank">Patreon Page</a>
    - Please choose any plan you want to subscribe to.
- 🔗 2. Linking Patreon with your Discord Account
    - Visit your <a href="https://www.patreon.com/settings/apps" target="_blank"> Patreon Account Settings -> Connected Apps </a>
        - On the "Third-party apps" section click "Connect" on Discord, a popup will appear then click on "Authorize" after that.
- 🌟 3. Unlocking those Patron-only exclusive features
    - Visit your <a href="https://anitrack.co/dashboard/mybilling" target="_blank"> AniTrack Dashboard -> Subscriptions </a>
        - This might take from 1-2 minutes to update or refresh the subscription list. Please be patient.
        - On the "Server Selection" section click on the dropdown menu then select your preferred server to unlock those features...
        - Note that you can only choose one server and can transfer to another at anytime

## 🎉 Perks
---
- 📦 Tier 0 - "Free"
    - List up to 8 Anime -> \`/anime add\`
    - Subscribe up to 80 member per anime -> \`/anime subscribe\`
- 🎁 Tier 1 - "Supporter - $3"
    - List up to 32 Anime -> \`/anime add\`
    - Subscribe up to 500 member per anime -> \`/anime subscribe\`
    - Access Private Discord Channel
    - Beta feature preview
    - Access To All Patreon-only Post 
- 💎 Tier 2 - "Supporter - $5" 
    - List up to 64 Anime -> \`/anime add\`
    - Subscribe up to 1200 member per anime -> \`/anime subscribe\`
    - Import list from AniList & MyAnimeList -> \`/anime import\`
    - Customizable Notification Time -> <a href="https://anitrack.co/dashboard/mybilling" target="_blank">AniTrack Dashboad -> My Billing -> Server Settings </a>
    - Access Private Discord Channel
    - Beta feature preview
    - Access To All Patreon-only Post

# ⭐ 02 - Bot | Commands List
---
<info>
Last updated (4/18/2022) - (MM/DD/YYYY)
</info>

<warn>
Always make sure to correctly Role-lock on some sensitive command(ex: /anime add, /anime remove, /anime import, etc...) if the bot is on public server with a lot of members to avoid the disaster... ;-;
</warn>

## 🤖 Every Commands List
| Command | subCommand | Payload | Permission | Lock | Stable |
|---|---|---|---|---|---|
| /anime | add | [animeID or romaji/english], [animeNickname] | everyone, specific-role|  | ✅ |
| /anime | remove | [animeNickname] | everyone, specific-role|  | ✅ |
| /anime | import | [platform], [platform List], [Status], [Username] | everyone, specific-role | PT2 | ⚠️ |
| /anime | list | [listFilter] | everyone |  | ✅ |
| /anime | subscribe | [animeNickname] | everyone |  | ✅ |
| /anime | unsubscribe | [animeNickname] | everyone |  | ✅ |
| /anime | analytics | [options] | everyone |  | ✅ |
| /anime admin | setchannel | [selected channel] | admin, guild-manager |  | ✅ |
| /anime admin | removechannel | [] | admin, guild-manager |  | ✅ |
| /anime admin | editpermission | [enable], [command], [role] | admin, guild-manager |  | ⚠️ |
| /debug |  | [options] | everyone, server-owner, developer |  | ✅ |
| /help |  | [] | everyone |  | ✅ |
| /anime | when | Coming soon | |  | ❌ |
| /anime | rename | Coming soon | |  | ❌ |
| /anime | info | Coming soon | |  | ❌ |

## 📦 Payload Definitions
- [AnimeID] - You can this from Anilist.co website URL when viewing one of the anime "https://anilist.co/ \`[21202 <-- This part]\` /Konosuba".
- [AnimeName] - The name in Romaji or English of that Anime.
- [AnimeNickname] - This can be anything as you can recognize it.
- [Selected Channel] - Text Channel that you've selected with Discord channel selection tool.
- [Platform] - This can be AniList or MyAnimeList.
- [Platform List] - This is your Anime List(ex: Watching, Plan to watch). inside selected platform.
- [Status] - Status of those Anime in your [Platform List] (ex: Airing, Not Yet Aired).
- [ListFilter] - Filter out the List(ex: Global Server List, Personal Subscribed Anime List)
- [Enable] - If this is Enabled then the Role will be locked to selected Role but if you choose to Disabled it the command will be available publicly. This is the same action as locking the Role with @everyone.
- [Command] - Command that you want to Role-lock.
- [Role] - Choose a specific Role so only person with the Role can use [Command].
- [Options] - There will be a prelisted options available for you to choose.
- [] - Leave this empty. The command does not require you to pick or input anything.

# ⭐ 03 - AniTrack | Frequently Asked Question ( Faq )
---

<info>
Last updated (4/18/2022) - (MM/DD/YYYY)
</info>

<warn>
Please read the <a href="https://anitrack.co/help" target="_blank">Documentation & Help page</a> before reading this or asking questions in support server.
</warn>

# ⭐ Login With Discord
---
## Q: I'm having troble logging in.
A: Please try refreshing the website or delete all the cookies and browser cache then try again. If you're still having the same issue, please report in the Discord server.

# 💎 Patreon Subscription
---
## Q: I did not receive my Patreon role on support server.
A: This feature is currently under development and will be available very soon.

## Q: I just bought a patreon subscription tiers but I did not receive the access to the features.
A: Please wait 1-2 minutes and try again. Don't forgot to select Discord Server you want to unlock the features in My Billing page inside the Dashboard.

## Q: Will the price of subscription tiers ever change?
A: No. Not likely. But there might be new tiers for the Patreon page.

## Q: What happen if my subscription ran out?
A: The Guild anime size will be shrinked to original limit and you wil lose access on all Patreon-Only features. Member that subscribed to the overlimit subscribe size will not be shrink down when subscription ran out but other member may not be able to subscribe to the target Anime. You would need to remove and add the Anime again.

## Q: The Bot is offline! And skipping some airing update message.
A: As we have mentioned before. This bot is in it "Beta" state. Which we are not sure what could go wrong once we released to the public. But if it does happen please contact or ask for support in our Discord Server!

# 📦 Open-Source
---
## Q: Will the codebase ever be available for open-source?
A: No. There won't be any full open-source version of our Bot, web, and others. But we do have a seperate open-source repository package for the Bot that we've made and you can use it with your Bot.


# ⭐ 04 - Bot | About me 
---

<info>
Last updated (4/17/2022) - (MM/DD/YYYY)
</info>

⚡ [AniTrack](https://anitrack.co) is an blazingly fast and very easy-to-use Discord Bot for notifying new/first Anime episode releases within your own server's anime list.

🔥 Powered By AniList & MyAnimeList

-> Powerful [Web Dashboard](https://anitrack.co/dashboard) For Motifying Notify Frequency and Patreon Subscription.
-> /Slash commands are fully documented with it's own help descriptions.
-> We support real-time Anime search so you don't have to look up for full Anime name or Anime ID by yourself!
-> You can subscribe to each individual Anime to get pinged when that new Anime episode is released.
-> And many more...
-> Support us via [Patreon](https://anitrack.co/patreon)!

["Real-Time Anime Search GIF image" <- Click me](https://cdn.discordapp.com/attachments/964753601903857755/964753696212787230/Anime_Add.gif)

⚒️ We're in Beta

More details -> [https://anitrack.co](https://anitrack.co)

![soon](https://media.discordapp.net/attachments/964753601903857755/964753695940173864/Aired_Soon.png "Soon Embed")

![aired](https://media.discordapp.net/attachments/964753601903857755/964753695650771084/Aired_Now.png "Aired Embed")
