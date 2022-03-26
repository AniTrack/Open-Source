# 01 Patreon Documentation Section 
---
<critical>
If your patreon subscription got cancelled, the current server overlimit anime list will be scale down to default limit size without any warning instantly. But member's subscribe list on overlimit subscribe list will stays the same.
</critical>
<info>
Don't worry if you didn't link your Discord Account before purchasing, The Bot will always rescan the Patrons every few minutes. 
</info>


## Instructions steps
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

## Perks
---
- 📦 Tier 0 - "Free"
    - List up to 8 Anime -> \`/anime add & addsearch\`
    - Subscribe up to 80 member per anime -> \`/anime subscribe\`

- 🎁 Tier 1 - "Supporter - $3"
    - List up to 32 Anime -> \`/anime add & addsearch\`
    - Subscribe up to 500 member per anime -> \`/anime subscribe\`
    - Access Private Discord Channel
    - Beta feature preview
    - Access To All Patreon-only Post
    
- 💎 Tier 2 - "Supporter - $5" 
    - List up to 64 Anime -> \`//anime add & addsearch\`
    - Subscribe up to 1200 member per anime -> \`/anime subscribe\`
    - Import list from AniList & MyAnimeList -> \`/anime import\`
    - Customizable Notification Time -> <a href="https://anitrack.co/dashboard/mybilling" target="_blank">AniTrack Dashboad -> My Billing -> Server Settings </a>
    - Access Private Discord Channel
    - Beta feature preview
    - Access To All Patreon-only Post

# 02 All Commands List
---
<warn>
Always make sure to correctly Role-lock on some sensitive command(ex: /anime add, /anime remove, /anime import, etc...) if the bot is on public server with a lot of members to avoid the disaster... ;-;
</warn>

## Payload Definitions
- [AnimeID] - You can this from Anilist.co website URL when viewing one of the anime "\`https://anilist.co/ [21202 <-- This part] /Konosuba\`".
- [AnimeName] - The name in Romaji or English of that Anime.
- [AnimeNickname] - This can be anything as you can recognize it.
- [Selected Channel] - Text Channel that you've selected with Discord channel selection tool.
- [Platform] - This can be AniList or MyAnimeList.
- [Platform List] - This is your Anime List(ex: Watching, Plan to watch). inside selected platform.
- [Status] - Status of those Anime in your [Platform List] (ex: Airing, Not Yet Aired).
- [ListFilter] - Filter out the List(ex: Global Server List, Personal Subscribed Anime List)
- [Enable] - If this is Enabled then the Role will be locked to selected Role but if you choose to Disabled it the command will be available publicly. This is the same action as locking the Role with @everyone.
- [Command] - Command that you want to Role-lock.
- [Role] - Choose a specific Role so only person with the Role can use [Command]

## Command Syntax List
| Syntax      | User Permission        | Command        | Command Payload                                |
| ----------- | ---------------------- | -------------- | ---------------------------------------------- |
| anime       | anyone or custom       | add            | [AnimeID] [AnimeNickname]                      |
| anime       | anyone or custom       | addsearch      | [AnimeName] [AnimeNickname]                    |
| anime       | anyone or custom       | import         | [Platform] [Platform List] [Status] [Username] |
| anime       | anyone                 | list           | [ListFilter]                                   |
| anime       | anyone                 | subscribe      | [AnimeNickname]                                |
| anime       | anyone                 | unsubscribe    | [AnimeNickname]                                |
| anime admin | admin or guild manager | setchannel     | [Selected Channel]                             |
| anime admin | admin or guild manager | removechannel  | -                                              |
| anime admin | admin or guild manager | editpermission | [Enable] [Command] [Role]                      |
| debug       | anyone                 | -              | -                                              |
