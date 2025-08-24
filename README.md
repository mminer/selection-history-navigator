# Selection History Navigator

This is a Unity editor extension that adds web browser-style **Back** and
**Forward** items to the *Edit > Selection* menu. These allow you to quickly
re-select the game object or asset that you previously had selected.

![Screenshot](https://matthewminer.com/images/selection-history-navigator.png)


## Installing

Add the package to your project via
[UPM](https://docs.unity3d.com/Manual/upm-ui.html) using the Git URL:

```
https://github.com/mminer/selection-history-navigator.git
```

1. Open the Package Manager window in Unity (*Window > Package Manager*)
2. Click the "+" button in the top-left corner
3. Select "Install package from git URL..."
4. Enter the above Git URL
5. Click "Install"

Alternatively, add the following line to your `Packages/manifest.json` file:

```json
{
  "dependencies": {
    "com.matthewminer.selection-history-navigator": "https://github.com/mminer/selection-history-navigator.git",
    ...
  }
}
```

You can also clone the repository and point UPM to your local copy.


## Using

After clicking on a few game objects or assets, press <kbd>command</kbd>
<kbd>[</kbd> (macOS) or <kbd>ctrl</kbd> <kbd>[</kbd> (Windows) to return to the
previous selection.

After navigating backward, you can also navigate forward with
<kbd>command</kbd> <kbd>]</kbd> (macOS) or <kbd>ctrl</kbd> <kbd>]</kbd>
(Windows).
