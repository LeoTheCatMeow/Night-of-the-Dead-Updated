# Current Changes & Bugfixes Tracklist

2021-2-18
[ThunderRazor]
- Fixed recruit/normal Elite Mutation wins not displaying correctly.
- Enabled win update/rewards for solo players and lowered the requirement for Medal of Honor to at least 2 players instead of 3.
- Added a "Glass Cannon" option for solo and duo players, taking and dealing extra damage.
- Improved zombie AI to better handle situations when there are large number of enemies on the map.

[LeoTheCat]
- Moved the unlock text on mission select to the left so that chat is easier to read.
- Fixed a bug where multiple X1 Bots and Reaper Drones can be made.
- Fixed unreadable texts and broken hotkeys for languages other than English.
- For now, French will use English texts, Traditional Chinese and Simplified Chinese will have a mix

2021-2-13
[ThunderRazor]
- Added win tracking for Elite Mutation and Outbreak mode.

[LeoTheCat]
<Class Balancing>
- Marksman - Shadowstep energy cost reduced from 20 to 15.
- Recon - Laser Designator no longer grants -armor, it instead grants 5%/10%/15% increased ranged attack speed to the designated target.
- Recon - Laser Designator reveal radius improved from 2 to 2/3/4, energy cost increased from 5 to 8.
- Recon - Motion Sensor no longer reduces enemy armor, now provides a global +1.5/+3 vison and detection buff to the team (Does not stack).
- Recon - Renamed Motion Sensor to Battlefield Radar to better reflect its current effect on the team.
- Engineer - X1 Guardian regular weapon damage improved from 12/18/24 to 18/25/32.
- Engineer's X1 Bot and Recon's Reaper Drone are now Heroic - and thus receive xp shared from the team (7 radius).
- Additionally, X1 Bot and Reaper Drone no longer take full xp from their own kills, those are instead evenly split among nearby teammates.
- Engineer - Adjusted the level progression of the X1 Bot so that it is initially easier to level up, but harder at later levels.
- Forward Observer - Slightly increased Airstrike friendy fire radius (from 1.5 to 2) so that it is not completely idiot proof.

<Gameplay Changes>
- Increased the push priority on Guardian of the Beta so he can't be body blocked.
- Hades now has a 50% chance to kill each mind controlled zombie when the fight starts instead of always killing all zombies.
- Due to X1 Bot becoming Heroic, the "Summoned" attribute has been added to most player-made units and mind controlled units.
- Sync Module now looks for units with the "Summoned" attribute for the 18% damage bonus.

<Qol Changes>
- Added more coloring for Monstrous and Atrocious Elite Mutation so it is easier to tell them from regular zombies.
- Forward Observer's shell count display now properly updates for other players too.
- Added tooltips that reflect weapon mod's influence on splash and reload. (Does not yet reflect talent or passive ability influences).
- Concentrated Fire and Focus Fire cooldowns are made to match their buff durations to avoid any confusion.
- Erebos Cinematic will no longer play for normal/nightmare games.
- Engineer's X1 Bot will now properly grow in size when upgraded.
- Replaced Engineer's Reinforce icon with a colored one that differs from Sync Module's icon.
- Replaced the CP icon with a direct number display just like the shield armor one, making the vertical behavior bar less crowded. 
 
<Bugfixes>
- Fixed a bug where Forward Observer's Airstrike is doing more damage than what the tooltip states.
- Fixed a bug where Recon's self cloak may be deactivated due to delayed damage.
- Fixed Turbo auto-cast not working properly.
- Fixed pet backstab not working.
- Fixed price tooltips on CI Ammo and Sync Module.

2021-2-10
[ThunderRazor]
- Made some number adjustments to Class Traits (for early class unlock).

[ReduxGelum]
 - Added oubreak and elite mutation victory bonus xp and credits.

[LeoTheCat]
- Updated translations of most core gameplay elements (items, talents) for Traditional Chinese.
- Flamethrower - Smite damage against Heroic increased from 1.8%/3.6%/5.4% to 4%/8%/12%.
- Flamethrower - Smite damage against real Bosses increased from 1.8%/3.6%/5.4% to 2%/4%/6%.
- Flamethrower - Smite damage is no longer affected by bonus damage dealt (such as Penance, Frenzy, HP ammo etc).
- Flamethrower - Smite damage is still affected by bonus damage taken (such as Heightened Senses, VRL-777 etc).
  (Note: This would make smite consistent with other % HP based effects in game, namely OSOK's % HP damage.)
- Flamethrower - Frenzy attack speed bonus improved from 1%/2% a stack to 2%/4% a stack, matching the damage bonus.
- Flamethrower - Inferno initial 50 damage over time removed, explosion delay reduced to 3s. now always grants frenzy stacks.
- Flamethrower - Fixed a bug where Inferno is doing way more damage than the tooltip suggests (the damage is registering multiple times).
- Flamethrower - Updated Helium Igniter Lv3's tooltip to clarify the bonus damage over time effect.
- Rifleman - Saline IV cooldown adjusted from 15/13/11 to 17/16/15.
- Forward Observer - Napalm Barrage now does grant XP normally. Slow reduced from 30% to 10% (can still stack up to 5 times).
- Fixed a tooltip error regarding Foward Observer's Mobile Infantry: Each infantry DOES NOT reduce FO's energy regeneration.
- Forward Observer - Slow Roast now grants +5 armor and +3 life regeneration, duration/cooldown increased to 30, cost increased to 35.
- Forward Observer - Veteran's Focus damage bonus increased from 15% to 30%.
- Forward Observer - Shockwave Barrage now also makes targets 15%/30% more vulnerable to damage.
- Forward Observer - Airstrike now launches 36 missiles that lock onto enemies with less friendly fire potential. Damage reduced to 60/120.
- Forward Observer - Lunar Technologies (passive) Level 2 changed from double airstrike to reduced airstrike cooldown and energy cost. 
- Forward Observer - Level 3 Fire Mission is now considered explosive and may be amplified by fire vulnerability effects.
- Fixed a bug causing Forward Observer to get Open Wound more easily. 
- Fixed idle Ghouls spawned from EC start.
- Fixed some errors with death messages, added some new death messages.
- Fixed Marksman Model having the wrong texture after swaping back from a skin change.
- Nazara clones in Elite Mutation will no longer have mutations.
- Added back the shield armor tooltip (now it is located to the right of the weapon damage UI).

2021-2-6
[ReduxGelum]
 - Added critter wander leash behavior to agrons guarding EC worms to prevent enemies getting stuck.

[LeoTheCat]
- Flamethrower - BURN! no longer reduces armor, now generates Frenzy during channel, faster at Level 2, energy cost increased from 10 to 15.
- Flamethrower - Inferno damage improved from 150 to 150 + 40% vs Armored. Cost reduced from 30 to 25. Cooldown increased from 15 to 25.
- Flamethrower - Inferno no longer grants 10 Frenzy on cast, Inferno kill Frenzy chance improved from 30% to 40%.
- Fixed a bug on Flamethrower's Inferno where it is not generating the correct amount of Frenzy.
- Lowered CP decay rate from 15% to 10%, allowing an average 0.3 gain in pubs and 1.3 gain in nightmare.
- CP gain or losses are now prevented in Normal mode too if the player randomed (since not all pub games are recruit these days).
- Flamthrower's Vengeance and Pet's Cloak Field can now be toggled.
- Added the improved limit system for Crawler Drones, Field Probes, Disruption Towers, and Sonic Traps (1 gets destroyed instead of all). 
- Replaced the faith animation with a new one (the current one looks too similar to an explosion).
- Added a cursor indicator for Pathfinder's No Quarter.
- Shortened the wait time between wave 10-11 in Survival Mode from 300 seconds to 200 seconds (real time).
- Technician - March of the Machine attack interference interval increased from 1.5s to 3s (less interference).
- Technician - March of the Machine attack interference will no longer happen if the weapon cannot friendly fire.
- Technician - March of the Machine move speed penalty removed.
- Technician - Ballistics damage bonus improved from 12%/24% to 18%/36%.
- Technician - Crawler Drone move speed improved from 2 to 2.25, matching Technician's base speed.
- Technician - Maintenance Drone Plasma Cutter damage improved from 150/200/250 to 200/250/300, now allowed to target structures.
- Technician - Maintenance Drone Plasma Cutter now allows movement during casting and can be used via smart command (right click).
- Technician - Maintenance Drone Field Retrofit now allows movement during casting and can be used via smart command (right click).
- Psi Ops - Mind Ravage replaced by Psionic Tempest, with stats lowered to fit as a T1 ability. 
- Psi Ops - Foresight now also amplifies spell damage taken in addition to the slow.
- Psi Ops - Psionic Tempest T3 has been reworked into Absolution, offering a barrier for the team and empowers Psi Ops for 15 seconds.
- Commando - Bring Them Down slow improved from 15%/25%/35% to 15%/30%/45%, radius improved from 1.5 to 2 + target unit radius.
- Commando - Monofilament Trap damage increased from 50/100 to 75/150, ally damage unchanged.
- Commando - Monofilament Trap energy cost at level 2 reduced from 25 to 15.
- Commando - The Horror cost and cooldown slightly reduced. Now deals % HP damage over time, reduced against Heroic.
- Units that manage to survive The Horror will be driven mad. Enemy Heroics are unaffected.
- Fixed some minor tooltip and visual effect errors.
- Enemies with Elite Mutation now reward double XP to the killer, does not affect shared XP due to current design limitations.
- Fixed an bug with Combat Engineer where Boom! Headshot affects Disruption Towers.
- Engineer - X1 Guardian Bot Targeting Computer can now be auto-cast, energy cost reduced from 10 to 5.
- Engineer - X1 Guardian Bot move speed increased from 2.2 to 2.42, matching Engineer's base speed.
- Engineer - X1 Guardian Bot damage increase per level improved from 5% to 10%.
- Engineer - Improved the timing window on Synergy so that it may proc more consistenty.
- Forward Observer - Base shield increased from 20 to 25.

2021-1-28
[ReduxGelum]
- Changed faith effect model to differentiate from smite.
- Enabled transient for faith ability.

[LeoTheCat]
- Reworked Demo's Spider Mine into Sentinel Mine (Widow Mine). Can fire missiles up to 7 times when deployed, max 7 on the battelfield.
- Renamed Make Mines to Make Explosives. It is now an innate ability that is learned when leveling up Sentinel Mine.
- Demo's explosive abilities consume charges from Make Explosives.
- Replaced Make Mines with a new passive talent - Explosive Aftershock, allowing Demo to specialize against large enemy clusters.
- When exceeding the number limit, Sentinel Mine/Armageddon will no longer all get destroyed. Instead the farthest one will be destroyed.
- Demo's Satchel now activates within 3 seconds instead of 5 seconds.
- Demo's Armageddon tremors now mini stuns instead of slows.
- Rifleman - Saline IV now also affects 1 other most wounded ally marine in 3 radius.
- Simplified Forward Observer's Fire Mission damage to 50/75/100 + 50% vs Massive.
- Simplified Forward Observer's Napalm Barrage damage to 40 + 50% Massive.
- Units stunned by Forward Observer's Shockwave Barrage will have the stun visual effect properly displayed.
- Forward Observer's Artillery tree now starts with 1700 shells in Nightmare mode but 1500 in easier modes.
- Forward Observer's rifleman minis have their stimpack replaced by Level 2 Saline IV, with a much longer cooldown and higher energy cost.
- Forward Observer's marksman minis can now cast Veteran's Focus on other bio units. Duration and energy cost increased.
- Lowered Strangler's base health from 125 to 120 (so that shatter can one shot them at 250% hp scaling).
- Improved the splash of UA420 Assault Rifle from 0.75 to 1.25.
- Pathfinder - Assault Jump initial cooldown reduced from 30 to 25, No Quarter center hit now also rewards 1 Assault Jump Charge.
- Pathfinder - Coming in Hot's DOT improved to 16/32 DPS for 10 seconds, 2x against Heroic. Max 5 stacks.
- Pathfinder - No Quarter cooldown reduced from 45 to 30, energy cost reduced from 35 to 25, invulnerability duration increased from 4 to 5.
- Pathfinder - Shoot To Maim energy cost per shot removed.
- Agrons that guard nydus worms in EC are now spawned right next to the worms, making them less likely to block off zombies.
- Players now have more time to rescue the civillians in EC before too many of them get infected.

2021-1-23
[ReduxGelum]
- Overall enemy pathing optimization - preventing units from getting stuck and causing lag.
- As a result certain exploit spots are no longer effective.
- Fixed cronus initial beam effect invisible on low graphics settings.
- Fixed texture set after 6 years (finally!).

[LeoTheCat]
- Fixed the inner radius of Eos and some other enemies so that they don't get stuck. This radius does not affect Flamethrower MK-3 dps.
- Storyline selection UI will now reflect lobby options for consistency (e.g. High Spawn should be highlighted if lobby option is set so).
- Realism command has been removed as pretty much all controversial changes have been reverted to the original.
- Engineer - Plasma Discharge damage increased from 20/40/80 to 30/60/90 (level1 zombie has 87.5hp at 250% scaling).
- Fixed some Engineer tooltip errors in the behavior bar.
- Tried to improve behavior bar's performance.
- Chem Expert - VRL-772 now cures all ailments instead of just some.
- Marksman - Monofilament Cartridge damage increased from 40/80/160 to 45/90/180. (level2 zombie has 175hp at 250% scaling).
- Marksman - One Shot, One Kill lv1/lv2 damage increased from 200/400 to 400/600.
- Marksman - Master Marksman passive reworked, still upgrades One Shot, One Kill but no longer stuns. Has a more unique effect instead. 
- Moved CP Bonus out of the behavior bar and added the stack count to its tooltip (still visible in the default sc2 behavior bar).
- Flamethrower - Helium-3 Igniter lv3 now also allows Flamethrower MK-3 to target air.
- Added a placement indicator for Recon's Supply Station.
- LD effect will now remain after Nazara splits.
- Reduced the intensity of Recon's upgraded flares.
- Fixed Surv wave 37 enemies dying before reaching players.

2021-1-18
[ThunderRazor]
- Added a merit system that lets players rate each other with merit and demerit points.
- Merits/demerits shall only be rewarded based on behavior and not skill (it is a peer to peer rating system).
- Every player can nomimate up to 10 merits and 5 demerits. (The most recent 10 or 5 will be kept and older ones discarded.)
- The player with the most merits (3 or more) will be awarded +5 karma at victory in the next game, if kept clean.
- Applying karmabite automatically demerits the griefing player, and demeriting a griefer automatically applies karmabite.
- 3 or more demerits locks out the griefer from being able to use shop, control leaver, and select advanced classes except in Survival.
- Merits can be used to vouch for demerited players (requires 2 merits to cancel 1 demerit).
- Click on player portrait to show the demerits dialog.
- Clck any UI button to hide the dialog (most UI buttons will work).
- Added option to permanently hide the dialog (check box in top right of screen).
- Optimized the random sequence of EC domes

[LeoTheCat]
- Removed the shield overcharge feature on Engineer's repair. (Therefore Energy Battery no longer improves the shield overcharge as well). 
- Energy Battery still improves repair speed, but now also grants 10/20 max energy increase to all allies that can use energy in the aura.
- Added a button for Engineer to remotely self-destruct Disruption Towers.
- Removed the % damage reduction system due to its performance issue and complex nature, all armor mechanics reverted back to OG.
- Preiously adjusted tank talents, including Demo's I'm Your Father and Assault's Safeguard reverted to their original numbers.
- As a side effect of the removal of this system, shield armor tooltip is currently unavailable.
- 590A5 Combat Shotgun damage vs Massive has been reverted to 70 from 65, splash damage moderately lowered instead.
- Removed Flamethrower MK-3's 2 damage penalty vs Armored.
- Increased the radius of most EC, AC bosses and a few regular enemies to better match their visual size. (Affects Flamethrower MK-3 damage)
- Removed Barret M112's ability to accidentally damage neutral objects via pierce (can still target neutral objects as the primary target).

2021-1-14
[LeoTheCat]
- Disabled the option to add AI players since recruit mode can already be forced during mission select.
- Adjusted Assault's Defensive Plating from reducing 20%/40%/60% max ailment stacks to reducing 30%/40%/50% max ailment stacks.
- Engineer - Field Probe abilities are now converted to 2 different weapon modes that can be swapped. 
- Engineer - Energy Battery now grants a fixed 8 radius aura and no longer adds energy capacity. It instead improves Repair with each level.
- Engineer - Repair can now overcharges the target unit's shield, increasing its max capacity, auto-cast allowed.
- Engineer - Disruption Tower overall dps improved. It now also provides a -5 ranged damage taken aura to allies, can stack twice.
- Engineer - Field Nexus ability icons updated, move speed improved, and weapon removed to avoid uncessary aggro.
- Engineer - Field Nexus Static Shield now also grants 1 shield armor and can affect all allies with shields instead of just field probes.
- Engineer - Compliance Matrix mind control attack speed penalty lowered moderately.
- Engineer's Disruption Tower and Plasma Discharge energy costs have been moderately lowered.

2021-1-11
[LeoTheCat]
- Reworked Chem Expert's Inbound Sickness again into something more team-oriented and practical.
- Added a range indicator for Chem Expert's VRL.
- Due to Chem Expert's Chemical Synthesis rework, anti-venom is now allowed to cast onto non-bio units but will only heal bio units.
- CI Ammo debuff will avoid player and ally units to be consistent with HE Ammo debuff.
- Fixed a bug causing open wound's bleeding visual to appear on the caster.
- Brought back the old TK system and disabled the new TK system to reduce performance overhead (a better version will be made).
- Spawn Factor options also add 10/20% hp scaling in addition to 1/2 Spawn Factor, highest hp scaling limited to 250%.
- Replaced the Realism button with High Spawn button at storyline selection since realism sees rare use. It's still available via -real.
- Added a visual effect for Recon's Execute.
- Added a visual effect for Commando's Surgical Strike.
- Reworked Nano Medic's Energy Capacitor, allowing it offer energy regen to allies when medic damages enemies with her abilities.
- Reworked Nano Medic's Volatile Injection, making it more effective and allowing situational use on allies. 
- Tweaked Nano Medic's Nano Sear. Damage improved but duration reduced. Each stack now reduces some armor too. 
- Lowered the energy costs of some of Nano Medic's abilities.
- Fixed a bug with Marksman's model sizes.

2020-12-14
[LeoTheCat]
- Added the 2 new enhancement items to shop.
- Chemical Expert - Contaminate and Desolation friendly fire damage reduced from 40% to 30%.
- Chemical Expert - Fixed a tooltip error regarding Contaminate's duration, it should be 12s instead of 10s.
- Chemical Expert - Contaminate dps increased from 20/30/40 to 30/40/50.
- Chemical Expert - Contaminate now deal damage/apply venom at a faster interval (does not affect total damage or duration).
- Chemical Expert - Scorched Earth now correctly deal bonus damage up to 15 venom stacks (previously stopped at 8 stacks).
- Chemical Expert - Scorched Earth damage increased from 120 + 25 per venom stack to 120 + 50 per venom stack.
- Chemical Expert's abilities will no longer attempt to apply venom on targets that still have shields.
- Chemical Expert - Chemical Synthesis now affects all abilities at 3/6 energy cost reduction and has some additional venom-related perks.
- Chemical Expert's Desolator abilities have their energy costs slightly adjusted due to the above change.
- Chemical Expert - Inbound Sickness has been reworked.
- Slight balancing of the mutation rate in elite mutation modes so that it's more consistent.
- Fixed a bug causing faith self damage to crit.
- Fixed many visual issues regarding model sizes, such as venom appearing extra large on certain bosses.
- Fixed a visual issue where open wound's bleeding effect stops after mutiple stacks of open wound are applied.
- Turbo (sprint ability on player summoned units) can now be auto-cast.
- HP scaling of enemies now scales more smoothly with squad rating rather than at fixed intervals (such as 1600, 1700, 1800).

2020-12-5
[LeoTheCat]
- MP9A2 Sub-Machine Gun range increased from 9 to 10, backswing slightly improved, adaptive value reverted to 1.
- 590A5 Combat Shotgun damage bonus vs massive reduced from 35 to 30 (total 70 -> 65).
- Crowbar damage increased from 40 to 45.
- Minor adjustments of the TK system, making texts fit in more & less flashy, tuning penalties to be more consistent & reasonable.
- Fixed Rifleman animation bug during repulse.
- Perception stat now correctly gives 1% crit chance per point (was 0.5%).
- One Shot One Kill base damage can now crit (previously One Shot One Kill cannot crit despite visual).
- Fixed a bug causing the actual crit chance to be about twice as much as the stated value.
- Crit skills from Rifleman, Assault, and Marksman have been buffed to compensate for the above bugfix.
- Fixed a design flaw causing Flamethrower to land more crits than other weapons.
- Increased Flamethrower base damage by 2 and reduced vs Armored/Massive penalty from -3 to -2 to compensate the above bugfix.
- Fixed an issue causing UIs to not completely hide during cinematics for players who have died.
- Fixed a bug where Stinger does not damage the impact target if it belongs to the attacking player.
- Elite mutation Monstrous (red aura) will no longer boost the unit's spell damage (such as Cronus laser).
- Added a behavior icon indicating the CP bonuses. Added some more milestones for CP bonuses. 
- Recruit and Normal (vet) now has the same CP decay rate as Nightmare (15%).
- Removed a 1sec shield regen delay on Chem Expert for consistency (all other classes have no delay).
- Players can now use Num Pad 3~6 to play dance/cheer animations on their character. (Only apply to some models, may need Numlock to work)
- Added more skins.
- Added 2 new enchancement items.
- Technician's nanite aura is now allowed to heal structures.
- Creep tumors are now light instead of armored/massive.

2020-11-29
[ThunderRazor]
- The following can be triggered playing solo:
  - Leaks (Scrap yard)
  - Armory turrets
- The following can be triggered by a lone surviving marine:
  - EC airlock civs (Delta-1)
  - AC transport civs (Delta-2)
  - AS dome seal (Sec opt B)
  - Mine shaft (Leto/Zeus/Seth)
- Rewarding less hulk spawns for triggering airlock civs early (15 second window).
  - Hulks capped to spawn factor at 0 seconds.
  - 6x Spawn factor cap at 15 seconds (default).
- If the truck is destroyed early, the bonus objective will fail.
  - Civs will follow marines until escorted to the containment facility.
- Armory turrets are invulnerable while underground.
- Sensor towers are invulnerable.
- Quick use ability is transient.
- Recon Reaper Drone is transient.
- Rifleman Repulse is transient.
- Fixed a bug causing a player to be marked as hacker after getting demoted in rare situations.

2020-11-21
[ThunderRazor]
-Team Kill penalty rework:
   - Direct killing of an ally will apply heavy penalties on the killer immediately (instead of having to type -karmabite).
   - Friendly fire abilities that threaten an ally and subsequently causing their death will apply a lighter penalty.
   - Allies walking into friendly fire abilities and dying as a result will count as an accident with no penalty. 
   - Victims can type "-pardon" to pardon the killer if needed.
- End of game no longer clears chat.
- Class Point Loss is now visible at end.
- All units owned by Marine Squad are now invulnerable after killing Perses in Alpha Company.
- Fixed "Suicide" text in no-killer cases such as death to venom.
- "Fire in the hole" text is only displayed for some damage dealing/blast skills and the stinger.
- Added lobby options for elevated spawn (+1sf) & high spawn (force sf 9 in NM mode, +1sf in others).
- Team location ability ( x -> q ) will now also display the controller of units that have shared control.

[LeoTheCat]
- Added a skin for Forward Observer.
- Removed the weird sniper rifle sound from shotgun attacks.
- Looked into an issue ocassionally causing mind controlled units to hurt ally marines - and probably fixed it.

2020-11-4
[ThunderRazor]
- Likely fixed issues that could occasionally cause nightmare mode to turn into recruit mode during selection.
- A1Abrams (Charlie Company Tanks) is now immune to Eos shriek.
- Minor AI improvements for zombies.

[LeoTheCat]
- Removed the early ambient spawn in Sec (which provided continuous extra mobs throughout the game).
- Slightly reworked the armory & comms waves in Sec, making them more challenging while keeping the overall XP income roughly the same.
- Infestor ambient spawns (when there are infestors alive) for Sec will now very occasionally spawn an infested marine instead of a zombie.
- Kill XP for infested marines lowered from 11 to 9, minor XP adjustments for other units as well (mainly to control XP income in Sec).
- Shared XP multiplier (for XP leeching) slightly lowered for PsiOps and Technician, minor adjustments for other classes as well based on
  their roles in the current meta.
- Nightmare mode button can no longer be toggled off to enter recruit mode, instead, normal button needs to be used for the toggle.
- Mobs spawned during Sec path A reactor download cycles now have a cap to avoid too much spawn causing the game to lag out.
- Shifted the complaince nexus near the bottom gen slightly so that it is not out of map bounds and can thus be attacked directly.

2020-10-22
[ThunderRazor]
- Fixed a bug where seekers are spawned incorrectly at Epsilon and causes FO minis to be instantly killed.
- Fixed a bug where ammo box may fail to pick up any ammo. 
- Fixed a bug where the game mode could mismatch with the difficulty if the mode is toggled quickly.
- Fixed a bug where the promotion visual effect isn't displayed correctly.

[LeoTheCat]
- Fixed a bug where vote kick karma penalty is applied incorrectly. 
- Ammo box will no longer destroy itself when stacked under certain conditions.
- Highlight tooltip of magazines and ammo boxes will now display the amount of ammo.
- Disabled the anti-swear feature due to abuse.

2020-10-17
[ThunderRazor]
- Added a "Class Trait" system allowing classes to be unlocked earlier based on the CP of other classes (original XP-unlock unaffected).
- All classes are made available in recruit mode (still requires XP or CP to unlock).
- In recruit, classes that previously didn't belong are CP-locked only (can't be unlocked with XP but can still be randomed at 10k XP).
- Veteran mode has been renamed to normal mode for the sake of clarity in the mission select screen. 
- Normal mode can now be toggled by clicking on the "Normal" button again to activate or de-activate it. 
- When normal mode is toggled off, the game will be in recruit mode.
- If the team does not meet the scaled XP requirement for normal mode, the "Normal" button will appear disabled.

[LeoTheCat]
- Attempted to fix Marksman's mono visual bug.
- Removed additional M5 spawns from AC recruit (the lab one still remains), made minor adjustments to AC recruit weapon spawns.
- Added a couple rare weapons to Sec recruit (still no Stinger), Sec vet now has 1 Stinger spawn at chapter 2 (previously none throughout).
- Surv recruit can now proceed past wave 20, added adjusted rewards for wave 20+ in recruit (much less than that of vet/nm).
- Adjusted the XP rewards for all recruit modes so they are reasonably less than that of vet/nm modes (EC recruit unchanged).
- Nazara in Sec recruit will no longer "assume direct control" of random zombies.
- Balanced the posion cloud in -em mode so that it stacks slower and checks cliff level.
- Hardened zombies in -em mode will no longer zap cloaked marines (such as Recon) out of energy.
- Zergling is offiicially the fastest pet on the face of the moon (Eshir you happy now?)

2020-10-15
- Added shared vision for new players under 500 XP (ThunderRazor).
- Removed vote kick requriement. If vote kick is successful, players who voted will lose some karma, but the player who is kicked will lose
  a much greater amount of karma. One cannot vote kick again if the previous vote kick has not been resolved (ThunderRazor).
- Fixed some classes not having the correct unlock tooltip, due to class swaping and new xp requirements etc, (Leo)
- Fixed chemical leak hexes not removed in recruit AC (Leo).

2020-10-12
- Disabled the cancel button for taunt skillls and Marksman's Stealth, a placeholder button is put in instead to allow stopping auto-cast.
- Cleared the banlist.
- Experimental changes on mode availability:
- XP requirement is now calculated based on the average XP of the team on a log scale, instead of based on the minimum.
- XP requirement for Nightmare mode increased from 500 to 4500, and still requires "No Newbie" (Everyone > 500XP).
- The same 3500XP requirement is now used to determine Recruit vs Vet mode in a non-nightmare game. (Instead of "No Newbie")
- Rewards have been added for Recruit AC, Surv, Sec as these now become possible.
- When calculating the log scale average, players with more than 100k XP is considered 100k XP.
- A message now displays at the beginning of the game showing the log scale average XP and the number of new players (<500XP).

2020-10-08
- Fixed Survival Perses ignoring stuns.
- Further balancing of Elite Mutation mode, nerfing atrocious and adding mechanics to other mutations to make them more interesting.
- Added a new mutation to Elite Mutation - Acidic, causing attackers to lose health over time and leaves a toxic cloud upon death.
- Refined the EC Easter Egg and made it harder to trigger.
- Added a "-mobs" command to check mob count in case of lagging.
- Shifted the added early Sec ambient spawn to after triggering Armory and removed the muta spawns.
- Clarified the tooltip for FO mini's Slow Roast upgrade.
- Fixed Cronus weapon displaying an incorrect amount of damage.
- Added some tooltips to Pathfinder's assault jump behavior.

2020-10-04
- Refined some terrain pathing (Thunderazor).
- Added an old easter egg (Thunderazor).
- Minor tooltip fixes (Leo).
- EC Nydus Worm pings now get destroyed if the Nydus Worm dies - to make kill tracking easier (Leo).
- Added kitten skins (Leo).
- Rifleman - Weapon Efficiency now increases both the duration and the cooldown of Focus Fire by 1 second (Leo).
- Some buffs to make pets' life better (Leo):
- Pets now gain minor unscaled damage bonus when leveling up.
- Players with lv3 or higher Bronze Star medal now have their pets start at lv2.
- In addition to growing to EPIC proportions at lv12, pets also have their lightning field radius increased to match the lv12 visual.
- Pirahna Missiles now have the same adaptive value (0.7) as Robotic Claws for the sake of consistency. (It used to be 1.0)
- Improved the backswing of Pirahna Missiles to match that of Robotic Claws (for easier infestor chase).
- Added a command card button specifying level up bonuses for pets.

2020-10-01
- Attempted to fix the following issues (may not be 100% fixed):
  Heal sound persisting after channeling stops.
  Crowbar sound having a global range.
  Engineer's Plasma Discharge AOE indicator persists after destruction.
- Atrocious elite mutation (fast regen) boss version can now be weakened with stuns. Limited duration removed.
- Added tooltips to all elite mutation behaviors.

2020-09-26
- Minor UI fixes.
- Minor modifications to Realism mode.
- Added a training mode that can be activated via typing "-train" or "-training", 4 or fewer players only.
  Can be used for solor practice & testing etc.
- Reworked M5 Pulse Rifle, making it more suitable for support classes.

2020-09-21
- Reworked Realism mode, skill indicators now display as usual. Instead, taunt and cloak auto-casts are disabled. Taunt circles remain
  disabled as well. % reduction armor mechanics is disabled and most tank class talents reverted to original. Realism mode description
  changed to "Just like the old times." Realism now available in all modes.
- Added to the tooltip of road flares specifying the real time duration (Dropship timer uses real time).
- Master of the Universe rank may now be saved and loaded correctly.
- Fixed Medals UI not working after player deaths.
- Barrett M112 now pierces an additional 2 targets behind the initial target, unaffected by splash mod.
- Weapon splash mod now correctly applies to L3 Grenade Launcher.
- Assault - Defensive Plating armor value reverted to +2/3/4 and now offers -20%/-40%/-60% max ailment stacks instead of regen.
- Assault - Charge now ignores Eos shriek while active.
- Assault - Cohersion Aura now grants +0.4 health regen to affected units.
- Slightly improved Assault's base life and energy regen.
- Nano-Health Augment health bonus is now divided into 2 stacks (need 2nha to reach the same health bonus).

2020-09-15
- Reduced the spin speed of Forward Observer's gunship to avoid motion sickness, the camera angle of the gunship has also been raised.
- Added additional UI at the mission select panel for special mods such as Elite Mutation, Realism, Outbreak... etc.
- Airlocks gates now automatically open after erebos 1 to avoid pathing bugs & lag when holding at Dome B.
- Fixed ping panel not working properly.
- Reduced the recently added early ambient spawn in Sec to prevent over leveling and disabled most of that during the final boss.
- Demolitions - Spiked Armor reverted to +4 shield armor at lv3.
- Fixed a game-breaking bug incorrectly stating Devastators as "Thors".
- More balancing tweaks with elite mutation mode and fixed some bugs that potentially caused lag.

2020-09-10
- Elite Mutation Mode added. Activate using "-elite mutation" or "-em" command, available in all difficulties.
- Must be typed at the beginning of a game, similar to -nm and -ob commands.
- Mutated enemies spawn after 180 game seconds, mutation frequency scales up as game goes on.
- Realism Mode added. Active using "-realism" or "-real" command, can be toggled.
- Must be typed at the beginning of a game, hides most UI and visual aids.
- Additional skins added.
- Flamethrower - Burst Fire energy cost reduced from 18 to 15, Inferno energy cost reduced from 35 to 30.
- Forward Observer - Shockwave Barrage lv2 stun duration reduced from 6 to 5 seconds.
- Fibrin Bandage hotkey reverted to the old x + x, quick use item hotkey becomes x + w instead.
- Survival mode IVAX and Seth health now scales with difficulty.

2020-09-08
- Credit rewards re-adjusted so that the total credits from all missions match the original NOTD. Slight shifts in payout are made as below:
  EC: 50 credits more than original EC  |  AC: 100 credits more than original AC  |  Sec: 150 credits less than original Sec;
- MP9A2 Sub-machine gun damage lower from 14(+14 vs light) to 12(+12 vs light).
- Forward Observer Shockwave & Napalm Barrage cooldown increased by 1.
- Forward Observer Lunar Technologies lv2 no longer reduces Airstrike cooldown, still reduces energy cost and allows 2 charges.
- Recon Laser Designator model reverted to the old model (laser drill lock-on).
- Added some moderate ambient spawn for Sec (starting after rescue).

2020-08-31
- Marine skill icons reverted to their old locations.
- Players with over 10k xp no longer gains or loses class proficiency points when random in recruit games.
- Players with over 10k xp now gains 1 additional karma upon finishing a recruit game with randomed class.
- Players now lose 1 karma for failing the civs quest at Delta-1 (including when civs have all turned into zombies due to delay).
- Added skins for various classes, XP and Karma act as qualifications for skin usage, no credit needed.
- Marksman - Leveling up concentration replaces the previous stacks instead of simply removing them.
- Minor visual changes and bug fixes.

2020-08-29
- Demolitions - Spiked Armor shield armor bonus reduce from +1/2/4 to +1/2/3
- Assault - Defensive Plating health bonus removed, armor bonus changed from 2/3/3 to 2/2/3, lv2/lv3 grants 10%/20% more hp regen.
  (Burst heal effects such as surgical laser, restoration, bandage, are not considered as hp regen)
- Assault - Taunt radius changed from 7/8/9 to 8 at all levels.
- 5 CP bonus changed from 10 shield and +1 shield armor to 10 shield and +1 unscaled melee damage.
- Minor tooltip fixes.
- Added some visual updates for Demolitions, Technician, Engineer, Marksman, Pathfinder, Chemical Expert, Psi Ops, and Commando.

2020-08-27
- Flamethrower - Inferno (Ultimate) rework:
  Can affect air units, affected units now burn itself and nearby enemies for 50 dmg over the duration of 5 sec, then explode for 150 dmg.
  No longer creates naplam on explosion. Explosion still has a 40% chance to spread inferno to nearby biological enemies.
  Explosions now deal minor friendly fire damage, caution advised.
  Flamethrower now gains 10 stacks of frenzy (if learned) upon casting Inferno.
  Burst Fire now immdiately triggers Inferno explosion.
  Inferno Cooldown increased from 9 seconds to 15 seconds.
- Fixed BURN still playing the animation when the target is already out of vision. Added sound effects for BURN.
- Added some visual updates for Flamethrower, Assault, Recon, Medic.

2020-08-25
- Fixed Rifleman Sonic Trap bug.
- Visual update for Rifleman.
- Sec Hades payout reduced from 0/250/650 to 0/220/600 (to counter "inflation").
- Nano-Health Augment now adds 22 health in addition to the 0.4 health regen. Bonus health does not stack.
- Flamethrower (Hero) - BURN! channel time to max damage/armor reduction reduced from 8s/4s to 5s/2s. Effect now persists for 3.5 seconds
  after channelling stops. (Does not gain new stacks).
- Fixed a bug causing Pathfinder's shield armor to be displayed incorrectly.
- Forward Observer players can now type "-dp 1/2/3" to control the dispersion of shells (default is 1).
- Forward Observer skills ranges now display correctly when hovering over the buttons.

2020-08-23
- Forward Observer shell count reverted to 1600. Shells are no longer produced over time.
- Forward Observer passive reworked again:
  Lv1 - Reduces call down time by 1.5 sec (unchanged).
  Lv2 - Reduces the cooldown and energy costs of airstrike, allowing up to 2 charges.
  Lv3 - Reduces the cooldown and energy costs of most barrage call downs.
- Units killed by napalm fire now provide shared XP to FO's nearby teammates. FO only gains partial XP.
- Units killed by airstrike bombs now provide shared XP to FO's nearby teammates. (FO already gains full xp from airstrike kills).
- Surveillance flare duration increased to 120s, cooldown increased to 90s. Range matches artillery skills. Allowing a maximum of 2 charges.
- Fire Mission lv2 damage changed from 75(+25 vs armored) to 75(+25 vs armored/massive).
- Fire Mission lv3 damage changed from 75(+25/50 vs armored/massive) to 75(+25/75 vs armored/massive).
- Napalm Barrage burn maximum stacks reduced from 6 to 5, slow reduced from 40% to 30%.
- Disabled the camera shake for shell impact.
- Icon update for Forward Observer.

2020-08-22
- Minor tooltip updates & fixes.
- Fixed anticipation buff becoming permanent once learned.
- Added nm and ob options in mission preference. (only visual)
- Visual indicator update for Forward Observer.
- Forward Observer - Fire Mission dmg changed from 25/50/75 (+50% vs massive) to 50/75/75 + 0/25/25 vs armored + 0/0/50 vs massive.
- Forward Observer - All shells impact radius increased from 2 to 2.5, call down wait time reduced from 8 to 5 sec.
- Forward Observer - Fire Mission/Shockwave Barrage random hit radius reduced from 5 to 2.5 (more accurate), Total possible impact radius
  reduced from 7 (5+2) to 5(2.5+2.5). Napalm Barrage total impact radius unchanged (7).
- Forward Observer - Starting and max shell count reduced to 1300 from 1600. Now 1 shell is produced every 12 sec (5 shell / min).
- Forward Observer - Lunar Booster reworked into Tech Upgrades:
   lv1 Lunar Booster: reduces call down time by 1.5 seconds, resulting a 3.5 sec call down time consistent with previous lv3 Lunar Booster.
   lv2 Smart Sensors: negates friendly fire damage from air strikes.
   lv3 Rapid Production: produces 5 more shells every minute (12sec / shell -> 6sec / shell).

2020-08-20
- Demo - I'm Your Father enemy damage reduction rescaled from 15%/30%/45% to 20%/30%/40%.
- Assault - Defensive Plating changed from +2/3/4 armor to +2/3/3 armor, 0/5/10 life, and 0/0/20% life regen amp.
- Assault - Safeguard maximum stack reduced from 7 to 6, duration increased from 5 to 6.
- Removed some uncessary behaviors from the detailed behavior bar, added some others.
- Spells now ignore the % dmg reduction from armor. (But can still be amplified by negative armor).
- AP Ammo -armor debuff now stacks up to 3 times.
- Added dropdown menus for mission and role preferences in the lobby. Currently only acting as a visual indicator.

2020-08-19
- Assault Taunt range increased from 5/6/7 to 7/8/9, fixed tooltip incorrectly stating the range being 6/8/10.
- Fixed Forward Observer not having the Quick Use ability, updated the icon art for Quick Use and Team Location.
- Fixed NC not breaking when using medkits or bandages with Quick Use.
- Marine Speech (yellow dialogue over head) now stays visible for a while instead of fading immediately.
- Lelantos (Brood Lord) and Mini Nydus now have their health bars displayed.
- Experimental: Each armor or shield armor (pick the greater one) now provides additional % dmg reduction, at roughly 1% per armor,
  scaling up to 50% at 100 armor. Negative armor points now increase dmg taken, at roughly 1% per negative armor, scaling up to 270%
  increased dmg taken at -100 armor. All % calculation is done after flat armor calculation.
  Reference formula for positive armor: (armor * 0.01) / (1 + armor * 0.01) reduced
  Reference formula for negative armor: 1.01 ^ armor - 1 amplified

2020-08-17
- Re-enabled ammo bar move button and made it more visible. It now allows the ammo bar to swap places with the new behavior bar.
- Added a second button after the ammo bar move button to allow enabling/disabling the new behavior bar.
- Greatly reduced the number of behaviors tracked by the new behavior bar to reduce distraction.
- Made some code-side changes in hope to optimize the performance of the new behavior bar.
- "-bar on/off" command simplified to just "-b", and it will toggle the status bar style.
- "-ping on/off" command simplified to "-qp" (standing for quiet pings).
- Messages are sent in the chat area to confirm any UI related changes.
- Misc. tooltip/icon changes to avoid confusion with the new behavior bar.
- Fixed some UI related errors upon marine death.

2020-08-12
- Fixed broken terrian (cracks) near the bottom hill
- Visual effects overhaul for Chemical Expert, Scorched Earth cursor indicator is now more accurate and grants vision of the impact area
- Added a cursor indicator for marksman's Monofilament Cartridge
- Assault can now move through units during charge
- AER13 Laser Rifle now deals bonus dmg based on the target's base armor (no longer affected by debuffs such as AP ammo)
- Updated some tooltips that were incorrect.
- Updated loading images
- Added a new behavior tracking bar to show behavior stacks and duration, temporarily disabled ammo UI move button to make room
- Added a Quick Use skill for every marine (hotkey x + x), allowing immediate usage of the first inventory item (weapon, medkit, bandage
  only) Fibrin Bandage skill hotkey changed to (x + w). Block Inventory Transfer button removed.

2020-08-11
- Fixed CP mix-up after the PF/FO swap, you bank records are NOT affected, only the interpretation logic has been changed,
  CP earned on PF will be attributed to FO in the original version and vice versa.
- Added 2 more chat commands: -bar on/off and -ping on/off to allow classic style status bars and a more tuned down ping system
- Marksman's Stealth can now be auto-cast
- Added a shield armor tooltip to all classes on their armor icon
- 5 CP bonus now offers 10 shield and 1 shield armor (consistent with the wiki) as opposed to just 10 shield
- AC IVAX payout reduced from 0/160/500 to 0/140/450
- Optimized Assault's charge skill with fewer hit checks to reduce lag, enabled targeting charge out of vision.
- MP9A2 Sub-Machine Gun adaptive value increased from -1/armor to -1.2/armor
- M5 Pulse Rifle added back to the game (single fixed location, experimental).

2020-08-10
- Removed collision for zombie cocoons and barrels
- Demolition & Assault's taunt skills can now be auto-cast
- Removed the smoke effect from taunt skills, added a range indicator for all taunt sources (including technician's mad spark)
- Updated visuals for Guardian of the Beta, Orbital Laser, and Nano-Shield
- MP9A2 Sub-Machine Gun damage increased from 12/22 (normal/light) to 14/28 (normal/light)
- Lv2 Zombies are now also marked as Light (consistent with Lv1 zombies)
- FO(AC) has been swapped with PF(Sec), their CP groups are now Demo/PF/Chem and Engineer/FO

2020-07-08
- Fixed a bug that prevents Pathfinder from leveling up
- Reworked item purchasing & magazine dropping code to avoid bugs causing various ammo related issues
- Fixed a bug that causes item weights to not apply correctly
- Updated the drop pod attack at Erebos with more clear visuals and sounds (removed the weird shotgun sound)
- Experimenting with unsegmented status bars
- Experimenting with ping panels (alt and hold for options)
- Updated weapon tooltips to include armor reduction values
- UI update: a new bossbar and an icon for the Master of the Universe Rank
- EC Eos Kill Credit Reward increased from 50/50/100 to 50/75/150 (re/vet/nm)
- AC IVAX Kill Credit Reward increased from 0/80/215 to 0/160/500 (re/vet/nm)
