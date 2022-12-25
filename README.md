# torchlight2_helper
<div align=left> 
  <img src="https://img.shields.io/badge/autohotkey-334455?style=flat-square&logo=autohotkey&logoColor=white">
  <img src="https://img.shields.io/badge/windows-0078D6?style=flat-square&logo=windows&logoColor=white">
  <br>
  <br>
</div>
This script helps the torchlight2 macro.<br>
From simple chatting to running macros that automate identify items, transmute items, enchant/disenchant items, and spam a skill per skill cooldown.<br>
In addition, gamble and fishing can be automated.<br>

* * *

### Configuration

Edit \Script Directory\torchlight2_helper.properties

```properties
LOGIN_PASSWORD=W***************************************************************
```

* * *

### How to use

`Ctrl+Shift+F1`<br>
Chat /bow

`Ctrl+Shift+F2`<br>
Chat /salute

`Ctrl+Shift+F3`<br>
Chat /dance

`Ctrl+Shift+F4`<br>
Chat /drums

`Ctrl+Shift+F5`<br>
Chat /lute

`Ctrl+Shift+F6`<br>
Chat /laugh

`Ctrl+Shift+F7`<br>
Chat /taunt

`Ctrl+Shift+F8`<br>
Chat /gunshow

`Ctrl+Shift+~`<br>
Identify all

`Ctrl+Shift+1`<br>
Move item from stash inventory

`Ctrl+Shift+2`<br>
Transmute item

`Ctrl+Shift+3`<br>
Restore shared stash

`Ctrl+Shift+4`<br>
Add enchant

`Ctrl+Shift+5`<br>
Disenchant and add enchant

`Ctrl+Shift+6`<br>
Inventory loop disenchant and add enchant<br>
```autohotkey
;Configuration examples
filterStatObj := [["+", 76]]  ;lv38 (38*0.69)28x3=84, ceil(84*0.90)75.6
filterStatObj := [["+", 111]] ;lv58 (58*0.69)41x3=123, ceil(123*0.90)110.7
filterStatObj := [["+", 152]] ;lv81 (81*0.69)56x3=168, ceil(168*0.90)151.2
filterStatObj := [["+", 184]] ;lv99 (99*0.69)68*3=204, ceil(204*0.90)183.6
filterStatObj := [["+", 187]] ;lv100 (100*0.69)69*3=207, ceil(207*0.90)186.3
filterStatObj := [["+", 195]] ;lv105 (105*0.69)72*3=216, ceil(216*0.90)194.4
```

`Ctrl+Shift+7`<br>
Inventory loop add enchant

`Ctrl+Shift+8`<br>
Transmute scroll

`Ctrl+Shift+Tab`<br>
Reroll world

`Ctrl+Shift+Q`<br>
Backup shared stash

`Ctrl+Shift+W`<br>
Backup save file

`Ctrl+Shift+E`<br>
Gamble

`Ctrl+Shift+T`<br>
Tarroch's tomb golem soul

`Ctrl+Shift+Y`<br>
Restart world

`Ctrl+Shift+A`<br>
Auto spam toggle<br>
```autohotkey
;Configuration examples
Filter examples<br>
isAutoHealthPotion := true
isAutoManaPotion := true
isAutoPetPotion := false
isAutoSkill := true
isAutoAttack := true
isDervish6 := true
isDervish5 := true
isDervish4 := true
lowHealth90Coord := [38, 522] ;90%
lowMana90Coord := [754, 522] ;90%
lowHealth66Coord := [38, 543] ;66%
lowMana66Coord := [754, 543] ;66%
lowHealth33Coord := [38, 568] ;33%
lowMana33Coord := [754, 568] ;33%
lowPetHealthCoord := [38, 10]
lowPetManaCoord := [38, 22]
skill1Coord := [251, 575]
skillXObj := []
activeskillCoord := [606, 582]
berserkerChargeCoord := [474, 508]
embermageChargeCoord := [467, 510]
engineerChargeCoord := [467, 510]
outlanderChargeCoord := [478, 516]
```

`Ctrl+Shift+S`<br>
Custom console

`Ctrl+Shift+D`<br>
Buy item

`Ctrl+Shift+F`<br>
Fish

`Ctrl+Shift+G`<br>
Sell item

`Ctrl+Shift+H`<br>
Hunt

`Ctrl+Shift+J`<br>
Custom console

`Ctrl+Shift+L`<br>
Login game

`Ctrl+Shift+N`<br>
Copy item

* * *

### Contact and license

<a href="mailto:xqbty8po-dntco43u@yahoo.com" target="_blank"><img src="https://img.shields.io/badge/yahoo!-6001D2?style=flat-square&logo=yahoo!&logoColor=white"/></a>
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
