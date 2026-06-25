---
tags:
  - vrchat
---
TODO: make page make sense
Ms paint window to partial step outwindow to partial step out of
---
### Vid's Grabbable Hue + Brightness Wheels
* [ ] Readme
* [ ] images with test robot

#### Notes 
 - This probably will break any other hue selection you have in your avatar's menus
 - I don't think you can have multiple wheels, you'd have to change a few params.
 - Don't expect any support, I just thought this was a cool thing and people wanted me to share it.
 - This guide assumes you have some VRChat/Unity knowledge. 

---
#### To Fix 
* [ ] base rotation and position
* [ ] add emissionhueshift

---
### Adding to your Avatar
You NEED the following packages added to your project through VCC:
- Poiymoi Toon: vcc://vpm/addRepo?url=https%3A%2F%2Fpoiyomi.github.io/vpm/index.json
- VRCFury: vcc://vpm/addRepo?url=https%3A%2F%2Fvcc.vrcfury.com

Min. version
Make sure they're up to date!
Gesture Manager will also help if you want to test in Unity's play mode

#### 1. Setting up materials
Do the following for each Poiyomi material on your avatar...
  - Under Color & Normals
     - Turn on Color Adjust
     - Turn on Hue Shift
     - Change Color Space to HSV
     - Right click -> 'Animate when Locked' on Hue Shift (Don't Rename!!)
  - Under Special FX
     - Under Any Emissions you use
       - Turn on Color Adjust
       - Turn on Hue Shift
       - Change Color Space to HSV
       - Right click -> 'Animate when Locked' on Hue Shift 

#### 2. Adding the wheels
* [ ] double check these 
1. Import unitypackage
2. Drag 'Color Grabbables' prefab onto the ROOT ARMATURE of your avatar
3. Rotate the 'Color Grabbables' prefab if things are weird
4. Raise the 'Color Grabbables' object above avatar's waist
5. Select the 'Wheel' object under 'Hue Wheel'
6. Rotate the Wheel object on the X axis so the triangle points to your avatar's main color.

---
### Customization
* [ ] customize notes
* There is an alternate hue wheel texture named 'Hugo', 



