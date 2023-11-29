# Server Aliases

<details><summary>Getting Started</summary>

You should run each of these as part of bringing your character to Silverymoon.



`!import <link>` Import your character into Avrae. The link should be from DNDBeyond, GSheets or DiceCloud. Be sure that it's a publically accessible link!

`!setrace` Import a few extra racial traits, features, etc.

`!level` Set up your hitdice for short rests, and your subclass for other alias features. It's worth re-running this each time you level up!

`!getstarted` This will set your character up with those nonstandard touches that allow them to interact with the downtime and roleplaying systems on the server.

-----------
</details>

<details><summary>Setting up in more detail</summary>

`!manage` Add details such as speed, senses, background features, and languages  
<details><summary>More information</summary>

!manage handles a lot of things Avrae doesn't pick up from your sheet. These attributes will show up when you use the !vsheet alias and are checked for in various other aliases. See `!manage help` for more information.
  
Languages: `!manage lang`

Resistances: `!manage res`

Immunities: `!manage imm`

Vulnerabilities: `!manage vuln`

Special Senses: `!manage sen`

Movement Speeds: `!manage speed`

Size Category: `!manage size`

Feats: `!manage feat`

Background Feature: `!manage back`

Condition Immunities: `!manage cond`

Creature Type: `!manage type`

----------------------
</details>

`!tool` Add your tool proficiencies and expertises
<details><summary>More information</summary>

This alias can be used both to add tool proficiencies and to _use_ the tool. 

`!tool all` See all available tools

`!tool pro <tool>` Gain proficiency in a tool

`!tool exp <tool>` Gain expertise in a tool

`!tool <tool>` Use the tool

`!tool <tool> <attribute>` Use the tool with a specific attribute

`!tool help` Receive further information on how to use this alias.

----------------------
</details>

--------------------
</details>

<details><summary>Downtime Activities</summary>

Each day, you can do up to two downtime activities, to represent those things your character does when they're not out being big heroes. You can choose to roleplay this, but it is absolutely not mandatory.

`!dt` Carry out a downtime activity
<details><summary>More information</summary>

  DTs can be completed **2x** daily to gain progress in XP, gold, learning spells or proficiencies with your character's free time in the city, **14** chances in total per week. The daily uses reset at midnight, by default UTC +0. You can change this with `!dt timezone`. Rewards are automatically added to your XP and gold. This resets each week on Sundays with lifestyle costs in ⁠the [weekly logs channel](https://discord.com/channels/866376531995918346/866544281408897024). The DT commands themselves are typed in ⁠the [downtime log channel](https://discord.com/channels/866376531995918346/881218238170665043).

  **Checks** - Each DT has two or three skill check rolls, and various saves. The activity descriptors are contained in each command's help, with their rolled checks. Give them a look through to find what your character may be better at.
Even on fails, players will always be rewarded some amount of gold or XP!
Proficiencies and expertise do give bonuses. Critical rolls (Nat 20) give an extra 1d10 gold or 1d8 XP bonus, too!

**Losing DT** - Some downtimes are more dangerous than others, with a chance at injury which requires 1 downtime for recovery, taking it from your counter. These downtimes offer possibility of more gold to compensate for their danger. You cannot complete these activities when you have less than 2 DTs left. Downtimes that do not involve a save are not susceptible to this.

----------------
</details>


`!week` Pay your weekly lifestyle cost, bank any RPXP you've earnt that week, and reset your downtimes.

-------------
</details>

