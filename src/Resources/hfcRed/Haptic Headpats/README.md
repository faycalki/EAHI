# Haptic-Headpats
[![Generic badge](https://img.shields.io/badge/Unity-2019.4.31f1-informational.svg)](https://unity3d.com/unity/whats-new/2019.4.31)
[![Generic badge](https://img.shields.io/badge/SDK-AvatarSDK3-informational.svg)](https://vrchat.com/home/download)
[![Generic badge](https://img.shields.io/badge/License-MIT-informational.svg)](https://github.com/hfcRed/Haptic-Headpats/blob/main/LICENSE)
[![Generic badge](https://img.shields.io/github/downloads/hfcRed/Haptic-Headpats/total?label=Downloads)](https://github.com/hfcRed/Haptic-Headpats/releases/latest)

Prefab that will make other players controllers vibrate when giving you headpats. 
Works with both write defaults on and off.

The package uses a chair to force haptics, which means if timed correctly, players would be able to sit on your head. They will immediately be kicked off in the next frame, but it is something to keep in mind.

[Showcase](placeholder)

## Installation

[Video Guide](https://youtu.be/b-pRDLDCASk)

* Drag the "Haptic Headpats" prefab onto your avatar in the hierarchy.
* Open up your avatars armature to find the head bone.
* Drag the head bone into the parent constraint of "Haptic Headpats".
* Open up "Haptic Headpats" and select both "Receiver" and "Haptics" to move them up into your head.
* Adjust the radius of the receiver to fit your head if necessary.
* Copy the "Enable Haptics" bool parameter from "Haptic Headpats FX" into your own FX parameters.
* Create a new layer in your FX controller and copy and paste the content of the "Haptic Headpats FX" layer into it.

## Download

You can get the latest version of the Haptic Headpats in [Releases](https://github.com/hfcRed/Haptic-Headpats/releases/latest).

## Support

If you encounter any problems or need help with the package dont hesitate to shoot me a message on Discord:
Red#1832

## License

Haptic Headpats falls under the [MIT License](https://github.com/hfcRed/Haptic-Headpats/blob/main/LICENSE) and is free to use and redistribute.
