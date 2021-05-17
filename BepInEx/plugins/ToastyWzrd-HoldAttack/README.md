#Hold Attack

With this little BepInEx plugin you can mine ore, cut wood and even fight with more comfort than ever. Say goodby to button mashing and hold down the attack key (or don't press anything at all).

##Configuration

You can configurate key bindings to toggle the mod (default: H) and to keep attacking without pressing the attack button (default: None). For key naming conventions look at https://docs.unity3d.com/ScriptReference/KeyCode.html
You can also adjust a delay (the number of FixedUpdates) before the attack is activated again. Decrease this if you are experiencing a pause between attacks. Optionally the delay can be set for each weapon. This is useful if you use custom animation speed.

##Installation

To install the mod you need to extract the contents of "plugins" folder into "<GameDirectory>\Bepinex\plugins".
The configuration file "Toawy.HoldAttack is generated after you start the game once.

##Changelog

0.4.2
- Fixed multiplayer for real this time
- No more errors
- KeepAttacking gets disabled when attacking manually

0.4.1
- Fixed Chat messing up the key bindings
- Hopefully fixed multiplayer
- Changed the default setting for KeepAttackingKey to None
- Now using new key naming convention: https://docs.unity3d.com/ScriptReference/KeyCode.html

0.4.0
- Added key binding to toggle attacking witout pressing the attack button (default: k)
- Added ability to disable key bindings (set them to none)
- Changed default ToggleKey binding to "h"

0.3.0
- Added key binding to toggle on and off (default: left alt)

0.2.2
- Added Nexus Update Check integration
- Added configurable delay (for custom animation speed support)