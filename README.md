# TaaprWareV2

This is an open source roblox executor with a custom DLL made in C++, and a UI made in C#.

Discord (better exploits soon): https://discord.gg/nAEHrW9EF9

This exploit helped me get from C++ hello world programs to real Luau function recreation for Roblox and finding offsets, expect it to be messy.

With a few edits, you can get execution working with only these addresses and no offets: rbx_getscheduler, rbx_addscript, rbx_runscript, rbx_deserializer_detour and rbx_deserializer_detour2
Or, for the bare minimum (localscript level, no custom bytecode) rbx_getscheduler and rbx_runscript.

The framework of custom functions was also done with very few addresses, needing only rbx_writevoxels, rL->top, and rL->base.

This exploit is good for beginners who want to experiment with custom functions without finding every offset in existence.

If you need help with addresses or offsets, join the Discord and I will help you.
