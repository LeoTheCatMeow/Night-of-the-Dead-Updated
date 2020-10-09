# Night of the Dead Updated

Disclaimer: I take no credit for the base game. This is only a personal attempt to bugfix and keep the game up and running smoothly in SC2 Arcade, with potential QOL or community requested updates. There may be a small amount of experimental features and personal explorations, but I will do my best to keep the game stable.

# Current Changes & Bugfixes Tracklist

8.7.2020
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

8.10.2020
- Removed collision for zombie cocoons and barrels
- Demolition & Assault's taunt skills can now be auto-cast
- Removed the smoke effect from taunt skills, added a range indicator for all taunt sources (including technician's mad spark)
- Updated visuals for Guardian of the Beta, Orbital Laser, and Nano-Shield
- MP9A2 Sub-Machine Gun damage increased from 12/22 (normal/light) to 14/28 (normal/light)
- Lv2 Zombies are now also marked as Light (consistent with Lv1 zombies)
- FO(AC) has been swapped with PF(Sec), their CP groups are now Demo/PF/Chem and Engineer/FO

8.11.2020
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

8.12.2020
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
  
8.17.2020
- Re-enabled ammo bar move button and made it more visible. It now allows the ammo bar to swap places with the new behavior bar.
- Added a second button after the ammo bar move button to allow enabling/disabling the new behavior bar.
- Greatly reduced the number of behaviors tracked by the new behavior bar to reduce distraction.
- Made some code-side changes in hope to optimize the performance of the new behavior bar.
- "-bar on/off" command simplified to just "-b", and it will toggle the status bar style.
- "-ping on/off" command simplified to "-qp" (standing for quiet pings).
- Messages are sent in the chat area to confirm any UI related changes.
- Misc. tooltip/icon changes to avoid confusion with the new behavior bar.
- Fixed some UI related errors upon marine death.

8.19.2020
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
  
8.20.2020
- Demo - I'm Your Father enemy damage reduction rescaled from 15%/30%/45% to 20%/30%/40%.
- Assault - Defensive Plating changed from +2/3/4 armor to +2/3/3 armor, 0/5/10 life, and 0/0/20% life regen amp.
- Assault - Safeguard maximum stack reduced from 7 to 6, duration increased from 5 to 6.
- Removed some uncessary behaviors from the detailed behavior bar, added some others.
- Spells now ignore the % dmg reduction from armor. (But can still be amplified by negative armor).
- AP Ammo -armor debuff now stacks up to 3 times.
- Added dropdown menus for mission and role preferences in the lobby. Currently only acting as a visual indicator.

8.22.2020
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
   
8.23.2020
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
- Napalm Barrage burn maximum stacks reduced from 6 to 3, slow reduced from 40% to 30%.
- Disabled the camera shake for shell impact.
- Icon update for Forward Observer.

8.25.2020
- Fixed Rifleman Sonic Trap bug.
- Visual update for Rifleman.
- Sec Hades payout reduced from 0/250/650 to 0/220/600 (to counter "inflation").
- Nano-Health Augment now adds 22 health in addition to the 0.4 health regen. Bonus health does not stack.
- Flamethrower (Hero) - BURN! channel time to max damage/armor reduction reduced from 8s/4s to 5s/2s. Effect now persists for 3.5 seconds
  after channelling stops. (Does not gain new stacks).
- Fixed a bug causing Pathfinder's shield armor to be displayed incorrectly.
- Forward Observer players can now type "-dp 1/2/3" to control the dispersion of shells (default is 1).
- Forward Observer skills ranges now display correctly when hovering over the buttons.

8.27.2020
- Flamethrower - Inferno (Ultimate) rework:
  Can affect air units, affected units now burn itself and nearby enemies for 50 dmg over the duration of 5 sec, then explode for 150 dmg.
  No longer creates naplam on explosion. Explosion still has a 40% chance to spread inferno to nearby biological enemies.
  Explosions now deal minor friendly fire damage, caution advised.
  Flamethrower now gains 10 stacks of frenzy (if learned) upon casting Inferno.
  Burst Fire now immdiately triggers Inferno explosion.
  Inferno Cooldown increased from 9 seconds to 15 seconds.
- Fixed BURN still playing the animation when the target is already out of vision. Added sound effects for BURN.
- Added some visual updates for Flamethrower, Assault, Recon, Medic.

8.29.2020
- Demolitions - Spiked Armor shield armor bonus reduce from +1/2/4 to +1/2/3
- Assault - Defensive Plating health bonus removed, armor bonus changed from 2/3/3 to 2/2/3, lv2/lv3 grants 10%/20% more hp regen.
  (Burst heal effects such as surgical laser, restoration, bandage, are not considered as hp regen)
- Assault - Taunt radius changed from 7/8/9 to 8 at all levels.
- 5 CP bonus changed from 10 shield and +1 shield armor to 10 shield and +1 unscaled melee damage.
- Minor tooltip fixes.
- Added some visual updates for Demolitions, Technician, Engineer, Marksman, Pathfinder, Chemical Expert, Psi Ops, and Commando.

8.31.2020
- Marine skill icons reverted to their old locations.
- Players with over 10k xp no longer gains or loses class proficiency points when random in recruit games.
- Players with over 10k xp now gains 1 additional karma upon finishing a recruit game with randomed class.
- Players now lose 1 karma for failing the civs quest at Delta-1 (including when civs have all turned into zombies due to delay).
- Added skins for various classes, XP and Karma act as qualifications for skin usage, no credit needed.
- Marksman - Leveling up concentration replaces the previous stacks instead of simply removing them.
- Minor visual changes and bug fixes.

9.8.2020
- Credit rewards re-adjusted so that the total credits from all missions match the original NOTD. Slight shifts in payout are made as below:
  EC: 50 credits more than original EC  |  AC: 100 credits more than original AC  |  Sec: 150 credits less than original Sec;
- MP9A2 Sub-machine gun damage lower from 14(+14 vs light) to 12(+12 vs light).
- Forward Observer Shockwave & Napalm Barrage cooldown increased by 1.
- Forward Observer Lunar Technologies lv2 no longer reduces Airstrike cooldown, still reduces energy cost and allows 2 charges.
- Recon Laser Designator model reverted to the old model (laser drill lock-on).
- Added some moderate ambient spawn for Sec (starting after rescue).

9.10.2020
- Elite Mutation Mode added. Activate using "-elite mutation" or "-em" command, available in all difficulties.
- Must be typed at the beginning of a game, similar to -nm and -ob commands.
- Mutated enemies spawn after 180 game seconds, mutation frequency scales up as game goes on.
-----------
- Realism Mode added. Active using "-realism" or "-real" command, can be toggled.
- Must be typed at the beginning of a game, hides most UI and visual aids.
----------
- Additional skins added.
- Flamethrower - Burst Fire energy cost reduced from 18 to 15, Inferno energy cost reduced from 35 to 30.
- Forward Observer - Shockwave Barrage lv2 stun duration reduced from 6 to 5 seconds.
- Fibrin Bandage hotkey reverted to the old x + x, quick use item hotkey becomes x + w instead.
- Survival mode IVAX and Seth health now scales with difficulty.

9.15.2020
- Reduced the spin speed of Forward Observer's gunship to avoid motion sickness, the camera angle of the gunship has also been raised.
- Added additional UI at the mission select panel for special mods such as Elite Mutation, Realism, Outbreak... etc.
- Airlocks gates now automatically open after erebos 1 to avoid pathing bugs & lag when holding at Dome B.
- Fixed ping panel not working properly.
- Reduced the recently added early ambient spawn in Sec to prevent over leveling and disabled most of that during the final boss.
- Demolitions - Spiked Armor reverted to +4 shield armor at lv3.
- Fixed a game-breaking bug incorrectly stating Devastators as "Thors".
- More balancing tweaks with elite mutation mode and fixed some bugs that potentially caused lag.

9.21.2020
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

9.26.2020
- Minor UI fixes.
- Minor modifications to Realism mode.
- Added a training mode that can be activated via typing "-train" or "-training", 4 or fewer players only.
  Can be used for solor practice & testing etc.
- Reworked M5 Pulse Rifle, making it more suitable for support classes.

10.1.2020
- Attempted to fix the following issues (may not be 100% fixed):
  Heal sound persisting after channeling stops.
  Crowbar sound having a global range.
  Engineer's Plasma Discharge AOE indicator persists after destruction.
- Atrocious elite mutation (fast regen) boss version can now be weakened with stuns. Limited duration removed.
- Added tooltips to all elite mutation behaviors.

10.4.2020
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

10.8.2020
- Fixed Survival Perses ignoring stuns. 
- Further balancing of Elite Mutation mode, nerfing atrocious and adding mechanics to other mutations to make them more interesting.
- Added a new mutation to Elite Mutation - Acidic, causing attackers to lose health over time and leaves a toxic cloud upon death.
- Refined the EC Easter Egg and made it harder to trigger.
- Added a "-mobs" command to check mob count in case of lagging.
- Shifted the added early Sec ambient spawn to after triggering Armory and removed the muta spawns.
- Clarified the tooltip for FO mini's Slow Roast upgrade.