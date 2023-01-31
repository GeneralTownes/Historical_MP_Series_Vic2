# The HFM Enhanced Series (MP) - Changelog

## This mod is built on HFM V1.27I (SighPie) and HFM More Stuff V3.5 (u/louisky58) submod.
**Credit:**
- Infamy reduction depending on rank & healthcare changes inspired by Heirs to Aquitania (Savs)
- Population size effects, final tech row, and LGLC tax moddifiers inspired by PDM Divide by Zero (GAGA Extrem)
- Population growth decision and conditions UI changes taken from The Grand Combo (Jman & others)
- Unciv rework from Harolds Triumph (Atlas), built from PUIR (Reno)
- Revanchism buffs taken from PUIR (Reno)
- Generals UI change, Trade Agreements & Tech/Inventions and Fake War idea taken from Victoria Universalis (KevinG)
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
- No militancy gain for unenforced war goals
- Executive: Can allow executive power, options restricted via government form
- Militarization: Raises or lowers the max soldier pops per state
- UBI option for socialists & vanguardists (very high pension level)
- R&D Policy: More RP, increase via decision conditions
- Westernisation: Reforms unlock tech up to lvl 2 (and nothing else)
- Secret police reform give triggered modifiers when admin funded to reduce pop mil and con
#### Administration
- Base of 1.5% bureaucrats required for full admin efficiency from them
- Require 2% bureaucrats to state colonies
- Greatly increased admin multiplier on large social reforms
- Reduced promotion chance based on social reforms
- Can set maximum percentage of bureaucrats in all non-colonial states
#### Parties
- Anarchists: Rare, similar to socialists, successful rebels will enforce Anarchism
- Rich pops will never support socialists, communists, anarchists, and very rarely radicals
- No party loyalty loss on war loss
#### National Focuses
- Party support increased to 0.010 daily
- Assimilation NF
#### Revanchism
- Army & mob buff modifiers scale with % of revanchism (capped at 50%)
#### Releasables
- Allow almost all tags to be released from the politics tab - apart from formables with existing cores
- Exceptions (non-releasables): China (& Nationalist China), DNB, Ethiopia, Ger & GCF, Gran Colombia, PLC, Scandi, Taiping, USSA
#### Rebels
- Pan-nats disabled
- Autorise will not occur

## Population
#### Liferating & Growth
- France average life rating increase to 33
- USA starts at 40
- Will decrease over the year range to 35 LR (excluding the capital): USA 1850->1865 , GB 1880->1900 , ITA 1890->1900 , GER 1900->1920
- Will increase over the year range to 35 LR: FRA 1900->1910
- Will increase over the year range to 40 LR (if in existence): CHI, HND, IDO, INO, KOR 1910->1931
- Pop-growth techs nerfed
- Healthcare only grants +0.01% pm at top level fully funded
- Removed starting baby booms
- Slaves grow at the same rate as other pops
#### Pop Needs
- Demand increase from inventions decreased to 1% per invention
- Luxury manufactured goods in luxuries for lower and middle class
- Tea & Coffee moved into luxuries
- Removed basic food demand as luxuries (canned food instead)
#### Literacy
- Greater decay in literacy in higher literacy pops
- Low literacy nations gain 10% edu eff every 10% lit below 50%
#### Demotion & Promotion
- Reduced (~33% decrease) rate of demotion
- Greatly (+100%) increased rate of promotion
- Colonial bureaucrats % set and changed via decision
- Colonial intellectuals can be all fired
#### Assimilation
- Republics have a slight increase
- Equality NV: slight increase
- 70& lower assimilation on culture-cores with your core
- 85% lower assimilation on culture-cores without your core
- Cannot assimilate on overseas non-cores
- Can manually core any coastal province if a port is owned (UK can't core Canada & Australia until 1900)
- Can gain and remove cores faster (and remove non-existent country cores with on your plurality culture provinces with Mass Pol.)
#### Immigration
- New World buff reduces 1900+
- Attraction from reforms greatly increased
- USA buffs nerfed slightly
#### Emigration
- Life needs met effects rate
- Removed almost all culture-specific modifiers
- Republic & Con. Monarchy have very slightly reduced rates
- Fully funded UBI has a very slightly reduced rate

## Technology
#### Inventions
- Biologism 100% chance

## Economic
Overseas penalty increased to 0.025 per provinces
#### Policies
- LF now 10% output and tech buffs
- Free Trade gives 5% output and small tech buffs
#### Goods
- Copper (RGO): Used to make bronze and in electrical goods
- Combined precious metals into precious goods
- Shares: Factory supply good & used to make stocks
- Stocks: Rich middle class and upper class good
- Pharmaceuticals: Army and richer pops supply good
- Interwar Hulls: Required for aircraft carriers
#### Factories
- Bronze: Copper & Coal inputs
- Pharmaceuticals: Glass & Opium
- Banks (Shares): Paper (clerk only)
- Stock Exchange (Stocks): Paper, Shares (clerk only)
- Interwar shipyard (Interwar Hulls): Steel, Coal, Machine Parts, Bronze
- Synthetic Rubber: Oil
- Nitrate Factory (Sulphur): Coal, Iron
- Machine Parts factories built only with RGOs (incase of parts crash)
#### Tech
- Power: Grants RGO size increases
- Metallurgy: Huge output buffs
- Transport: Later techs increase max railroad to lvl 10
- Farm RGOs stop scaling with late-campaign Power and Transport tech
- Tractors province modifier requires invention tractors, not a slave or colonial state
- Mechanized Mining province modifier requires inventions machine_tools & nitroglycerin, not a slave or colonial state
- Commercial Retailers province modifier requires inventions distribution_channels & electrical_lighting, not a slave or colonial state
#### Infrastructure
- Railroad: Max lvl increased to 10, effects per railroad lvl buffed (RGO output & factory throughput)
- Naval Bases: No longer give navy cap, max lvl increased to 8

## Diplomacy
Peacetime mob disabled
#### Infamy
- Base decay at peace and war increased to -0.15 monthly
- SP lose an additional -0.02 monthly
- Neither GP or SP, but westernised gain -0.05 monthly
- Uncivilised lose an additional -0.2 monthly (scaling to -0.1 as they reach half-westernised)
- Afircan uncivs gain an additional -0.2 monthly (scaling to 0 as they reach 70% westernised)
#### CBs
- Great Wars locked until 1900
- Can add war goals on puppets
- Justify 'fake' overlord war in order to add CBs on puppets
- Take capital & minor conquest added
- Liberate and puppet, and steal puppet CBs added
- Military access CB (~week justification), the war is the access
- Mass conquest if a dictatorship form with Mass Politics
- 10 infamy demand chinese concession (East Asia countries need breech loaded & naval statistics, everyone else needs machine guns & naval logistics/be Russia/be Iran)
- Radical republics and Absolute monarchies can enforce gov types on the other gov type
- Jihad CB for unwesternised sunni against infidels
#### Warscore
- Acquire state/substate cost ~27-33
- Acquire core/substate core cost ~14-17
- Place in the sun ~10
- Chinese concession ~21
- Non-Chinese concession ~14-17
- Free people / allied core ~21
- Monroe doctrine / Oriental crises ~14
- Chinese/Indian Reunification ~5
#### Truces
- GW truce is 8 years
- Independence truce is 10 years
- Military access truce is 1 year
- Trucebreaking gives 0 militancy
- Trucebreaking gives 5 infamy
- Trucebreaking gives -100 prestige
#### Relations
- Nothing costs diplo points aside from increasing/decreasing relations
- No prestige cost to dishonouring calls

## Military
War score from battles is capped at 25
No war exhaustion hit on rebel occupations
War subs pay for 100% of mil goods
Fort effects doubled
#### Units
Soldier pops concentrate in state capitals, requires 3k soldier pops for 1st brigade (then 5k onwards)
- Bombers: 'Attack version' of planes (fighters)
- Guards: Have recon (less than hussars)
- Aircraft Carriers: Long range, high attack, mid hull
- Dreadnoughts: Scale better with tech
- Cruisers: Require small amount of oil to build, cannot build overseas
- Submarines: Torpedo attack & high evasion
- Irregulars start unlocked for all
- Siege units effects doubled
#### Tech
All units will immediately unlock when conditions met
- Heavy Armament: Greatly buffed artillery attack
- Light Armament: Gives Infantry & Guard discipline increases
- Submarines scale greatly with 1900+ tech
- Gas attack is reduced to 1, no defence, taken via decision
- Navy speed will not benefit sail ships in the steam era onwards
- Army Leadership gives increased mil tactics 
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
German states only get all German cultures on forming Germany
#### Europe
- UK: Can revolt to the UFB, can keep Irish accepted, annexes the EIC at the start 
- FRA: Can take empire flava as the Republic
- AUS: Can form SGF (and release its non German land), cannot form the GCF (removed tag), no Hungary revolt tag/war
- DNB: RnG removed & cultures now accepted via decisions
- RUS: Only cores Poland late-campaign, option to take all of Manchuria
- GER: Formed via region control (explained in unification decision) as NGF/SGF or with rev_n_counter as NGF/PRU
- ITA: Formed via region control (explained in unification decision), or with rev_n_counter and no other player with North/South Italian primary owning land not as your puppet in the region
- Ottos: Tanzimat reforms can be completed as a republic & Arab revolt won't remove or stop getting accepted cultures
- NET: Starts with Indonesian puppets annexed, and can quickly annex Aceh and Jambi
- POR: Can unite with Brazil to form the UPB
#### Americas
- USA: Manifest Destiny unlocks CB for USA & Mexico, Monroe Doctrine CB
- Mexico: Can accept Centeral American
- Gran Columbia: Carribean expansion ability
- Brazil industrial RGO change decisions later-campaign
#### India
- EIC if independent can form India
- Decolonisation RGO changes
#### East Asia
- Qing collapses with 2 miltancy and non conservative/reactionary party, or if it is a republic
- China surviving the Warlord Era can accept all Chinese cultures
- JAP tag will annex all independent primary Japanese (not TKG) tags who aren't at war automatically if TKG puppetted/destroyed
- JAP will gain the cores of TKG if TKG doesn't exist
#### Oceania
- Australia can form Oceania, with small expansion flava

## Map
- Rivers with -2 crossing plenlty added (province modifier label)
- German provinces smoothed
- Redrawn Trieste area & West Switzerland
#### Straits
- Vanilla straits added (Dover-Calais, Japan-Korea)
- Hormuz & Carribean straits
#### Canals
- Copenhagen Canal (controlled by Copenhagen) with straits access across the islands
- Gibraltar Straits operate as a canal with two control provinces: Gibraltar, Ceuta
- Both Gallipoli and Golden Horn act as control canals
- Aden Strait acts as canal
- Indonesian 'canal' system controlling access from internal (north) sea to external (southern) sea from Singapore to Dili

## AI
- AI now weighted to build meta stacks
- High priority to take key techs (Medicine & Military Directionism)
- Enthusiasm for bad focuses set to 0
- Aggressiveness massively increased

## MP Support
#### GM Decisions
- Can transfer GM country
- Ally everyone
- Seige and unseige countries
- Immediately kick players
- Can separately disable land transfers, infamy transfers, and trade deals (and renable them all separately)
- Can switch players / GM nation
#### Grants
- Standard Money Transfer options
#### Infamy Transfers
- Like grants, but limited to GPs or capital on the same continent
- Take for ally CBs
#### Land Transfers
- State
- State (3rd party)
- Substate
#### Sanctions
- 1st level sanctions apply at 32.5 infamy
- 2nd level sanctions apply at 40 infamy
#### Puppet Units
- Can start a fake war to regain control over all puppet units
#### Event removal
- Many events removed that so little