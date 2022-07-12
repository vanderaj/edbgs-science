# Table of contents

**DRAFT** This guide is being actively updated for Odyssey Update 12 with science experiments

![SINC logo](../assets/sinc-logo.png)

- Basic concepts
- Minor factions
- Influence
- Faction states
- Missions and states
- Practical examples
- Further reading

## Basic concepts

- **Background simulation (BGS)**: This is what defines a lot of the stuff you find in the game: Missions, markets, POIs. The BGS ticks once daily. The tick time changes every so often, especially after game updates. With these ticks, influence values and faction states are updated according to actions performed by players.

- **Faction reputation**: Your standing with the faction. The higher your reputation, the better the missions they'll give you. You can increase your reputation by doing missions for that faction, turning in bounties issued by them, trading in the markets they control (including black markets) and selling exploration data in stations they control.

- **System**: Each inhabited system contains one or more assets, each of which can be controlled by a different faction. There are several kinds: Coriolis, Orbis, planetary, etc. One of them, usually the biggest, determines control of the whole system, which means that if a faction controls that asset, they'll control the system.

## Minor factions

Minor factions are political entities within Elite's universe. They control stations and markets, and hand out missions. Each faction has a home system from which they cannot retreat. In most cases the name of the faction includes the name of its home system. Each system can have up to 7 factions, although there are exceptions if FDev god-mods a minor faction into that system or if the system had over 7 factions before they added this cap. Factions are classified by type and government type. Each category has different characteristics; for instance, anarchy factions usually open black markets when they get control of a station, if it didn't have a black market before.

Faction type is a hidden value and determines the conflicts between factions (war or elections), and should not be confused with government type, which is shown in the system map. A conflict between different types will be a war (or civil war), while conflicts between factions with the same type will be elections. The only exception are criminal factions, which never have elections. The types that determine conflicts are the following:



- Criminal: Anarchy
- Corporate
- Authoritarian: Dictatorship, feudal, patronage.
- Social: Communist, confederacy, cooperative, democracy and theocracy.
- Prison colony: Unknown


I've listed the typical associations between faction types and government types for NPC factions, but this isn't always the case. There are a few exceptions, especially player factions or PMFs. For instance, our PMF is a democracy but it has wars with democracies and elections with corporates (so it'd be a corporate democracy). I've heard other PMF have anarchy-like markets, and they sell stuff that is supposed to be illegal in their systems, so if you buy it and a cop scans you right as you leave the station, you'll get a fine. This is sometimes referred to as the Cubeo virus, and it is the result of the government type not matching the typical faction type.


When a faction is aligned with a superpower (Empire, Federation or Alliance), they may have a different name. For example, imperial anarchies are called rebels in the game. If you want to know the type of the faction you're dealing with, your best bet is checking the faction summary in the system map. It always shows the type of faction it actually is there. Doing missions for aligned factions will also increase your standing with that superpower, which will allow you to earn reputation faster for other factions aligned with that superpower. In the case of factions aligned with the Federation or the Empire, doing missions for them will allow you to rank up in their respective navies, which will eventually give you access to certain systems (Sol, Achenar...) and certain ships (Imperial Clipper, Federal Corvette...).



[url=https://youtu.be/YGqndJFKOfA?t=664]From a recent Q&A Livestream with Dav Scott[/url], we know that conflicts between minor factions are determined by hidden parameters, and that they don't have anything to do with government type.

## Influence


Each inhabited system has a total of 100% influence, shared among the factions present in that system. Influence is a key factor in the BGS, and will determine conflicts between factions (more on that later). Each action you perform in a system will have an inherent transaction value (+1, -1, +2...). At each daily tick, these values are added, subtracted and overall used to calculate if and by how much the influence of the faction in the system will change that day. There are several ways to increase or decrease a faction's influence.

To increase a faction's influence, you can:

- Do missions for that faction.
- Trade-in their markets.
- Sell exploration data at stations they control
- Turn in bounties issued by them (doesn't matter if the station is controlled by other faction).
- Do actions that hurt other factions, so that some of the influence they lose bleeds into your faction. Combining this with the other points above is one of the most effective ways to raise your faction's influence quickly.

To decrease a faction's influence, you can:

- Destroy their ships, including system security ships if they're the controlling faction.
- Trade-in black markets they control.
- Do missions for other factions so that they 'steal' influence from your faction. This is most effective if your faction has the highest influence in the system.

The exact value of these transactions has been changed over the years. You can find the current values [url=https://forums.frontier.co.uk/showthread.php/424397-What-is-a-transaction]here[/url]. These values [u]may change[/u] depending on the current state of your faction; you can check exactly how the values change [url=https://forums.frontier.co.uk/showthread.php/424668-States-quot-Best-Current-Thinking-quot]here[/url]. If you're not familiar with faction states, I recommend you read section 4 of this guide. As for missions, you can very easily check the exact number of +'s the provide for your faction, as from 3.0 onwards it is listed in the rewards list. VIP sightseeing missions can go as high as 5+!

The amount of influence a faction can gain or lose every tick depends on the population of the system. As a general rule, the higher the population, the harder it is to gain or lose influence. If you want to learn more, check [url=https://forums.frontier.co.uk/showthread.php/423837-Influence-caps-gains-and-the-wine-analogy]this[/url].

You can check every faction's influence, along with its type and current state, in the system map:

[img]http://i.imgur.com/DbbB04t.png[/img]

## Faction states

Due to different actions performed by players, states may go pending and eventually trigger. Each state has a countdown in days or ticks (during which it shows as a pending state), and a cool down before it can happen again (during which it shows under 'recovering states'). States can have different effects on the faction. States affect the faction in all the systems it's in, even if it just shows up in one system.

 There are 3 types of states: Economical, which only involves one faction, conflicts, which involve 2 factions, and other (expansion, retreat and investment).

**Economical**: Each economical state has its own 'bucket', which is filled by specific player actions. When an economical state triggers, the other buckets are emptied except the outbreak and famine buckets, which are halved. The buckets are faction-wide, i.e. there isn't a bucket for each system, they all share the same bucket.

## Boom**: Easily triggered by trading in their markets or doing missions that contribute to boom, such as haulage missions, data courier missions, tourist/business people transport missions, etc.

- For the duration, the effect of trading (and haulage missions) on influence is doubled, including the negative effect of smuggling.
- Countdown: 2 days
- Min/Max duration: 3/28 days
- Cooldown: 2 days

## Bust**: Triggered by smuggling in black markets.

- For the duration, trade actions do not contribute to influence.
- Can be shortened by trading actions.
- Countdown: 2 days
- Min/Max duration: 3/28 days
- Cooldown: 2 days

## Civil unrest**: Triggered by trading or smuggling weapons, performing crimes in systems the faction controls or destroying the ships of the faction.

- For the duration, combat actions have double the effect (this also means killing the faction's ships has double the effect)
- Can be shortened by performing combat actions.
- Countdown:  1 day
- Min/Max duration: 3/7 days
- Cooldown: 3 days

## Lockdown**: One of the most damaging states. Can be triggered by killing the faction's ships, especially system authority vessels.

- You can increase your influence by selling bounty vouchers issued by your faction.
- Services in stations the faction controls are closed, including, but not limited to, mission board, market and outfitting ([url=http://imgur.com/a/eqodO]example[/url]).
- Can be shortened by bounty hunting.
- Countdown: 1 day
- Min/Max length: 3/14 days
- Cooldown: 1 day

## Famine**: Nobody's sure what triggers this state. It appears that a lack of player activity could be a factor.

- For the duration, combat actions have no effect, food trading (and missions that involve these commodities) have double effect on influence, and food has higher prices in the market.
- Can be shortened by trading food.
- Countdown: 3 days
- Min/Max length: 3/28 days
- Cooldown: 25 days

## Outbreak**: As with famine, no one's sure what triggers it, although some have hypothesized waste trading may trigger it, since biowaste hauling missions fill the outbreak bucket for the target faction.

- For the duration, combat actions have no effect, medicine trading (and missions that involve these commodities) have double effect on influence, and medicines have higher prices in the market.
- Can be shortened by trading medicines.
- Countdown: 4 days
- Min/Max length: 3/28 days
- Cooldown: 7 days

Here's a spreadsheet with the effect of player actions on different buckets, according to [url=https://youtu.be/y5DGyG6Qwvk?t=1843]a live stream from some time ago:

| Action | Boom | Bust | Civil Unrest | Lockdown | Famine | Outbreak | Influence |
| Trade | Up | Down |
 |  |
 |  |
 |  |
 |  |
 | Up |
|
|
 | Trade food |
 | Up |
 | Down |
 |  |
 |  |
 | Down |
 |  |
 | Up |
|
|
 | Trade medicines |
 | Up |
 | Down |
 |  |
 |  |
 |  |
 | Down |
 | Up |
|
|
 | Trade weapons |
 | Up |
 | Down |
 | Up |
 |  |
 |  |
 |  |
 | Up |
|
|
 | Smuggle |
 | Down |
 | Up |
 |  |
 |  |
 |  |
 |  |
 | Down |
|
|
 | Smuggle food |
 | Down |
 | Up |
 |  |
 |  |
 | Down |
 |  |
 | Down |
|
|
 | Smuggle medicines |
 | Down |
 | Up |
 |  |
 |  |
 |  |
 | Down |
 | Down |
|
|
 | Smuggle weapons |
 | Down |
 | Up |
 | Up |
 |  |
 |  |
 |  |
 | Down |
|
|
 | Redeem bounties |
 |  |
 |  |
 | Down |
 | down |
 |  |
 |  |
 | Up |
|
|
 | Redeem combat bonds |
 |  |
 |  |
 | Down |
 |  |
 |  |
 |  |
 | Up |
|
|
 | Sell exploration data |
 | Up |
 | Down |
 |  |
 |  |
 | Down |
 | Down |
 | Up |
|
|
 | Murder |
 |  |
 |  |
 | Up |
 | Up |
 |  |
 |  |
 | Down |
|
|
 | Other crimes |
 |  |
 |  |
 | Up |
 | Up |
 |  |
 |  |
 | Down |
|
[/table]

**Conflicts**: These states are unique in that they involve 2 factions. To trigger a conflict, you must match the influences of the factions. Alternatively, you can raise your faction's influence above 60% to trigger a conflict with the controlling faction ( a *coup d'état*, so to speak). A faction can only have one conflict at a time, including pending states, so you can't have a pending war in system X if you're having elections right now in system Y. When the conflict starts, the influence the factions have is 'locked', and they can only interchange influence with themselves. **However, it has been reported since a few patches ago that influences are not locked anymore, might be a bug**. One of the factions must have at least 7% influence for the conflict to trigger. This rule prevents low influence factions from being locked in perma-wars. A conflict can't be interrupted by triggering other states. Instead, the other states will be delayed.

The special rules for the effect of actions on influence are applied faction-wide, not just to the system where the conflict is taking place. Conflicts can interrupt economic, expansion and retreat states. This means that you can interrupt a lockdown by triggering a war for example. When a victor is declared, they gain control of the most valuable asset the loser controls. Once the asset transfer has happened, there is no way to undo that in the same conflict. You must wait until it ends next tick (some people call this day after asset transfer a 'dead day', since it serves no purpose whatsoever) and trigger another conflict.

A typical conflict will follow the following path, assuming the gap is wide enough on day 7:

Day 1: Conflict goes pending.
Day 2
Day 3
Day 4: Conflict starts.
Day 5
Day 6
Day 7: Asset transfer happens.
Day 8: Conflict ends.

## Elections**: Triggered between factions with the same ideologies (check section 2 for more information): democracies with democracies, corporates with corporates, dictatorships with dictatorships (yes you read that right, dictatorships can have elections). The exception is anarchy factions. They will always go to war/civil war, even with other anarchies.

- The gap needed to declare a victor is 3%
- For the duration, combat actions have no effect on influence for both factions. The best way to win is doing missions for your faction or trading in their markets.
- Countdown: 3 days
- Min/Max duration: 4/5 days
- Cooldown: 2 days

## Civil war**: Triggered between 2 factions that don't have the same type of government but have the same home system.

- The gap needed to declare a victor is 3%
- Conflict zones will spawn around bodies in the system. You can help your faction by going there, siding with them and killing enemy ships. You will receive combat bonds for each kill, which you can turn in at any station of the system to increase your faction's influence.
- For the duration, only combat actions contribute to influence.
- If the war reaches its max duration but the gap is not wide enough to declare a victor, the war will be halted, and the conflict zones will be in cease fire. The civil war will end and a new war will go pending shortly after.
- Countdown: 3 days
- Min/Max duration: 4/28 days
- Cooldown: 0 days

## War**: Triggered between 2 factions that share neither the same political ideologies nor have the same home system.

- Like civil wars, except the gap needed is 5% instead of 3%.

**Other**: These states don't have buckets and only involve one faction.

### Expansion

When a faction reaches 75% or more in a system, it will get a pending expansion if it has no active or pending conflicts. This is an opportunity for the faction to expand into other systems. After a 5-day countdown, the expansion will trigger. It will interrupt a boom state if it is active (I'm not sure about the other economical states). All activities contribute to influence for the duration. The cost or 'tax' of this state is 15% influence in the system the faction is expanding from, which will be drained slowly with each tick. You can prevent this by doing missions for your faction or ending the expansion early by triggering a conflict. Expansions will end boom state early if there's one active.

- The system the faction will expand to will be the closest system with 6 or fewer factions.
- The maximum range appears to be 25-30 lys. I have personally seen our faction trigger an investment (I'll get there in a sec) and then expand to a system 25.5 ly away.
- Countdown: 5 days
- Min/Max length: 3/7 days, will typically run for 5 days from my experience.
- Cooldown: 2 days

## Investment**: If there is no suitable system within range of a regular expansion, it will fail after its duration and the faction will start an investment state. It lasts for 5 days and does not prevent conflicts (it's the only case in which a faction can have 2 active states at once). Once the investment ends it will be on recovery for a day, and then an expansion will go pending. Once it triggers, this expansion will have an enhanced range, although the max range is not clear yet. The expansion won't necessarily trigger from the system the investment was active.

## Retreat**: If a faction expanded to a system but their influence there stays at 2.5% or lower for too long, a retreat may trigger. If the influence of the faction is below 2.5% when the retreat ends, the faction will be forced out of the system. A faction cannot be forced to retreat from their home system, or if there are 3 or fewer factions in the system, except if there are for instance 5 factions and 3 of them get a pending retreat at the same time. We've successfully reduced the number of factions in a system to 2 this way. Retreat will end boom state early if there's one active.

- Countdown: 1 day
- Min/Max duration: Unknown/5 days
- Cooldown: Unknown

You can check where your faction expanded to and the recent states the factions have gone through by checking the news board of the station. You can also check the pending, current and recovering states for every faction in the system if you dock at a station and check the **Faction Status Summary**, added in 2.2:

![Station News](station-news.png)


[img]http://i.imgur.com/Id5kJnj.png[/img]

Here's an spreadsheet with just numbers:


[table]
|

Countdown
Min length
Max length
Cooldown
|
|
 | Expansion |
 | 5 |
 | 3 |
 | 5 |
 | 2 |
|
|
 | War |
 | 3 |
 | 4 |
 | 28 |
 | 0 |
|
|
 | Civil war |
 | 3 |
 | 4 |
 | 28 |
 | 0 |
|
|
 | Election |
 | 3 |
 | 4 |
 | 5 |
 | 2 |
|
|
 | Boom |
 | 2 |
 | 3 |
 | 28 |
 | 3 |
|
|
 | Bust |
 | 2 |
 | 3 |
 | 28 |
 | 3 |
|
|
 | Civil unrest |
 | 1 |
 | 3 |
 | 7 |
 | 3 |
|
|
 | Famine |
 | 3 |
 | 3 |
 | 28 |
 | 25 |
|
|
 | Outbreak |
 | 4 |
 | 3 |
 | 28 |
 | 7 |
|
|
 | Lockdown |
 | 1 |
 | 3 |
 | 14 |
 | 1 |
|
|
 | Investment |
 | 0 |
 | 5? |
 | 5? |
 | 0 |
|
|
 | Retreat |
 | 1 |
 | ? |
 | 5 |
 | ? |
|
[/table]


--


## 5. Missions


Missions always have a positive effect on the source faction (the faction that gave you the mission), usually an increase in influence and a positive effect on a state (filling the bucket of a good state, like boom, or emptying the bucket of a bad state, like lockdown). However, 2.2 reintroduced target factions for missions. The effect of missions on the target faction is't always positive. If the target faction is the same as the source faction, no negative effects are applied. Each kind of mission has a different effect on states. Since 3.0, regular missions will also affect the influence of the target faction. Whether this effect is positive or negative depends on the type of mission, this has yet to be throughly tested.

Missions will offer three of several reward types:

- Get the full rewards as credits.
- Get a part of the reward as cargo (for instance, nano breakers)
- Get a part of the reward as materials (for instance, biotech conductors), at the cost of reducing the credit reward.
- Get extra reputation, at the cost of reducing the credit reward.
- Get extra influence, at the cost of reducing the credit reward.

[img]https://i.imgur.com/IjctIhD.png[/img]

If you're trying to get your faction to gain influence, I recommend you pick the extra influence reward whenever possible.

- **Delivery missions**: Increases  boom for both factions and influence for source faction.. The exceptions are:
- *Biowaste delivery*: Will increase outbreak for the target faction and decrease outbreak for the source faction.
- *Food/Medicine delivery*: Will decrease famine/outbreak for the target faction respectively.
- *Weapon delivery*: Will decrease lockdown for the source faction and civil unrest for the target faction.
- *Drugs*: Will decrease bust for source and increase bust for target faction.

- **Smuggle missions**: Increases bust for target faction, decreases bust and increases influence for source faction. The exceptions are:
- *Weapons smuggle*: Increases lockdown for target and decreases lockdown for source instead of bust.
- *Slaves*: Increases civil unrest for target faction and reduces unrest for source faction.
- *Medicines/Food:* Increases boom and influence for source and decreases outbreak/famine for target.
- *Drugs*: Decreases bust for source and increases bust for target.

- **Data courier missions**: Increases boom for both and influence for the source faction.

- **Massacre missions**: Increases influence for source faction while reducing it for target faction. Different kind of targets affect different states:
- *Conflict zone ships*: Decreases lockdown for source, increases lockdown for target. This is a reliable way to trigger a lockdown if enough massacre missions spawn.
- *Skimmers*: Increases influence and decreases lockdown for source, increases famine for target.
- *Goliath*: Increases influence and decreases lockdown for source, increases lockdown for target.
- *Pirates*: Increases influence for source faction and increases boom for both source and target factions.
- *Other targets*: Unknown

- **Fetch/Donation missions**: These don't have a target faction, as you're delivering the goods to the same faction.
- *Money/Regular commodities*: Increases boom, except when the faction is famine, unrest, bust or outbreak. In this case it counteracts the negative state instead of increasing boom.
- *Food*: Decreases famine.
- *Drugs*: Increases boom if donation, decreases unrest if fetch.
- *Medicines*: Decreases outbreak.
- *Weapons*: Decreases civil unrest.

- **Extraction missions**: Increases influence and boom.

- **Salvage missions**: Increases influence. If it's a space salvage mission, increases boom. If it's a planetary salvage mission, decreases unrest.

- **Planetary scan missions**: Increases influence, decreases lockdown.

- **Surface attack**:
- *Destroy generator*: Increases boom and influence for source, increases unrest for target.
- *Hack*: Increases influence and decreases lockdown for source, increases lockdown for target.


- **Passenger missions**: There are lots. Here's the effects we've gathered so far:

[table]
|
Passenger type
Effect on source faction
Effect on target faction
|
|
 | Aid worker |
 | +Inf, -Civil Unrest |
 | +Inf, -Famine |
|
|
 | Business |
 | +Inf, +Boom |
 | +Inf, +Boom |
|
|
 | Medical |
 | +Inf, +Boom |
 | +Inf, -Outbreak |
|
|
 | Political prisoner |
 | +Inf, -Lockdown |
 | +Inf, -Lockdown |
|
|
 | Politician |
 | +Inf |
 | +Inf, -Civil unrest |
|
|
 | Prisoner |
 | +Inf, -Civil Unrest |
 | +Inf, +Civil unrest |
|
|
 | Protester |
 | +Inf, -Civil unrest |
 | -Inf, +Civil unrest |
|
|
 | Rebel |
 | +Inf, -Lockdown |
 | -Inf, +Lockdown |
|
|
 | Refugee |
 | +Inf, -Bust |
 | +Inf, +Civil Unrest |
|
|
 | Scientist |
 | +Inf, -Famine |
 | +Inf, -Famine |
|
|
 | Security |
 | +Inf |
 | +Inf, -Lockdown |
|
|
 | Tourist |
 | +Inf, +Boom |
 | +Inf, +Boom |
|
|
 | Rebel |
 | +Inf, -Lockdown |
 | -Inf, +Lockdown |
|
|
 | Deliver VIP explorer |
 | +Inf, +Boom |
 | +Inf, +Boom |
|
|
 | Deliver VIP general |
 | +Inf, -Lockdown |
 | +Inf, -Lockdown |
|
|
 | Deliver VIP head of state |
 | +Inf, -Civil Unrest |
 | +Inf, -Civil unrest |
|
|
 | Deliver VIP rebel |
 | +Inf, -Lockdown |
 | +Inf, -Lockdown |
|
|
 | Deliver VIP tourist |
 | +Inf, -Civil unrest |
 | +Inf, -Civil unrest |
|
|
 | Sightseeing criminal |
 | +Inf, -Bust |
 | * |
|
|
 | Sightseeing general |
 | +Inf, -Lockdown |
 | * |
|
|
 | Sightseeing rebel |
 | +Inf, -Civil Unrest |
 | * |
|
|
 | Sightseeing tourist |
 | +Inf, +Boom |
 | * |
|
[/table]

- Since you have to bring your passengers back to the same station (and to the same faction) in sightseeing missions, there is no target faction for these missions.

A lot of these missions are dependent on faction states. For instance, haulage missions are much more common during a boom. If a faction is in outbreak, missions to transport medics and medicines will pop up in the nearby systems, and that faction will have a lot of source/donation missions asking for medicines.

## NOTE**: I've recently updated the mission section with information from [url=https://cdb.sotl.org.uk/missions]this[/url] page. If you want to see a more complete spreadsheet about missions, check it out! I may end up adding that whole spreadsheet into this guide, but it would take a while as making tables in this forum's code is a bit of a lengthy process.


--


## 6. Practical examples


In this section I present some real-life scenarios, and the strategy I would follow.


Example 1

[img]http://i.imgur.com/IhxJB2r.png[/img]

Let's imagine there's only 1 asset in this system, and Sirius Hyperspace controls it. Your faction is Ngalia Flag. You'd normally have to fight Yuracani Independent Combine on your way up (and you'd get no asset for winning that conflict). However, since it's currently in civil war with Yuracani Crimson Combine, you can bypass them and aim straight for the controlling faction. Remember, factions can only have one conflict-active or pending at any given time.



Example 2

[img]http://i.imgur.com/2e7P3mL.png[/img]

Your faction, Liberty Party of GD 219, just expanded to this nice system. It turns out the factions above you all control some valuable asset. In this case, your best option would be to slowly increase your influence to trigger conflicts with all the factions above you, and grab as many assets as you can before challenging the controlling faction.


---


## 7. Further reading


This guide does not cover everything, despite its size. I encourage you to check these links if you want to learn more about the BGS:

- [url=https://forums.frontier.co.uk/forumdisplay.php/240-The-BGS]BGS subforum in the official Elite forums[/url]

- [url=https://forums.frontier.co.uk/showthread.php/400110-Don-t-Panic-BGS-guides-and-help]More BGS guides.[/url]

# References

<!---
Comments look like this and do not show up in the PDF

References are cited as @mittner2014brain or [@mittner2014brain].

-->
