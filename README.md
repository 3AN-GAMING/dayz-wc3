# WC3 DayZ map making

## TO DO LIST

*  - [x] Humanity system do vJASS
*  - [] Blood system convert to Health system
*  - [] Multibars multiboard hud system
*  - [] Dodělat gun system a přidat modely a zvuky
*  - [x] Převést hotwire kit & respawn token
*  - [x] Předělat hero select na Gender select
*  - [] Dodělat itemy
*  - [] Přidat druhý granát do hry a optimalizovat patch *20.1*
*  - [x] Spínačové systemy - Humanita , Krev
*  - [x] Hlad Proměnné

# Patch Notes 18.1

* Systém humanity převedený na MUI GUI systém , takže je ready pro multiplayer.
* Dospínačování blood money a lost civil wallet

# Patch Notes 19.1 (upload at 22 00 cca)

* Převedení systém hladu a žízně do přikazové verze
* Optimalizace Granátů do itemů (sg01, grenade01)

# Patch notes 19.1 a1 

* Optimalizace radio zóny , dospínačování
* raw meat , hunger system + další itemy kolem hunger / thurst systemu

# Patch notes 21.1 a1

* Zrušení tlačítka alt , už nelze vidět HP.
* statistiky převedeny do multiboardu

| Player Name  |    |
| ------------- | ------------- |
| Blood  | Blood_int  |
| Humanity  | Humanity_int  |
| Kills  | Kills_int  |


![Image of Yaktocat](https://ctrlv.cz/shots/2018/01/21/p35n.png)

### Předměty dotvořené :

* Raw meat
* apple
* Chips
* blood bag
* canned fish
* canned beans
* life token

# Patch notes 23.1 a1

* Přidány airdropy (jass)

![screenshot](https://ctrlv.cz/shots/2018/01/23/JpS1.png)

* Přidány dodatečné itemy k jídlu a pití 
* Optimalizace proměnných
* Přidán item - Life token (funkční)

# Patch notes 23.1 a2

* Odstraněný leaky z mapy


# Patch notes 25.1 a1

* ## Item list done

| Item name  |   + blood | + hum | + hunger | + add efeect
| ------------- | ------------- |---|---|---|
| meat  | 300  | 0| 10|none|
| chips  | 300  | 0| 10|none|
| apple  |  300  | 0| 10|none|
| bloodbag  | 300  | 0| 10|none|
| canned fish  |  300  | 0| 10|none|
| beer  |  300  | 0| 10|none|
| baned beans  |  300  | 0| 10|none|
| lost civil wallet |0| -100|0|none|
| blood money | 0| -100|0| none|

* ## Air drop system

* timing : 1 per day at *20:00*

* ## Loots 

| air drop name | obsah | 
|---|---|
| military | zbraně , naboje , armory, vybaveni |
| food | jidlo atd.. |
| base building | nabytek , crafting potřeby |
| medic drop | bbčka , atd atd.. |

* ## Gun system 

| Name | Typ | Ammo | fireRate | Reload time | Damage human | Damage Zombie | Damage vehicles| Range |
| --- | --- | --- | --- | ------ | --- | --- | ---| --- |
| Mauser Red C96 | xxx |  xxx |  xxx |  xxx |  xxx |  xxx |  xxx | xxx |
| Chainsaw | xxx |  xxx |  xxx |  xxx |  xxx |  xxx |  xxx  xxx |
| Baseball with nails | xxx |  xxx |  xxx |  xxx |  xxx |  xxx |  xxx | xxx |
| Vintorez | xxx |  xxx |  xxx |  xxx |  xxx |  xxx |  xxx | xxx |
| PDW | xxx |  xxx |  xxx |  xxx |  xxx |  xxx |  xxx | xxx |
| Machette | xxx |  xxx |  xxx |  xxx |  xxx |  xxx |  xxx | xxx |
| Hammer | xxx |  xxx |  xxx |  xxx |  xxx |  xxx |  xxx | xxx |
| Baseball | xxx |  xxx |  xxx |  xxx |  xxx |  xxx |  xxx | xxx |
| Sledge hammer | xxx |  xxx |  xxx |  xxx |  xxx |  xxx |  xxx | xxx |
| Revolver | xxx |  xxx |  xxx |  xxx |  xxx |  xxx |  xxx | xxx |
| RPG-7 | xxx |  xxx |  xxx |  xxx |  xxx |  xxx |  xxx | xxx |
| Molotov | xxx |  xxx |  xxx |  xxx |  xxx |  xxx |  xxx | xxx |
| Makarov | xxx |  xxx |  xxx |  xxx |  xxx |  xxx |  xxx | xxx |
| MK48 | xxx |  xxx |  xxx |  xxx |  xxx |  xxx |  xxx | xxx |
| M9 | xxx |  xxx |  xxx |  xxx |  xxx |  xxx |  xxx | xxx |
| M40A3 | xxx |  xxx |  xxx |  xxx |  xxx |  xxx |  xxx | xxx |
| M240 | xxx |  xxx |  xxx |  xxx |  xxx |  xxx |  xxx | xxx |
| Grenade | xxx |  xxx |  xxx |  xxx |  xxx |  xxx |  xxx | xxx |
| Gold plated revolver | xxx |  xxx |  xxx |  xxx |  xxx |  xxx |  xxx | xxx |
| g17 | xxx |  xxx |  xxx |  xxx |  xxx |  xxx |  xxx | xxx |
| bizonSD | xxx |  xxx |  xxx |  xxx |  xxx |  xxx |  xxx | xxx |
| colt 1911 | xxx |  xxx |  xxx |  xxx |  xxx |  xxx |  xxx | xxx |


* ## Recipes

* ###*list*

| item crafted name | items needed | 
| ---|---|
| 01 | xxx |
| 02 | xxx |
| 03 | xxx |
| 04 | xxx |
| 05 | xxx |
| 06 | xxx |
| 07 | xxx |
| 08 | xxx |
| 09 | xxx |
| 10 | xxx |
| 11 | xxx |
| 12 | xxx |
| 13 | xxx |
| 14 | xxx |
| 15 | xxx |
| 16 | xxx |
| 17 | xxx |
| 18 | xxx |

# Patch notes 25.1 a2

* *added items*
* *teren*

# items drop list

### items

# * 1 - Zelená ( The Toys ) 0-1000  40%
* Brick - Cihla
* Cement - Cement
Pepsi Cola
Wood Logs - dřevo
Toilet papper  - toaletní papír
Apple - Jablko
Jerry Can -  Benzín
Meat- Maso
Matchbox - Sirky
AMMO1- 12Gauge
AMMO2- 9mm
AMMO3- 5,56mm
Chips- Chipsy
Scrap metals - šrot
Nails- hřebík
Canned Fish 
2 - Tmavě modrá (Better than nothing) 1001-2000 25%
Wooden Fence - Dřevěný plot
Toolbox - Nařadí
Cynder wall
Colt python
Lee enfield
Mauser Red C96- zbraň
338 lapua magnum ammo
Haloogen - halogen
Remington
Baseball- Basebolka
Bandage - Bandáž
Rope- Lano
Double barell shotgun
Bulp - žárovka
Machete
Eletric Cabels
3 - žlutá  (Pay to Survive) 2000-2500 15%
Brick Wall - Cihlová zeď
AUG
M4A1 MOD
Wheel - kolo
Spray "Red"
Spray "Green"
Spray " Blue"
Mountain dew
Pump shotgun
Civil Wallet- Civilní peněženka
Mountain dew
Polyester- Plast PVC
Transformator - Transformator
Car Battery- Akumulator
Smoke
Briefcase
4- hnědá (STALKER) 3000-4000 10%
Bronze - Bronz
Deser Eagle
Compost- Kompost
Box- krabice
Lamp-Lampa
Speedometer
Bush- Keř
Gold bar
P90
HEGrenades ammo
M14
Silver bar
Bumper - narazník
Land mine - Mina
Bear trap
Fish net trap - Past na ryby
Citrine
Car radiator - Radiator pro auta
Sapphire
5 - Růžová (Psychopath tools) 4001-8000 4%
NV Googles - Noktovizor
Teddybear - Medvídek
MP-40
Transmitter- Vysílačka
FN FAL
Kevlar- Vesta
M4A1 SOPSD 
Obsidian - Obsidian
Amethyst
Military radio - Radio
Peridot
Diamond
Silver Bullet - Stříbrné kulky
Specimen 13 - Exermplář 13
REBEL CLOTHES
AK47-Goldplated
AK47-Silver Plated
AK47-Nightmare
6 - Světle modrá (Insane Survival)  9000-12000 3%
Megaphone - Megaphone
Parkour Book- parkourova kniha
Canadian Boots - Kanady
Krasnodar's Biomask
Amethyst
Sentry Gun
L115A3 SD
Emerald
Ruby
KSVK
AK47- Husky
AK47SD- Luccawear
AK47SD - Collosus
AK47- Jasmine
AK47- Brasilia
7 - Červená (Ancient Predator's ) 12001-18000 2%
NATO Medkits
Minigun for car - minigun do auta
Uranium - Uran
Ghillie Suit - heykal
Kransodar sniper Clothes
Bandit Clothes
Garnet
AS50
Zirkon
Ak47 - Bomberman
AK47 - D00M
AK47- Madness
BloodBag
8 - Bílá (The Silence of the Lambs) 18001-? 1%
Palladium Ore - Palladium
Hotwirekit- hotwirekit
Lock - zámek
Blackmarket Hummer
Life Tokken 
Opal
AK47-Rainbow
Radar
DMR SD
M32

