# Auto Select Preset

The presets automatically selected by the `Auto Select Preset` button can be changed

![image](../assets/images/AutoSelectPreset.png){ width="300"}

The `BetterSabersPresets\.AutoSelect\Presets.json` file is where the auto selection of presets can be set by the user:

``` json title=".AutoSelect\Presets.json"
{
  "red": "Red [BetterSabers]",
  "cd": "Red [BetterSabers]",
  "kylo": "Red [BetterSabers]",

  "blue": "Blue [BetterSabers]",

  "greenyellow": "Lime [BetterSabers]",
  "lime": "Lime [BetterSabers]",

  "green": "Green [BetterSabers]",

  "purple": "Purple [BetterSabers]",

  "yellow": "Yellow [BetterSabers]"
}
```

The left side is the search pattern, while the right side is the preset name.  
If a saber blueprint contains the text[^1] `red`, `cd`, or `kylo` in its name, it will select the preset named `Red [BetterSabers]`.

The file is read from top to bottom, so a file containing `greenyellow` will auto select Lime since it is above Green


[^1]: Case Insensitive