# The HFM Enhanced Series (MP) - Changelog

## This mod is built on HFM V1.27I (SighPie) and HFM More Stuff V3.5 (u/louisky58) submod.
**Credit:**
- Infamy reduction depending on rank & healthcare changes inspired by Heirs to Aquitania (Savs)
- Population size effects, final tech row, and LGLC tax moddifiers inspired by PDM Divide by Zero (GAGA Extrem)
- Population growth decision and conditions UI changes taken from The Grand Combo (Jman & others)
- Unciv rework from Harolds Triumph (Atlas), built from PUIR (Reno)
- Revanchism buffs taken from PUIR (Reno)
- Generals UI change, Trade Agreements & Tech/Inventions taken from Victoria Universalis (KevinG)
- Aircraft Carrier & Bomber icons and sprite from CWE mod (settintotrieste & others)
- Liberate & Puppet CB, Steal Puppet CB, map textures from HFME (Jman & others)
- Protectorate CBs from HPM 0.4.6 (arkhometha)
- Clerk only factories & new goods GFX from PDM (Naselus)
- Iran flavour by Atlas
- Haiti flavour by Jman
- Military topbar expansion by SirRunner
- Thanks to Nurse_Reno for the craftsmen & bureaucrats fix, and immigration code.
- Thanks to Zombie for the keybinds help
- Thankyou to Jman for the batch file to add in parties
- Settings file from ZombieDoD (Zombie_Freak)
Thankyou to Zombie_Freak for the advice over the past months
Everything else is our own (as far as I remember).
---
<br/>

**Any problems or changes to suggest can talk to lead dev: Townes**

<br/>
---
<br/>

## Political
#### Government Forms
- Anarchist: Similar to republic, locked into anarchist 'party'
#### National Values
- Can change via decision if republic or anarchist
#### Reforms
- Executive: Can allow executive power, options restricted via government form
- Militarization: Raises or lowers the max soldier pops per state
- UBI option for socialists & vanguardists (very high pension level)
- R&D Policy: More RP, increase via decision conditions
- Westernisation: Reforms unlock tech up to lvl 2 (and nothing else)
#### Administration
- Base of 1.5% bureaucrats required for full admin efficiency from them
- Require 2% bureaucrats to state colonies
#### Parties
- Anarchists: Rare, similar to socialists, successful rebels will enforce Anarchism
#### National Focuses
- Party support increased to 0.010 daily
- Assimilation NF
#### CBs
- Great Wars locked until 1900
- Can add war goals on puppets
- Justify 'fake' overlord war in order to add CBs on puppets
- Take capital & minor conquest added
- Liberate and puppet, and steal puppet CBs added
- Military access CB (~week justification), the war is the access
- Mass conquest if a dictatorship form with Mass Politics
- 10 infamy demand chinese concession
#### Revanchism
- Army & mob buff modifiers scale with % of revanchism (capped at 50%)

## Population
#### Liferating & Growth
- France average life rating increase to 33
- USA starts at 40
- Westernised China, India and Korea can increase to 40 with tech, will decrease in ~50 years
- ~1900-1910, Decrease to ~31 for Germany, Benelulx, Italy, Britain, Austria-Hungary, USA (in two stages)
- Pop-growth techs nerfed
- Healthcare only grants +0.01% pm at top level fully funded
#### Pop Needs
- Demand increase from inventions decreased to 1% per invention
- Luxury manufactured goods in luxuries for lower and middle class
- Tea & Coffee moved into luxuries
- Removed basic food demand as luxuries (canned food instead)
#### Demotion & Promotion
- Reduced (~33% decrease) rate of promotion
- Greatly (+100%) increased rate of promotion
- Non-accepted overseas colonials limited to 1% soldiers, until Colonial Reform (then limited to 2.5%)
#### Assimilation
- Republics have a slight increase
- Equality NV: slight increase
- Full cultural rights reform: allows assimilation on cultural cores (still some engine locks)
- Can manually core overseas
#### Immigration
- New World buff reduces 1900+
- Attraction from reforms greatly increased
- USA buffs nerfed slightly
#### Emigration
- Life needs met effects rate
- Removed almost all culture-specific modifiers
- Republic & Con. Monarchy have very slightly reduced rates
- Fully funded UBI has a very slightly reduced rate

## Economic
Overseas penalty increase 3x, to 0.1 per provinces
#### Goods
- Copper (RGO): Used to make bronze and in electrical goods
- Tin (RGO): Used to make bronze
- Combined precious metals into precious goods
- Shares: Factory supply good & used to make stocks
- Stocks: Rich middle class and upper class good
- Pharmaceuticals: Army and richer pops supply good
- Interwar Hulls: Required for aircraft carriers
#### Factories
- Bronze: Tin & Copper inputs
- Pharmaceuticals: Glass & Opium
- Banks (Shares): Paper (clerk only)
- Stock Exchange (Stocks): Paper, Shares (clerk only)
- Interwar shipyard (Interwar Hulls): Steel, Coal, Machine Parts, Bronze
- Synthetic Rubber: Oil
- Nitrate Factory (Sulphur): Coal, Iron
#### Tech
- Power: Grants RGO size increases
- Metallurgy: Huge output buffs
- Transport: Later techs increase max railroad to lvl 10
- Farm RGOs stop scaling with late-campaign Power and Transport tech
#### Infrastructure
- Railroad: Max lvl increased to 10, effects per railroad lvl buffed (RGO output & factory throughput)
- Naval Bases: No longer give navy cap, max lvl increased to 8

## Military
#### Units
Soldier pops concentrate in state capitals, requires 3k soldier pops for 1st brigade (then 5k onwards)
- Bombers: 'Attack version' of planes (fighters)
- Guards: Have recon (less than hussars)
- Aircraft Carriers: Long range, high attack, mid hull
- Dreadnoughts: Scale better with tech
- Cruisers: Require small amount of oil to build
- Submarines: Torpedo attack & high evasion
#### Tech
- Heavy Armament: Greatly buffed artillery attack
- Submarines scale greatly with 1900+ tech
#### Combat Width & Supply
- Brigades are 5k
- 5 combat width increase in 1920 & 1930
- Base supply increased ~60%
- Greater multiplier from tech
#### Naval Supply
- All coal supply requirements for ships removed
- Strength loss occurs below 75% supply
- Strenght min set to 0 (will not auto-delete)
- Base repair rate halved
- Ports give -5% build time & 5% repair speed per level

## Flava
Many nations no longer need (only) GP for flava, or high prestige. War policy requirements relaxed, and can't form nations on players
#### Europe
- UK: Can revolt to the UFB, can keep Irish accepted, can annex the EIC at the start 
- FRA: Can take empire flava as the Republic
- AUS: Can form SGF (and release its non German land)
- DNB: RnG removed & cultures now accepted via decisions
- RUS: Only cores Poland late-campaign, option to take all of Manchuria, decision to core CPL land
- Ottos: Tanzimat reforms can be completed as a republic & Arab revolt won't remove accepted cultures
- POR: Can unite with Brazil to form the UPB
#### Americas
- USA: Can claim all of Mexico (with only standard MD cores)
- Mexico: Can accept Centeral American
- Gran Columbia: Carribean and Peru-Bolivia expansion ability
- Brazil industrial RGO change decisions later-campaign
#### India
- EIC if independent can form India
- Decolonisation RGO changes
#### China
- Qing collapses with 2 miltancy and non conservative/reactionary party, or if it is a republic
- After surviving the Warlord Era can accept all Chinese cultures
#### West Africa
- Niger Empire / Federation union tag added (with industrial RGO changes)
#### East Africa
- Ethiopian cultures can form the East African Federation, or Coptic Empire with expansion south and north respectively

## Map
- Rivers with -2 crossing plenlty added (province modifier label)
- Redrawn Trieste area & West Switzerland
#### Straits
- Vanilla straits added (Dover-Calais, Japan-Korea)
- Hormuz & Carribean straits
#### Canals
- Copenhagen Canal (controlled by Copenhagen) with straits access across the islands
- Gibraltar Straits operate as a canal with two control provinces: Gibraltar, Ceuta
- Both Gallipoli and Golden Horn act as dual control canals, with provinces on either side as control provinces
- Aden Strait acts as canal

## AI
- AI now weighted to build meta stacks
- High priority to take key techs (Medicine & Military Directionism)
- Enthusiasm for bad focuses set to 0
- Aggressiveness massively increased

## MP Support
#### Grants
- Standard Money Transfer options
#### Infamy Transfers
- Like grants, but limited to GPs or cpital on the same continent
- Take for ally CB
#### Land Transfers
- State
- State (3rd party)
- Substate