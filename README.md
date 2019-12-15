# ProjectHSIFiles
 Project Files for upcoming development.
/// HAMMER
/// HAMMER \ 🔨
/// HAMMER is a HSI Resource System And Extractor Roblox Automated System _HRSAERAS_ As we will refer to it when we are talking about, yeah....
## What Hammer Does
### Shared Assests.
/// HAMMER's own system HRSAERAS will first extract contents from a ServerStorage Folder and run the script, this will first get the shared assests ready,
The Coding is as follows:

```lua
print("/// HAMMER")
print("/// 🔨 - HAMMER")
print("/// 🔨 Shared Asests loader")
warn("/// Below this is 🔨 Shared Asests Loader Logs, to only be used for debuging.")
warn("/// 🔨 Shared Asests Logs.")
warn("/// 🔨 | ⚠️ - If no shared asests appear, this may mean that either: The developer put them in the wrong place or there are no shared asests.")
warn("/// 🔨 | ⚠️ - The right place is ServerStorage under [SHAREASESTS]")
print("/// 🔨 | 🕐 - Waiting 5 Seconds.")
wait(5)
if game.ServerStorage.SHAREASESTS.True.Value == true then
	print("/// 🔨 | ✅ - The folder is there!")
else
	error("/// 🔨 | ❎ - An error happened while requesting a required module, script halted.")
end
print("/// 🔨 | 🕐 - Waiting 5 Seconds.")
wait(5)
if game.ServerStorage.SHAREASESTS.SharedAssests.Disabled == true then
	print("/// 🔨 | ✅ - The script is there!")
end
print("/// 🔨 | 🕐 - Waiting 5 Seconds.")
wait(5)
print("/// 🔨 | 🕐 - Putting Script in SERVERSCRIPTSERVICE and running.")
game.ServerStorage.SHAREASESTS.SharedAssests.Parent = game.ServerScriptService
game.ServerScriptService.SharedAssests.Disabled = false
print("/// 🔨 | ✅ - Script Running")
```
This is optimized for RBLX Lua.