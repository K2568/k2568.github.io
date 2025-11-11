# K2's Lists / Create / Performance / 1.19.2 / Fabric-Quilt

## Extra performance:

[List of performance mods from TheUsefulLists](https://github.com/TheUsefulLists/UsefulMods/blob/main/Performance/Performance119.md#fabric-119x)

Fabric mods work on quilt but not the other way around

If you are playing multiplayer:<br>
Client mods are only needed on the client, you don't need to put this on a server.<br>
Server mods are only needed on the server end, if you are hosting with essential or e4mc then install them on your client.<br>
Both mods will be needed on both client and server for players to be able to join while they are present.

If you are playing singleplayer you can ignore the client, server, both tags.<br>
<br>

If you dont want to manually install the mods this is the recommended modpack: <br>
[Download Latest Fabric Curseforge](https://www.curseforge.com/minecraft/modpacks/fabulously-optimized/files/all?page=1&pageSize=20&version=1.19.2&showAlphaFiles=show) <br>
[Download Latest Fabric Modrinth](https://modrinth.com/modpack/fabulously-optimized/versions?g=1.19.2&c=release&c=beta&c=alpha)

## If you want to use shaders:

|                    | Modrinth        | Curseforge      |
|--------------------|-----------------|-----------------|
| Iris             | [Download Latest](https://modrinth.com/mod/iris/versions?c=beta&c=release&g=1.19.2&l=fabric) | [Download Latest](https://www.curseforge.com/minecraft/mc-mods/irisshaders/files/all?page=1&pageSize=20&version=1.19.2&gameVersionTypeId=4) |
| Iris Flywheel Compat| [Download Latest](https://modrinth.com/mod/iris-flw-compat/versions?c=release&c=beta&c=alpha&g=1.19.2&l=fabric) | [Download Latest](https://www.curseforge.com/minecraft/mc-mods/iris-flywheel-compat/files/all?page=1&pageSize=20&version=1.19.2&gameVersionTypeId=4&showAlphaFiles=show) |

If you still experience rendering problems or lost performance try all flywheel backends including the one Iris Flywheel Compat adds: <br>
/flywheel backend irisflw:iris_instancing <br>
/flywheel backend batching <br>
/flywheel backend instancing <br>
/flywheel backend off <br>