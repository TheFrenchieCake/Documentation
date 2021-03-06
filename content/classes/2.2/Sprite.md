---
ID_PAGE: 25305
PG_TITLE: Sprite
PG_VERSION: 2.1
TAGS:
    - Sprite
---
##Description

class [Sprite](/classes/2.2/Sprite)



##Constructor

##new [Sprite](/classes/2.2/Sprite)(name, manager)

Create a new [Sprite](/classes/2.2/Sprite).
A tutorial about sprites can be found here

####Parameters
 | Name | Type | Description
---|---|---|---
 | name | string | 
 | manager | [SpriteManager](/classes/2.2/SpriteManager) | 

##Members

###name : string

The sprite name

###position : [Vector3](/classes/2.2/Vector3)

The sprite position

###color : [Color4](/classes/2.2/Color4)

The sprite color

###width : number



###height : number



###angle : number

The sprite angle

###cellIndex : number

The index of the cell

###invertU : number

True if invert in U axis ; False otherwise

###invertV : number

True if invert in V axis ; False otherwise

###disposeWhenFinishedAnimating : boolean

True if dispose when finished animating ; False otherwise

###animations : [Animation](/classes/2.2/Animation)[]

Animations array

###size : number

The sprite size

##Methods

###playAnimation(from, to, loop, delay) &rarr; void

Function to play the sprite animation

####Parameters
 | Name | Type | Description
---|---|---|---
 | from | number | 
 | to | number | 
 | loop | boolean | 
 | delay | number | 

###stopAnimation() &rarr; void

Function to stop the sprite animation
###dispose() &rarr; void


