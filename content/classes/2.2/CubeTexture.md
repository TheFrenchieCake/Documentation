---
ID_PAGE: 25220
PG_TITLE: CubeTexture
PG_VERSION: 2.1
TAGS:
    - BaseTexture
---
##Description

class [CubeTexture](/classes/2.2/CubeTexture) extends [BaseTexture](/classes/2.2/BaseTexture)



##Constructor

##new [CubeTexture](/classes/2.2/CubeTexture)(rootUrl, scene, extensions, noMipmap)

Create a new [CubeTexture](/classes/2.2/CubeTexture). Used to create a new skybox.
A tutorial about cube textures  can be found here : https://github.com/BabylonJS/Babylon.js/wiki/15-Environment

####Parameters
 | Name | Type | Description
---|---|---|---
 | rootUrl | string | 
 | scene | [Scene](/classes/2.2/Scene) | 
optional | extensions | string[] | 
optional | noMipmap | boolean | 

##Members

###url : string

The texture URL

###coordinatesMode : number

The coordinates mode

##Methods

###clone() &rarr; [CubeTexture](/classes/2.2/CubeTexture)

Clone the cube texture
@return [CubeTexture](/classes/2.2/CubeTexture) A clone of the cube texture
###delayLoad() &rarr; void

Delay the texture loading
###getReflectionTextureMatrix() &rarr; [Matrix](/classes/2.2/Matrix)


