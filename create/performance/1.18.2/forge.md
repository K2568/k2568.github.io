# K2's Lists / Create / Performance / 1.18.2 / Forge

## Extra performance:

[List of performance mods from TheUsefulLists](https://github.com/TheUsefulLists/UsefulMods/blob/main/Performance/Performance118.md#forge-118x)

If you are playing multiplayer:<br>
Client mods are only needed on the client, you don't need to put this on a server.<br>
Server mods are only needed on the server end, if you are hosting with essential or e4mc then install them on your client.<br>
Both mods will be needed on both client and server for players to be able to join while they are present.

If you are playing singleplayer you can ignore the client, server, both tags.<br>
<br>

If you dont want to manually install the mods this is the recommended modpack: <br>
[Download Latest Forge Modrinth](https://modrinth.com/modpack/hammer/versions?c=release&c=beta&c=alpha&g=1.18.2&l=forge) <br>

## If you want to use shaders:

|                    | Modrinth        | Curseforge      |
|--------------------|-----------------|-----------------|
| Oculus             | [Download Latest](https://modrinth.com/mod/oculus/versions?c=beta&c=release&g=1.18.2&l=forge) | [Download Latest](https://www.curseforge.com/minecraft/mc-mods/oculus/files/all?page=1&pageSize=20&version=1.18.2&gameVersionTypeID=6&showAlphaFiles=show) |
| Iris Flywheel Compat| [Download Latest](https://modrinth.com/mod/iris-flw-compat/versions?c=release&c=beta&c=alpha&g=1.18.2&l=forge) | [Download Latest](https://www.curseforge.com/minecraft/mc-mods/iris-flywheel-compat/files/all?page=1&pageSize=20&version=1.18.2&gameVersionTypeId=1&showAlphaFiles=show) |

If you still experience rendering problems or lost performance try all flywheel backends including the one Iris Flywheel Compat adds: <br>
/flywheel backend irisflw:iris_instancing <br>
/flywheel backend batching <br>
/flywheel backend instancing <br>
/flywheel backend off <br>