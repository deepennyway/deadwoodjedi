---
title: "Help"
downloads:
    - "/download/DeadwoodJedi Speed Calculator Working v7.xlsx"
---

**What the heck is this "Calculator"?!?**

The Clan Boss Speed Calculator is a tool to help you calculate when your champions are taking their turns in relation to the Clan Boss, what skills they will use, and in general finding the best way to maximize the damage your compositions can do.  Like any tool, however, the Calculator is only as useful as the artisan who wields it. And this tool can be very simple or very complicated, depending on what you want to accomplish, but in either case this calculator follows some very specific rules that you will need to know and accomidate in order to effectively use the calculator. 

{{<ad>}}

## Video Tutorial
{{< youtube "vH9-Ha9bTRo" >}}

## General Guidance
Know that this calculator is close to, but certainly not perfect. It has limitations, especially when trying to use specific Champions, but for most teams it will get the turn order correct, allowing you to speed tune your team for optimal performance. Testing is highly encouraged to ensure the best results.  

To achieve the best results you will need to input a few things for each Champion: their Base Speed, their Total Speed, their number of Speed Sets, whether they have the Lore of Steel Mastery and any Speed Aura the Lead Champion might have.  Each of these can have a profound effect on the results, so it is recommended to be diligent in filling out the calculator. However, for experimentation or hypothesizing, only the Total Speed is really necessary.

The Calculator will give you exact results, but certain masteries, gear, and abilities will prevent those results from being replicated in actuality.  It does not calculate random chance, so masteries like Arcane Celerity, Rapid Response, Cycle of Magic, and Lasting Gifts can all throw off the calculator. The same can be said for gear sets like Relentless and abilities like Golden Reaper's or Rotos' a1 ability that reset cooldowns or grant extra turns based off a percentage chance.

When trying to tune your team for more complex compositions (such as achieving a 4:3 or 3:2 Champion to Clan Boss turn ratios) the speeds of every member matters, not just the champion you want to go faster. So if you are struggling finding the right composition, try adjusting a different champion, not just the fastest one.

The Calculator can also track the skills each champion will use. It is not necessary for turn order purposes, but often very helpful when trying to get certain skills to activate or stay active at specific times. There are some specific rules the Calculator follows which are described in the Advanced Calculator Rules section.

Specific champions that influence speed are options as well. When tuning a team with speed and turn meter buffs please follow the instructions VERY CAREFULLY.  The calculator will use exactly what you input. So if you forget to add a mastery or speed set or input the skills in the wrong order or with the wrong cooldowns, it will not behave correctly! Towards the end of these instructions, in the Speed Champions: How to Use section on how to properly use these Champions, with some specific rule breaking cases for proper tuning.

{{<ad>}}

## A Step-by-Step Guide: How to Use the Calculator
To use the Calculated Speeds, simply follow a couple quick steps:

For a champion that can effect speed, select them from the drop down menus. Make sure to read about how to best use them and avoid errors down below under Advance Calculator Rules and Speed Champions: How to Use

1. Fill in the Total Speed of the Champion.
1. Fill in the Champions Base Speed.
1. Fill in the number of speed sets.
1. Fill in any speed aura.
1. Fill in the cooldowns for that Champions skills.
1. Make sure to fill in all FIVE Champion speeds. 

Those are the basic step-by-step rules. To better tune WHEN the skills are activated, you can fill in the Delay under each skills Cooldown.  This will prevent the skill being used for that amount of turns, after which it will act as normal. 

{{<ad>}}

## Advanced Calculator Rules
There are some general rules the calculator follows to incorporate the wide variety of skills Champions can use:

- Champions will typically use their a4 before their a3 before their a2 before their a1.  Not all Champions follow this pattern, but the calculator will prioritize skills in this order.
- If your Champion prioritizes skills in a different order, input them in order of priority. For example, Arbiter typically prioritizes her a3 over her a4, so you should put her cooldown for the a3 in the a4 slot and vice versa.
- If a Champion doesn't use a skill, leave the cooldown blank. For example, Frozen Banshee only uses her a1 and a3 against the clan boss, so leave her a2 blank.
- For Champions with skills that RELIABLY grant an extra turn, reduce the cooldown of all skills by 1 to simulate that effect. Examples would include Turvold's and Ma'Shalled's a2 and Athel's a3. You would not do this for Arbiter's a4, since it does NOT reliably grant an extra turn.
- Some Champions only activate their abilities if they score a critical hit, for these champions the calculator assumes they will critically hit 100% of the time.
- Do not include passive abilities with cooldowns. The calculator will not work correctly if it is not a selected skill you can reliably choose manually.
- When a Champion is stunned their cooldowns will not tick down. The Calculator does NOT factor this in. If you have a Champion that is dedicated to getting stunned, you can account for it by increasing all their cooldowns by 1. Please understand the stun will throw off the skills used. If it is a Speed Champion that is stunned this will very likely throw off the whole teams turn order.

{{<ad>}}

## Speed Champion: How to Use
What helps make this calculator unique is that it incorporates the unique speed and turn meter boosts specific Champions utilize.  This may prove helpful for those of you using a speed comp or a champion with a buff extender. These are the specific Speed Champions integrated into the Calculator for those of you using a speed comp or a Champion with a buff extender:

Apothecary, Arbiter, Broadmaw, Diabolist, Elder Skarg, Foli, Frostbringer, Galek, Golden Reaper, Gorgorab, Haruspex, Heiress, Hellgazer, Hexia, Hexweaver, High Khatun, Hordin, Juliana, Krisk, Kymar, Lanakis, Longbeard, Lyssandra, Marksman, Ma'Shalled, Maulie, Pitiless, Sandlashed Survivor, Seeker, Sethallia, Shamrock, Shatterbones, Shirimani, Sikara, Siphi, Turvold, Valla, Vrask, Ultimate Galek

Due to the size and peculiarities of this list of Champions, I have not been able to test them all. This part of the Calculator is still a work in progress. Be patient and be diligent when using these Champions. Your feedback with any issues will be of paramount importance.

This list is missing several Speed Champions.  Any Champion with speed and turn meter boosts that are placed randomly, such as Raglin's A1, can't be reasonably accounted for in the Calculator and are thus excluded. That doesn't mean the Champions aren't useful, merely that they aren't included in the Calculator.

In order to best use the Calculator with these Speed Champions, it is important to understand some special unique cases and how the Calculator deals with them. Here is specific guidance for Speed Champions:

-   Marksman's a1 and Lanakis' a3 will occaisonally grant an extra turn, but that same ability will throw off any precise speed composition. Their abilities are still included in the case you care to manual your run.
-    Maulie has a unique ability that activates when hit.  If you place her as the Lead, the calculator will assume she is hit every turn, otherwise it will assume she is hit only on the AOE's.
-    Arbiter's tool tip is inaccurate. Her a3 AND her a4 both grant a 30% turn meter boost contrary to the written information. Arbiter will typically prioritize her a3 skill over her a4, but not always.  To simulate her higher priority, swap the cooldowns of her a3 and a4 skills. Observation will be needed to confirm this in your individual runs.
-    Foli's ability activates when stunned, so if you place him in the lead position it should simulate this. 
-    Several Champions prioritize their a2, so make sure to use that ability in the a3 slot. I believe these Champions include: High Khatun, Turvold, Ma'Shalled, Shamrock and Gogorab. Again I have not confirmed that all these champions behave this way, so make sure to observe and confirm.
-    Haruspex and Siphi only use their a3 to revive allies. I recommend leaving that skill slot blank.
-    Counter-Attack Champions (Skullcrusher, Martyr, Valkyrie) are included for ally abilities involving their a1 skills.
-    Valkyrie's turn meter boost passive is NOT included.
-    Martyr prioritizes her a2 skill (counter-attack) over her a3, so for now leave her a3 skill blank...
-    Longbeard's Ally Attack ability will trigger the a1 skills of allies.
-    Painkeeper requires a LOT of customizing to use: (1) increase the cooldown of ALL of her skills by 1 (2) any Delays for your Champions - ALL of your Champions - will need to be increased by 1 as well. The way it works is Painkeepers a3 will reduce ALL cooldowns by 1 in the calculator. In the game, however, Painkeeper doesn't reduce her own cooldowns.

{{<ad>}}

## Contributors
The calculator is a creation of mine, but heavily influenced and inspired by the work of the r/RaidShadowLegends reddit community, primarily u/NapoleonCamembert and u/Kuroshioizo. NapoleonCamembert and Sinso in particular have been abundantly helpful in fleshing out the calculator. Additionally my clanmate PeanutButter has been huge in helping me get this site up and running. And lastly, thanks to MurderInc for providing sound advice and helping promote the site.

While accurate, this is still a work in progress, not a finished product. There are a LOT of Champions, each with a LOT of abilities, and incorporating them is both tedious and difficult. So if you notice any Champions not behaving correctly, please let me know so I can better improve the calculator.

I hope that you all will continue to help me improve upon it so we can all have a better experience playing a game we all love.  

Click on the button below that says DOWNLOAD FILE if you wish to download the excel version of this calculator. If you make any improvements I simply ask that you share them with me so the calculator can continue to improve.

{{<download>}}

{{<ad>}}