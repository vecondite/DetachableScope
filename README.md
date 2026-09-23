A fork of my [DetachableSilencer](https://github.com/vecondite/DetachableSilencer) mod that is focused on detaching scopes from snipers rather than silencers from pistols.

<img width="800" height="450" alt="ezgif-827d86fe3be57c9a" src="https://github.com/user-attachments/assets/07740474-a90a-488a-9593-f5a43570fd11" />

> [!WARNING]
> Contributors needed! I am unfortunately not able to add controller support as I do not have a controller at hand. If anybody does, and has some knowledge of plugin-sdk modding and controller-handling, please make a pull-request or contact me with one of the methods at the very bottom of this README. Thanks! and have fun!

Installation
---
Drop the modloader folder to the root folder of GTA:SA.
If you're using Immersive Weapons Pack by pedrowav, make sure to go to the "(optional - immersive weapons pack by pedrowav)" folder and read the readme there.

config.ini
---
- keybind: the keybind to attach/detach the scope.
- cheatcode: the cheatcode that can be used to refresh the configuration. (old cheatcode has to be used to refresh!)
- boneid: the bone id that the scope model is attached to.
- x,y & z offsets: the offsets of the scope model from the fingers.
- ifp: IFP file of the switch animation.
- anim: Anim name of the switch animation.
- animDuration: Duration of the anim. (After how long the scope model is deleted)
- animSpot: When the scope model is attached to the gun.
- scopeModel: The model id of the scope model.
- scope: a field that is used to save whether the player has a scope or not.

CREDITS:
---
> Distributed as FOSS under the MIT license.
- Me (vecondite): The mod itself.
- metayeti: [INI Library](https://github.com/metayeti/mINI).
- Dryxio: [Animation Editor](https://gtastuff.com/tools/ifp-editor).
- LINK2012: Injector (hooking) library.
- pedrowav and the Immersive Weapons Pack team: The immersive weapons pack models.
- Gemini: Minor bug fixes.

Need Help?
---
- @vecondite on Discord
- vecondite on libertycity
- vecondite on github
