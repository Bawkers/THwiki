# Start a Siege

To start a siege as a nation, place a colored banner close to the town you want to siege. You will need 10 gold per plot that the defending town owns and also a General or King rank to initiate the siege. The siege winner will receive this money back. A nation may only have one siege active at a time. Starting a siege will also mean that pvp will be enabled in that town.

### Conquest Siege
A Conquest Siege occurs when a nation attacks an unoccupied town. This happens when a nation wants to expand by conquest. If the attacking nation succeeds, it may capture and plunder the town.

### Liberation Siege
A Liberation Siege occurs when a nation attacks a town occupied by another nation. This happens when a nation wants to free a town from occupation. To begin the siege, you must enemy the nation associated with the town. To do this, do /n enemy add (nation). If the attacking nation succeeds, it may capture and plunder the town.

### Suppression Siege
A Suppression Siege occurs when a nation attacks a town it occupies. This happens if a nation wants to suppress rebel activity in the town. If the attacking nation succeeds, it may plunder the town.


## Occupied Towns
If a nation defeats a town that it does not own, it has an option to occupy the town. An occupied town will contribute to its occupying nation's bonus plots, and it will appear under the occupier's name in `/n list` and color on the Dynmap. If the occupied town is a guardian town, its peaceful towns will be counted as belonging to the occupier. However, an occupied town will remain part of its home nation unless it chooses to join the occupying nation.

### Revolt Siege
A Revlot Siege occurs when a town revolts against its occupier. This happens when a town wants to free itself from occupation. You will not need to prepare gold per the town's plots, but you must still place a banner outside of the town in order to begin the siege. If the defending nation succeeds, it may plunder the town.

## Peaceful Towns
As a mayor, declare your town to be peaceful using '/t toggle peaceful'. The status will be confirmed in 5 days (1 day if the town is new). Once confirmed, the town becomes immune to sieges, taxes, & nationality-spawn-restrictions. PVP is locked off, and it gets a public /t spawn (if it didn't have one already). Nation choice is more restricted: the town can only choose a nation which has a 'guardian town' within 75 chunks. A town qualifies as a guardian town if it has 30 plots or more and is not peaceful. Peaceful Town residents cannot receive nation-military ranks and are afflicted by 'war allergy' if they enter a siege zone.

**NOTE: A nation's capital town can NOT be peaceful. If a town is peaceful and is the capital of a nation, it will be automatically deleted due to the guardian town system at the start of the towny day.**

# Winning a Siege

For the attacking nation to win a siege, the siege score must be positive, and for the defending town to win, the siege score must be negative. Sieges last for 3 days and the timer can be found in `/t` for that town. 

## Battle Sessions
Sieges are broken up into battle sessions. A battle session lasts for 50 minutes and has a 10-minute break period from one session to the next. At 10 minutes past every hour (5:10, 6:10, ...), a new session will begin. Each battle session acts as a 'round' in which players can accumulate battle points. The side with the most battle points at the end of the session adds those points to the siege score.

### Banner Control 
Gaining banner control for your side contributes to battle points. This requires you to have a military rank and can be done by remaining close to the siege banner for 7 minutes. If an enemy is also near the banner, you must clear them out before you can take banner control. Once your side has banner control, 10 siege points will be given every 20 seconds.

### Killing Players
Killing enemies within a 150 block radius of the siege banner contributes 150 battle points. Allies with a military rank can also contribute. All residents in the nation and allies with a military rank can contribute to the score.

### Counterattack Booster
Maintaining banner control can produce many points, but it comes at a cost. Each additional player who takes banner control will increase the points lost upon their death by 10%. A smart enemy will know how to use this to their advantage.

## Abandon Attack
After 24 hours of a siege being initiated, kings or generals can abandon the siege by placing an all-white banner around the siege banner.

## Surrender Town
After 24 hours of a siege being initiated, mayors can surrender the town by placing an all-white banner somewhere in the town.

## Military Ranks
Military ranks are used in siege warfare for those that contribute to sieges. If a player does not have a military rank upon entering the siege zone, they will receive a 'war sickness' effect. The military ranks for towns are guard, sheriff, and mayor. The military ranks for nations are soldier, captain, general, and king. To give a military rank you must be a king or general. Do `/n rank add (name) `

# Post-Siege Events

After the siege is won or lost, the leaders of both sides have some decisions to make. The town of the siege will receive 12 days of immunity from another attack. A town's mayor may request the siege zone be rolled back to its original state.

## Capturing a Town
After the siege is won, a king or general can place a colored banner in the wilderness around the town to add the town to their nation. The mayor of the captured town will stay the same, but the town will be forced to join the attacker's nation.  If the capital of a nation is taken, then the new capital is the largest town in that nation. 

## Plunder
After the siege is won, a king or general can place a chest in the wilderness around the town to plunder 5 gold per chunk, transferring the gold to the plundering nation. If the town does not have enough gold, the town will fall into ruin. 

### Ruins
When a town is deleted or falls, it will enter a ruined state for 72 hours. After 24 hours of the town being in a ruined state, it can be reclaimed using `/t reclaim`. If no one claims it after 72 hours, the town will be deleted. Only the pre-ruin residents can reclaim that particular town. If a resident leaves the town while ruined they cannot rejoin or reclaim it.

**NOTE: You may only gather valuable blocks from a ruined town. Griefing or removing non-valuable blocks is NOT allowed and will result in a punishment. Review what are considered valuable blocks in the rule guide on our website.**

## Nation Refund
As a king, if your nation gets deleted for any reason, including the capture of your last town, you will be refunded (75%) of the initial setup cost. This can be claimed using /n refund. This amount in gold ingots will be sent to your inventory. If your inventory is full, it will be sent to your echest. If your echest is full, it will be dropped to the floor.


# Tips
1. **Fortify towns** - Walls are important. During sieges they help stop enemies from infiltrating towns and killing residents.
2. **Fortify or abandon outposts** - Outposts are important. Towns can be besieged anywhere they have claimed territory.  Make provisions to defend valuable outposts, and abandon the rest.
3. **Assign combat ranks** - Find residents who can be trusted to fight for your town or nation, and assign them military ranks.
4. **Watch your town bank balance** - As a mayor, keep enough money in the bank for sieges. If a town is pillaged or plundered of all its gold by a siege attacker, the town will be destroyed, entering a ruined state for 3 days with all perms enabled. After 1 day it can be reclaimed by any resident, otherwise it will be deleted.
5. **Make friends & allies** - Diplomacy is critical.  As a mayor, diplomacy can be the difference between your town remaining independant, within a friendly nation, or occupied by an expansionistic empire. As a king, diplomacy can be the difference between your nation succeeding, and its annihilation.
6. **Do not remove guards while they are near sieges** - As an under-siege mayor, if one of your guards (online or offline) is near the siege banner, ensure they do not get removed as a battle participant (e.g. deranked). If this happens, a siege-point penalty will be applied.
7. **Do not remove soldiers while they are near sieges** - As an attacking/defending king, if one of your soldiers (online or offline) is near a siege banner, ensure they do not get removed as a battle participant (e.g. deranked). If this happens, a siege-point penalty will be applied.
8. **Make a plan B (Mayor)** - As mayor, defeat in battle is rarely a cause for abandoning your town. Your town may lose a little money due to plunder or be temporarily occupied, but your buildings, items, and townspeople are the same and still need your wise leadership to prosper.
9. **Make a plan B (King)** - As king, defeat in battle is sometimes only a temporary setback. If a town has fallen to the enemy, rally your soldiers to defend your remaining towns. If your capital is about to fall, evacuate to a (new or existing) loyal town and declare it the capital (king will change). 

Thanks to Goosius & LlmDl
