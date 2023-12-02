# Front-End Scaleform Movies
### Using `PushScaleformMovieFunctionN`
These are all implying the use of the Blip Info popup front-end, `frontend = 65`, `layer = 1`

All of these are based on their usage in decompiled scripts

## SET\_DATA\_SLOT\_EMPTY(`int layer`)
`layer` seems to always be `1`

Clears all the data slots from the specific layer

## DISPLAY\_DATA\_SLOT(`int layer`)
`layer` seems to always be `1`

This function will show changes made to the front-end, changes are not shown unless this is used.

## SET\_DATA\_SLOT(`int layer`,`int index`,`int frontend`,`int unk0`,`int slotType`,`int unk1`,`int unk2`)
`layer` seems to always be `1`

`index` controls the slot position you're assigning data to

`frontend` appears to control which frontend you're manipulating

`slotType` defines the appearance of the slot (range `1-5`)


## SHOW\_COLUMN(`int layer`, `bool show`)
`layer` parameter appears to be the front-end layer. `1` is always used, `0` appears to modify other HUD elements, such as the map legend.

`show` parameter enables or disables the `layer`

# Other Stuff
## AddBlipInfoIcon Icon Number's

    0 - Star
    1 - 1 Skull
    2 - Flag Icon (Race)
    3 - Shield Icon
    4 - 3 Skulls
    5 - Blank
    6 - Cassle Icon
    7 - Blank
    8 - Pacachute Icon
    9 - Car Crash icon
    10 - Flag With Car
    11 - Flag with Person
    12 - Flag with Bike
    13 - Flag with Boat
    14 - Flag with Plane
    15 - Last Team Standing Icon
    16 - Case Icon
    17 - Heist Setup
    18 - Heist 
    19 - Flag with Ramp?
    20 - Watch Icon?
    21 - Wheel on fire?
    22 - Money Icon on fire?
    23 - Last Team Standing VS Icon?
    24 - Flag with scope?
    25 - Flag with gear?
    26 - Crown Icon
    27 - RC Car Icon with Timer
    28 - F1 Icon
    29 - Flag with Shield Icon
    [30 - Infinity] - Flag with LS Car Meet Icon 