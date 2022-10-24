# Godot

## Hints

You can use the [Godot Tools](https://marketplace.visualstudio.com/items?itemName=geequlim.godot-tools) extension to run code in VS Code. With Godot 4, make sure the VS Code language server port setting is changed to `6005`. In Godot 3, this defaults to `6008`.

```
Godot_tools: Gdscript_lsp_server_port
The server port of the GDScript language server
6005
```

When this isn't set correctly, you may see the following error:

```
Couldn't connect to the GDScript language server at 127.0.0.1:6008. Is the Godot editor running?
```
