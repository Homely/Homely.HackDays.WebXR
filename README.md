# Basic WebXR Demo

----------------------------

### Concept:
Add WebXR (VR/AR/MR) capabilities to web app.


### Rationale:
Provide better insight of a listing by showing a 3D model than just photos.


### Scope:
Show a basic 3d house embedded in a web app.

### New technology used:
aframe, three.ar, aframe-ar, glTF, glitch

Demo:
<https://homely-hackdays-webxr.glitch.me/>

----------------------------
## Background:

WebXR == VR/AR/MR

<https://blog.bixlabs.com/webvr-a-glimpse-a6cb31d7514d>
<https://developer.oculus.com/webvr/>

Demos:
airbnb

<https://www.youtube.com/watch?v=8M7DhNEQcfs>


----------------------------
## Steps:

Create 3d scene:
1) Show in browser
2) With a model
3) Using mobile AR/VR


# Step 1: Show in browser
----------------------------

#### aframe
web framework for building virtual reality experiences.

<https://aframe.io/>
<https://github.com/aframevr/aframe/>
<https://github.com/aframevr/awesome-aframe>


###### Notes:

Inspect Mode:

`Ctrl + Alt + I`

Embed:

`<a-scene embedded class="aframe"></a-scene>`
<https://aframe.io/docs/0.3.0/components/embedded.html>
<https://tengio.com/blog/bringing-vr-to-the-web-a-frame/>


# Step 2: With a model
----------------------------

#### Types:

* dollhouse (AR)
* full house (VR)


#### Format: 

* GLTF
<https://github.com/aframevr/aframe/blob/master/docs/components/gltf-model.md>


#### Providers:


#### Sketchfab
Guide: Create a simple A-Frame scene from Blender models found on Sketchfab

<https://github.com/WebVRRocks/webvrrocks/issues/50>

##### Non-downloadable examples:

* House # 1
<https://sketchfab.com/models/8034a5c4bca64e57913519bed0eb7cfe>

* Kitchen # 2
<https://sketchfab.com/models/d4b8066f357244ae9fc2433ef2f5ddd4>

* Elliot's apartment - Mr Robot - Archilogic
<https://sketchfab.com/models/81f6a4894f3e48f29bc6eea7bed7d656>

* Ultramodern house with interior/exterior
<https://sketchfab.com/models/6dec53007a5c4c97a896d1a5b5bec754>

* House in context of neighbourhood (LA)
<https://sketchfab.com/models/cc2f212f3200476292c49c2d574ce01e>

* Interior + exterior
<https://sketchfab.com/models/845b9968f599409daadf40bc510b981a>

##### Downloadable examples:

* Modern Office
<https://sketchfab.com/models/45c73e4d033d4bb5bf7139d57f36d8c5>

* Low Poly House (cute!)
<https://sketchfab.com/models/f58917bb2e614d1d80066bed8d8075a3>

* Creepy old house
<https://sketchfab.com/models/e1f959bd85764753bcd3ee2ae86f79fd>

* Simple old multi-storey house
<https://sketchfab.com/models/c7fc9c288a8b470a8482f7347a2d40ca>

* Metal Tower with animated roller shutters
<https://sketchfab.com/models/a972a15421a942429f1279824e00c042>




#### Matterport

basic integration

<https://try.matterport.com/virtual-reality/webvr/>

<https://developers.google.com/web/showcase/2017/matterport>

<https://matterport.com/blog/2017/07/27/matterport-expands-webvr-beyond-daydream-include-majority-android-devices/>


#### 3d.io
interior 3d maps

<https://3d.io/>

<https://3d.io/docs/api/1/aframe-components.html>

<https://archilogic-com.github.io/3dio-inspector-plugins/>

<https://3d.io/use-case/designer-portfolio-augmented-vr.html>

<https://3d.io/use-case/virtually-staged-3d-scan.html>

Real Estate Virtual Tour using A-frame and 3d.io

<https://www.youtube.com/watch?v=3nzl9zKbFGs>



# Step 3: Using mobile AR/VR
----------------------------

Mobile VR:
---------

A WebVR Workflow for A-Frame, from GearVR to Vive

<https://medium.com/@flimshaw/a-webvr-workflow-for-a-frame-from-gearvr-to-vive-2c47ae823810>

#### Oculus browser
Oculus browser is designed from the ground up to be the best web browsing experience in VR. 

<https://www.oculus.com/experiences/gear-vr/1257988667656584/>

----------------------------

Mobile AR:
---------

##### Marker:
* tracking for older phones.

#### AR.js - Efficient Augmented Reality for the Web

<https://github.com/jeromeetienne/AR.js>
<https://medium.com/arjs/ar-js-supports-tango-on-a-frame-too-2c098de4df34>
<https://aframe.io/blog/arjs/>

Demo:

<https://arexp.glitch.me/torus-knot/>

##### Markerless:
* Tracking for new phones (S8/iPhone 8)

#### WebARonARCore/WebARonARKit
An experimental Chromium modification in the form of an app for Android that lets developers build Augmented Reality (AR) experiences using web technologies on top of Google's ARCore.

<https://developers.google.com/ar/develop/web/getting-started>
<https://github.com/google-ar/WebARonARCore>

Home staging AR Demo
This demo let's you draw a floor plan in AR and then furnish it automatically.

<https://github.com/archilogic-com/3dio-js/tree/master/examples-browser/staging/stage-room-ar>

#### aframe-ar
Basic A-Frame support for the new three.ar.js library and WebARonARKit / WebARonARCore browsers.

<https://github.com/chenzlabs/aframe-ar>




# Future
----------------------------

#### Map
##### MapBox 
3d mapping integration

<https://blog.mapbox.com/mapbox-gl-js-ar-js-a-frame-vr-mapbox-ar-vr-93c09be08742>


#### React
* aframe-react