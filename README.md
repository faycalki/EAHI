![Logo of the project](https://i.imgur.com/ZPRZd1U.png)

# Expanded Avatar Hand Interactions
EAHI stands for Expanded Avatar Hand Interactions. EA is a framework established by Faycal Kilali (Faycal#6941) with the goal of expanding the functionality of avatars within Virtual Reality software. 

*If you like this project, please star it/favorite it in GitHub, and rate it appropriately in Gumroad / other websites where relevant.*

## Features
* More immersion! -- Other individuals' hands can now feel vibrations by touching your hands, adding to the immersion for hand interactions that involve hand touches, such as hand holding.
* Ability to high five other individuals' avatars, face, torso. 
* Ability to high five your very own avatars' hands, face, torso.
* Highly customizable! -- Boasting toggles for every feature included, sound volume adjustment, and multiple custom sound effects and visual special effects for the hand interactions.
* Easy to install! -- most integrations to avatars can be done in less than 10 minutes.
* Made with passion! -- this project is intended to spread joy, immersion, and open up more options for those seeking additional virtual social interaction ice breakers.
* Free of cost and open source under the license! -- not a single penny is needed to utilize this project, and its open for contributions as per the specifications laid down.

# Download
| Source | Link | Status |
|---|---|---|
| GitHub | [Release Candidates](https://github.com/faycalki/EAHI/releases) | [![GitHub All Releases](https://img.shields.io/github/downloads/faycalki/EAHI/total.svg)](https://github.com/faycalki/EAHI/releases) |
| Gumroad | [Release Candidates](https://faycalki.gumroad.com/) | [![Gumroad All Releases](https://i.imgur.com/VUmT2Oi.png)](https://faycalki.gumroad.com/) |

## Installing / Getting started
Video guide on integrating this Prefab to your avatar: <a  href="https://www.youtube.com/watch?v=nIs1ykJiGm0">  <img  alt="Youtube"  src="https://i.imgur.com/g1UVbZT.png"  width="100"  height="30">  </a>
1. Import VRCSDK, and whatever your avatar requires along with the avatar;
2. Import Avatars 3.0 Manager ([Download Link](https://github.com/VRLabs/Avatars-3.0-Manager/releases));
3. Import the Extended Avatar Hand Interactions Unity Package;
4. Drag prefab to the root of the avatar in the Hierarchy, then unpack the prefab, then drag all the Haptic Constrainer(s) out of the EAHI Prefab into the root avatar directory;
5. Delete the now empty EAHI Prefab in the Hierachy;
6. Drag the Left Wrist from the Hierarchy to the Haptic Constrainer's Constraint Settings that has "LH Haptics Receiver" as its child, drag the Right Wrist from the Hierarchy to the other Haptics Constainer's Constraint Settings;
7. Select all three: LH Haptic Receiver, LH Haptics, and EAHI LH Subgroup at the same time by CTRL clicking them in the Hierarchy then drag them in the scene to fit into the proper position of the left hand. Afterwards, select all three: RH Haptic Receiver, Haptics, EAHI RH Subgroup at the same time by CTRL clicking them in the hiearchy then drag them in the scene to fit into the proper position of the right hand;
8. Using Avatar Manager 3.0+, if you have Write Defaults on in your FX layer then you should combine (WD ON) EAHI FX Layer in the prefab with the avatar's FX layer. Otherwise, combine (WD OFF) EAHI Fx Layer in the prefab with the avatar's FX Layer;
9. Using Avatar Manager 3.0+, combine the EAHI Paramaters in the prefab with the avatar's parameters;
10. Add the EAHI Submenu in the unity package to your avatar's menu.
Optional step: fine tune the radius of the Haptic Receivers and the Primary Receivers to the radius you wish for them to receive feedback.

## Remarks
* You must manually enable the interactions in the menu when you load up the avatar and those you interact with must have their avatar interactions enabled;
* There are a number of sounds included, if you wish to change them then you may change the audio clips in the Sounds folder.
* Warning: if your avatar does not have Left Wrist, Right Wrist, then you will have to constraint the starter bone of the hand instead, whatever the naming scheme might be for that in your Hierarchy. For JP models its usually just "hand".
* If your avatar does not play sounds when interacting with EAHI, then ensure your avatar has at max 1 audio source active that is not EAHI. EAHI requires 2 audio source slots and VRChat only allows 3 Audio Sources to be active at any given time.

## Developing
Here's a brief intro about what a developer must do in order to start developing the project further: 

git clone the repository for the latest source code, then using Unity 2019.4.31f1 and the latest VRCSDK, edit the unity package appropriately.

## Licensing
This MIT license pertains only to the custom code and assets produced by Faycal Kilali. For licensure of the open source projects used in this software, refer to the corresponding licenses in the Resources folder.

## Contributing
All contribution requests must satisfy the main license, therefore they must also satisfy the licenses of the open source projects utilized in this project.

## Credits
Faycal Kilali for founding the project, lead development, establishment of the EA framework, and the creation of the master EAHI prefab.

hfcRed for the Haptic Headpats OSP.

FrostyFowl for testing multiple iterations, support, and providing a viable HQ SFX.

Logo art by Tammillia Winters at https://missinktrovert.com/logo-graphic-design/

## Links
Faycal Kilali (also known as Faycal#6941 in VRC and Discord) at https://github.com/faycalki 

hfcRed at https://github.com/hfcRed

- Repositories of my other projects: https://github.com/faycalki/

  - In case of sensitive bugs like security vulnerabilities, please feel free to contact Faycal Kilali whenever, I value all efforts to improve the security of the project.

## Additional avenues
<a  href="https://discord.gg/DM8jW4re6j">  <img  alt="Youtube"  src="https://i.imgur.com/ChU5TAS.png"  width="150"  height="100">  </a>