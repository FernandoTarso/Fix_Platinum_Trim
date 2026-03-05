This is a client fix for the https://github.com/Fuzss/illagerinvasion mod, specifically version 1.21.1, 
but it should work for any version where this happends, if there are any others.

The issue is that the flow armor trim doesnt load in. This happens because the armor_trims.json was lacking
that pattern, all this does is add it as well as bolt pattern (idek that one, but it seems it was missing too).

All that is needed is to extract the Fix_Platinum_Trim-main folder on the minecraft\resourcepacks folder 
of the game instance, and enableing it in-game. That is done though home/pause menu: options > resource packs >
Select it on the left side.

It should work to do the same process server side, but I didn't test it yet.
