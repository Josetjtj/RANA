# Lemmy Long Legs 2

## Controls

|Actions|Keyboard|Touchscreen|Controller|
|-|-|-|-|
|directions|arrows|arrow icons|D-pad / joystick|
|grow up|arrow up|up icon|A |
|Pause|P/pause icon|pause icon|start/select|

## How to create your own maps

### 1) Clone this project
### 2) Create a new map and change the size of the blocks.
Initially, it is displayed: Block Size `16` x` 16`. Replace it with `32` x` 32`.
##### The first map is map0, then map1, and so on. Maps with other names will not show up. 
### 3) place entities

#### inventory:

#### blocks

`blue` : solid block (you can round the corners)

`green` : one-way block,the white line shows the blocking direction

`yellow` : hurts the player

`gem blocks` : become or stop to be solid every time the player touches a gem of the same color

#### objects/upgrades

`gems` : change the state of gem blocks of the same color then disappear

`water glass` : resets the player's upgrades

`strawberry` : boosts the player's speed

`mushroom` : boosts the player's growth speed

`watermelon` :  boosts the player's gravity

`purple sign` : checkpoint

`cube` : gather them all! Can only be collected once

#### enemies

`orange duck` : no contact damage but shoots spike balls

`green duck` : no contact damage but shoots flying balls

`spike ball` : rolls, is subject to gravity, breaks when it hits a wall and make the player fall when it hits his legs

`flying ball` : slower than a spike ball, flies, go trough  walls and doesn't make the player fall

`orange character` : walks forward and turn around when it hits a wall

`yellow character` : walks forward and turn around when it hits a wall or a pit

`black character` : copy the player's movements in mirror (on the map, place any sprite except for the ghost or feet)
note: the movements might not be precise enough be used in an actual level.


#
#####
## Credits

[physics](https://microstudio.dev/i/microstudio/coronahunt/) by i/microstudio

[parallax](https://microstudio.dev/i/gilles/parallax/) by i/gilles

[car asset](https://games-in-bits.itch.io/chunky-pixel-art-car-assets) by Games in Bits

music by Baconcat008
