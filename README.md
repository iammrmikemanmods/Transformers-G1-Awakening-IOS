# ClassicBubbles Lab — isolated CI branch

This branch builds the ClassicBubbles diagnostic and native-preview app. It is not a Transformers game update and must not be merged into main.

0.1.0: user confirmed app/helper execution on iPhone11,8, iOS 17.5.1, UID 501; wallpaper frameworks and native Bokeh classes loaded.
0.1.1: opt-in native WKBokehView preview experiment with installed presets, Pause/Play, Light/Dark and persistent progress report. No wallpaper application or SpringBoard injection.

The immutable base source plus compressed, SHA-256-pinned diff reconstructs the complete developer source. The final manifest verifies every source file before compilation. Package identifier remains com.iammrmikeman.classicbubbles. Installation/upgrades/removal through Sileo exclusively.

Build validation does not establish successful native rendering on the phone; that remains pending the user's preview test.
