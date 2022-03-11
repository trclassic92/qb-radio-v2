# qb-radio
qb-radio Nopixel Inspired Radio (v2) for qb-core

# License

    QBCore Framework
    Copyright (C) 2021 Joshua Eger

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>

## Dependencies
- [qb-core](https://github.com/qbcore-framework/qb-core)
- [pma-voice](https://githubmate.com/repo/AvarianKnight/pma-voice)
- [qb-radialmenu](https://github.com/qbcore-framework/qb-radialmenu) - Optional (Access to change channels 1 - 6)

## Features
- Latest Nopixel Inspired Radio
- Radialmenu join channel option 1 - 6 (Credits - [MonkeyWhisper](https://github.com/MonkeyWhisper))
- Inventory Image [qb-radio/imgforinvenotry]

## RadialMenu Events
Add the trigger to your qb-radialmenu > config.lua (Anywhere you want someone to have access to it) for example:
```
            id = 'joinradio1',
            title = 'Channel 1',
            icon = 'info-circle',
            type = 'client',
            event = 'qb-radio:client:JoinRadioChannel1',
            shouldClose = true
```  
Credits to MonkeyWhisper for creating the event

## Images
- [Google search link to radio](https://www.aircraftspruce.com/catalog/avpages/yaesuVertexFTA750L.php)
![Preview Screenshot](https://i.imgur.com/cXjH8Rx.png)
- Preview of the radio https://www.youtube.com/watch?v=fYU_PKpAG6o

## Installation
- Replace current qb-radio with this version if you want to use it

1/12/2022 (Radio Effects)
-  To add the new radio sounds go to `\pma-voice\ui`

Inventory image - replace radio.png in your current inventory image folder with this one.

## Discord Support
- [Join Discord](https://discord.gg/zRCdhENsHG)

## Original qb-radio
- [qb-radio](https://github.com/qbcore-framework/qb-radio)
