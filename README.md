# Hello world xrfragments

<img src="https://xrfragment.org/example/assets/logo.png" width="30%"/>

Auto-Hosted XR Fragment-compatible XR viewer
<br>

## Getting started:

* download `index.glb`
* edit in your favorite 3D editor (blender e.g.), and play with the [embedded properties](https://xrfragment.org/#%F0%9F%93%9C%20XR%20fragments) of objects (`custom property`-tab in blender)

<img src="https://i.imgur.com/Y8k9JL5.png"/>

* familiarize yourself with XR Fragments using [these youtube video's](https://www.youtube.com/playlist?list=PLctjJGlTmeE64XPSQER2BSbjmqVGaWM4J) and the [documentation](https://xrfragment.org)
* create/update/add gltf/fbx/stl/uszd) models (and link them using `href` or `src`, see below)

>  see [embedded properties](https://xrfragment.org/#%F0%9F%93%9C%20XR%20fragments) 

## Quick testing

To test modifications quickly, click the 'load 3D asset'-button in the [sandbox](https://xrfragment.org/example/aframe/sandbox) after pressing the XRF-button:

<img src="https://i.imgur.com/WTzbLwh.png"/>

##  Publishing to the web

* Press the fork button, and it will automatically host an experience at your own URL
* in the github 'Actions'-tab figure out the url(`https://yourusername.github.io/xrfragment-helloworld` e.g.) and visit it
* profit!

> now upload more `.glb` or `.gltf` files (`new.glb` e.g.):

<img src="https://i.imgur.com/MsmZJDQ.png"/>

In another scene (`index.glb` e.g.) link to that asset (`new.glb`) by selecting an object in blender, and add a custom `href` property to it:

<img src="https://i.imgur.com/smkwHYv.png"/>

Or if you want to embed a scene into another, use `src` instead of `href`

> Profit! now you can click/teleport from one scene to another! (see the docs at [xrfragment.org](https://xrfragment.org) for more features)

#### Selfhosting (only advanced users)

If you don't like free hosting, then you can selfhost as well:

* https://github.com/coderofsalvation/xrfragment-aframe-helloworld
* https://github.com/coderofsalvation/xrfragment-three-helloworld

> More info 

* [XR Fragments github](https://github.com/coderofsalvation/xrfragment)
* [XR Fragments website](https://xrfragment.org)
