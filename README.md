This is a client fix for the https://github.com/Fuzss/illagerinvasion mod, specifically version 1.21.1. 
~~but it should work for any version where this happends, if there are any others~~.
Testing required on other versions.

The issue is that the flow armor trim doesnt load in. This happens because the armor_trims.json was lacking
that pattern, all this does is add it as well as bolt pattern (idek that one, but it seems it was missing too).

All that is needed is to extract the Fix_Platinum_Trim-main folder on the minecraft\resourcepacks folder 
of the game instance, and enableing it in-game. That is done though home/pause menu: options > resource packs >
Select it on the left side.

Client side fix:

https://github.com/FernandoTarso/Fix_Platinum_Trim/releases/tag/v1.0

~~It should work to do the same process server side, but I didn't test it yet.~~
No fix are required on the server, but it can be suggested, by editing server.properties:

resource-pack=https://github.com/FernandoTarso/Fix_Platinum_Trim/releases/download/v1.0/Fix_Platinum_Trim.rar

resource-pack-prompt=Fix for the flow platinum trim missing texture.

resource-pack-sha1=52292479fbc3ee1fe1d33ef8fb8a1f49fdc85238
