# 1.0.0
* Cross-platform support. (Windows, macOS, Android, iOS, renderer is Windows only, mobile coming soon)
* GDR2 support.
* Rewrote Layout Mode. (Levels now load significantly faster and triggers do not break)
* Fix seed freezing and crashing. (Switched to Geode's generator for seeds)
* Fix iOS related filesystem crashes. (Switched to Geode utilities for filesystem operations, temporarily removed macros/renders/autosaves location settings in More Settings due to issues with Geode, where those settings would crash.)
* Beautify game version display in macro information popup. (Used to have trailing zeros)
* Port keybinds to Geode's keybind system (cross-platform keybinds, including mobile if connected to a Bluetooth/USB keyboard.)
* Fix a bug where if a popup is open in xdBot, the keybinds would still be clickable, causing unexpected behavior like being able to close the xdBot menu via keybinds.
* Added a setting to More Settings to open the xdBot menu instantly.
* Added a setting to More Settings to choose the default macro format. (GDR2, GDR, JSON)
* Made xdBot detect and prevent you from recording/playing a macro or rendering a level if you have Click Between Steps enabled in Geometry Dash settings.
* Fix capitalization of 'OK' across UIs.