# The *CRAZY* [Forsaken](https://www.roblox.com/games/18687417158/Forsaken) script
- 60+ features![^1]
- over a year of development![^5]
- 3 UI styles if you dont like the default one![^2]
- 0 AI Usage.[^3]
- our own anticheat for forsaken! [^4]
- and its all keyless! completely free!
```luau
 loadstring(game:HttpGet('https://raw.githubusercontent.com/BBro2137/KulkiGUI/refs/heads/main/source'))()
```
> paste this into your executor of choice to load the newest version of kulki gui from the web OR download the latest kulki gui release and then open the .lua file (the obfuscated code) with any text editor (like windows built-in notepad) and paste it into your executor

"you're so done i just got wallhacks" - that one john doe skin and everyone after executing kulki gui



> [!NOTE]
> ## Executor Compability
> if your executor is not on this list or that it wasnt tested for your version it might just not work at all. so dont complain about my script "not working" when its just your executor
> 
>
> [Velocity](https://realvelocity.xyz/) (tested to be working on: v4.x.x)
>
> [Madium (V2)](https://getmadium.net/) (tested to be working on: v4.x.x)
>
> [Real](https://projectreal.gg/) (tested to be working on: version v5.1.0)
>
> [Volt](https://voltbz.net/) (tested to be working on: version v5.1.1)

> [!IMPORTANT]
> the script collects the following data when executed:
> 
> 
> - your forsaken playtime (optional)
> 
> - the server JobID youre in. (optional)
>
> - your executor name and version.
> 
> - if the server youre in is a private server. (optional)
> 
> - your roblox UserID and user name
>
> if the data is marked with "(optional)" then you can go to the script settings and turn off "EXTRA DATA COLLECTING" (it is enabled by default), which will later never collect that data unless the script data is deleted or it is re-enabled.
> 
> this data is **NOT SOLD** it is also **NOT PUBLISHED ANYWHERE**, it is ONLY ACCESSIBLE BY ME (me means MY discord account).
> 
> the data is collected **ONLY** for blacklisting purposes
> 
> your IP or anything that is not on the list is never collected.
> 
> **VERSIONS BEFORE v5.1.2 COLLECT MORE DATA WHICH IS NOT HASHED AND NOT ENCRYPTED** i realized that collecting all of that is shady and not trust worthy

# FAQ
<details>
<summary>the script kicked me and said "Not Safe" what do i do?</summary>
 
> the "not safe" error exists to protect the blacklist and the script. it can be triggered by having another script running that kulki gui thinks is suspicious.

> if rejoining doesnt fix it then its most likely your executor being just not being supported,

> you can also check your auto-execute folder for any scripts and just disable them since they can also trigger this
</details>

<details>
<summary>is this script detected?</summary>
 
> from what ive seen forsaken has a complete lack of client anti-cheat which means its not possible to get detected.

> BUT forsaken does have a server-side anticheat which MIGHT catch you using stuff such as infinite bloxy cola, but the inf cola option does try to hide itself with just lowering the cola speed time.
</details>

<details>
<summary>can i get banned for using this script?</summary>
 
> the short answer is yes.
 
> you can get banned on roblox depending on your executor (you dont need to run kulki gui for roblox to have a chance on finding you, you only need to inject your executor to potentially get detected and banned later)
 
> you can get banned on forsaken if someone records you doing something suspicious such as infinite stamina or most other obvious options, but if you only use ESP & sneaky buffs then you PROBABLY wont get banned by the forsaken mods.
</details>


<details>
<summary>do you use the script yourself?</summary>
 
> i dont, i only update it

> last time i used this script in a public server was mid 2025, i dont need to use this script since im not ass at the game ;D

> but that also means the script has really bad testing before updates :c
</details>

<details>
<summary>why is this script free?</summary>

> because its a passion project, not a source of money

> i did see other free keyless scripts for forsaken and they werent the best so it was crazy to find out that kulki gui is js like that (no glaze)

> the most popular other keyless script that i found was ["forsaken plus"](https://rscripts.net/script/forsaken-plus-invincibleautogen-and-more-ZruY) and it doesnt have many cheats/features compared to kulki gui 
</details>

<details>
<summary>how old is this?</summary>

> the oldest version of kulki gui was created on april 6th, with only survivor and killer esp.
</details>

<details>
<summary>the script says im blacklisted, what do i do?</summary>

> well youre blacklisted which means you did something to/with this script that i didnt like and decided to blacklist you from it

> you are NOT ALLOWED to attempt to bypass the blacklist. if you will attempt though then you will have to face terrible consequences
</details>

<details>
<summary>i found a bug/security vulnerability or have a feature request!</summary>

> feel free to create an "issue" on this repository

> dont create joke issues.
</details>

<details>
<summary>why is the script obfuscated?</summary>

> because i dont want people stealing it.

> and also because the script has a blacklist system, if people could read the source code they would make bypasses way easier which is not cool :c

> i do know that using obfuscation just makes the script performance way way worse but its mostly due to the [obfuscator i use](https://moonveil.cc/) breaking a lot with simple obfuscation, i have to do vm based obfuscations sadly.
</details>

<details>
<summary>does this work on xeno/solara?</summary>
 
> no, because both of them dont support basic functions such as hookfunction() and require() due to them "external executors"
</details>

<details>
<summary>what executors are NOT supported?</summary>

> from what ive tested the broken ones are:
> - xeno
> - solara
> - wave (wave's crypt library is doing some shenanigans idfk)
</details>

## to do
- [x] make the README.md look less ass
- [ ] make the script fully public and publish it onto script sites
- [ ] add more detections to KAC
- [ ] add more "ESPs" to the drawing ESP type
- [ ] remove herobrine

[^1]: as of 28.08.2026 the code editor shows 66 options with 1 of them disabled for maintenance so its a total of 67 (no 67 joke intended.) but a couple of these features are script settings (i wouldnt consider them features) which makes the total around 60.
[^2]: the script supports three UI styles: [Luna](https://docs.nebulasoftworks.xyz/luna), [Starlight](https://docs.nebulasoftworks.xyz/starlight) and "Kulki" (kulki is the original ui from v3.0.0 which i made myself but it looks ass so i added 2 more styles in v5.)  Luna UI is the default style, since its the most compatible one
[^3]: using ai to code is super boring and just bad, if you use ai to code your exec scripts you should visit [this website](https://create.roblox.com/docs/tutorials)
[^4]: the script includes a feature called "Kulki AntiCheat" or "KAC" for short, its very experimental but so far it can guess stamina cheats with low false positives. it still needs to be improved
[^5]: for most of this script's lifespan it has been a fully private script for me and a couple other people, it has only been released to the public on august of 2026.
