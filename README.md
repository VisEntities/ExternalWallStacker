The plugin will allow the server owner to set the amount of high external walls that will be stacked on top of the placed high external wall, set whether the user of this plugin will need the chat command permission or not, and require the user of this plugin to have the materials required to stack the walls.

When the user places an high external wall, a # of externals walls are stacked on top. The # is based on the plugin configuration. The plugin has one toggle command (/wstack) and is compatible with [URL='http://oxidemod.org/plugins/r-remover-tool.651/'][B][I]RemoverTool by Reneb[/I][/B][/URL]. When the user removes the ground high external wall then the walls stacked on top are also destroyed.

## Chat Commands
* `wstack` - Enables/disables high external wall stacking.


## Permission
* `externalwallstack.wstack`

## Configuration
[LIST]
[*][I][U]RequireMaterials[/U][/I]
[/LIST]
[LIST]
[*][B]Description[/B]: When this configuration is set to true, it will require the users to have high external walls in order to stack high external walls. If the users has 2 high external walls and the configuration setting "[U][I]StackHeight[/I][/U]" is set to 2, the walls will stack 1 high because 1 of the 2 high external walls is being placed on the terrain. If the user removes the ground high external wall while this configuration is set to true, they will receive all of the high externals they used to stack the wall.
[/LIST]
[LIST]
[*][U][I]StackHeight[/I][/U]
[/LIST]
[LIST]
[*][B]Description[/B]: This configuration will dictate how high the high external walls will stack.
[/LIST]
[LIST]
[*][U][I]UsePermission[/I][/U]
[/LIST]
[LIST]
[*][B]Description[/B]: If this configuration is set to true, it will require the users to have the permission "externalwallstack.wstack" to use the chat command /wstack.
[/LIST]
[U][B]Lang[/B][/U]
[LIST]
[*][I][U]NotAuthorized[/U][/I]
[/LIST]
[LIST]
[*][B]Description[/B]: The message that is displayed to the user if they don't have the permission to run the chat command /wstack.
[/LIST]
[LIST]
[*][U][I]CommandToggle[/I][/U]
[/LIST]
[LIST]
[*][B]Description[/B]: The message that is displayed to the user if they successfully run the chat command /wstack.
[/LIST]

## Credits
* Originally created by Dyceman - Deadlaugh