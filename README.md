# Sync Plugins
Sketch.app plugin for syncing current / local `.sketchplugins` with their master raw version at GitHub. Operates directly from the application menu bar.

## Installation
1. Download and open `Sync-Plugins-master.zip`
2. Navigate the Sketch menu bar to `Plugins ▸ Reveal Plugins Folder...`
3. Place the `Sync Plugins.sketchplugin` and `Plugin.index` files in this folder
4. That's it...

## How to Use 
Edit the `Plugin.index` file by adding any / all plugins you plan to keep synchronized ( see example below ). Begin the syncing process by selecting `Plugins ▸ Sync Plugins` in the Sketch menu bar. A notification will sound when syncing completes and the plugins are updated.
 
**Index Example**

```Javascript
// Normal
Plugin_1 = "MyPlugin.sketchplugin"
GitHub_1 = "https://raw.githubusercontent.com/user/repo/master/.."

Plugin_2 = "YourPlugin.sketchplugin"
GitHub_2 = "https://raw.githubusercontent.com/user/repo/master/.."

// Subfolder
Plugin_3 = "YourPluginFolder/YourPlugin.sketchplugin"
GitHub_3 = "https://raw.githubusercontent.com/user/repo/master/.."
```

**Keyboard Shortcut**  
 `Control` + `Shift` + `S`
 
**Usage Notes**  
Only the plugins listed in `Plugin.index` will sync. The naming structure, for example: `Plugin_2` and `GitHub_2`, must remain intact for the plugins to sync properly. The script initially supports 10 plugins, but more can be added by editing the `Sync Plugins.sketchplugin` file. Do this **only** if you are completely confident in how it works.

## Feedback
If you discover any issues or have questions regarding usage, please send a message to [code@nath.co](mailto:code@nath.co) or find me on GitHub [@nathco](https://github.com/nathco).