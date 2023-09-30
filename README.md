# Stellr's ASL Combo Gestures
[![Github All Releases](https://img.shields.io/github/downloads/StellrVR/stellrs-asl-combo-gestures/total.svg)](https://github.com/StellrVR/stellrs-asl-combo-gestures/releases/latest)

A simple Unity package for ASL using combination gestures.


# What's Included?
- A folder of animations used in the gestures animation controller
- A Gestures animation controller
- How To Guide


# Hand Shapes Used In Controller
- F
- R
- I
- K
- X
- 8
- E
- ILY
- W
- G
- B
- Flat O
- Bent V

# Hand Shapes Included in Folder
- IRLY
- U

*Want more hand shapes? Visit my other GitHub page for 63 more animations! https://github.com/StellrTravels/vrchat-asl-handshapes*

*If you want to change the hand shapes, you can drag and drop the animations into the animation states in the controller.*


# How To Add Combo Gestures (in case you don't read the guide included):
1. Drag and drop the Gestures animator controller into the Gestures slot in your avatar descriptor.
2. Add "CopyGesture" and "SignToggle" bool parameters to your avatar's parameters.
3. Add "Copy Gesture" and "Sign Toggle" menu options as a Toggle in your avatar's Expressions Menu
4. Profit


*Note: Not every avatar's hands will look nice with this package, so you will need to adjust the animations accordingly to your avatar.*

(Some animations and setup script for the animator controller made by SaikoArt_Finn)
(https://saikoartfinn.gumroad.com/l/lbSUY)

# Common Problems / Fixes
**My left hand is not copying the same handshape as my right hand.**
1. You must have "CopyGesture" as a Bool parameter in your avatar's Expression Parameters

**The sign hands are not working at all.**
1. Ensure that you have the "SignToggle" Bool parameter in your avatar's Expression Parameters, as the sign animations are off by default.

**My hands are claws! / My hands are broken!**
1. Ensure that your FX controller does not have any animations that are for your GESTURES ONLY. This conflicts with the Gesture Controller and will cause your hands to break.
