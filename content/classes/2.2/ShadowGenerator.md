---
ID_PAGE: 25210
PG_TITLE: ShadowGenerator
PG_VERSION: 2.1
---
##Description

class [ShadowGenerator](/classes/2.2/ShadowGenerator)



##Constructor

##new [ShadowGenerator](/classes/2.2/ShadowGenerator)(mapSize, light)

Creates a new [ShadowGenerator](/classes/2.2/ShadowGenerator) object

####Parameters
 | Name | Type | Description
---|---|---|---
 | mapSize | number | 
 | light | IShadowLight | 

##Members

###static FILTER_NONE : number

No filter will be used for this shadow

###static FILTER_VARIANCESHADOWMAP : number

The variance shadowmap will be used for this shadow

###static FILTER_POISSONSAMPLING : number

The poisson sampling filter will be used

###static FILTER_BLURVARIANCESHADOWMAP : number



###blurScale : number



###bias : number



###blurBoxOffset : number



###filter : number

One of the following values : FILTER_NONE, FILTER_VARIANCESHADOWMAP, FILTER_POISSONSAMPLING

###useVarianceShadowMap : boolean

True by default, defines the realtime shadowing algorithm, using the light's point of view

###usePoissonSampling : boolean

Disables the useVarianceShadowMap and activates poisson sampling to soften shadows

###useBlurVarianceShadowMap : boolean



##Methods

###isReady(subMesh, useInstances) &rarr; boolean



####Parameters
 | Name | Type | Description
---|---|---|---
 | subMesh | [SubMesh](/classes/2.2/SubMesh) | 
 | useInstances | boolean | 

###getShadowMap() &rarr; [RenderTargetTexture](/classes/2.2/RenderTargetTexture)

Defines which shadow will be rendered
###getShadowMapForRendering() &rarr; [RenderTargetTexture](/classes/2.2/RenderTargetTexture)


###getLight() &rarr; IShadowLight

Returns the [DirectionalLight](/classes/2.2/DirectionalLight) of this [ShadowGenerator](/classes/2.2/ShadowGenerator)
###getTransformMatrix() &rarr; [Matrix](/classes/2.2/Matrix)

Returns the transform matrix of this [ShadowGenerator](/classes/2.2/ShadowGenerator)
###getDarkness() &rarr; number

Returns the darkness
###setDarkness(darkness) &rarr; void

Sets the darkness with the given float between 0.0 to 1.0

####Parameters
 | Name | Type | Description
---|---|---|---
 | darkness | number | 

###setTransparencyShadow(hasShadow) &rarr; void

Defines if the light goes through the object's holes and non opaque surfaces

####Parameters
 | Name | Type | Description
---|---|---|---
 | hasShadow | boolean | 

###dispose() &rarr; void


