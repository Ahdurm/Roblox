# Roblox

Scripts for this game live in `src/` and are synced into Roblox Studio with [Rojo](https://rojo.space).

| Folder        | Shows up in Studio as                          |
|---------------|------------------------------------------------|
| `src/server`  | ServerScriptService › Server                   |
| `src/client`  | StarterPlayer › StarterPlayerScripts › Client  |
| `src/shared`  | ReplicatedStorage › Shared                     |

File endings: `.server.luau` = Script, `.client.luau` = LocalScript, `.luau` = ModuleScript.

## Syncing into Studio

1. Install the Rojo plugin in Studio and the Rojo app (see rojo.space).
2. Get the latest files: `git pull`
3. In this folder run: `rojo serve`
4. In Studio, open the Rojo plugin and click **Connect**.

Only the `Server`, `Client` and `Shared` folders are managed by Rojo; everything else in your place is left alone.
