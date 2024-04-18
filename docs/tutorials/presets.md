# Creating Presets

Creating a preset is as simple as creating a new `.json` file in the `Presets` folder and setting the options you want.

**Notes**

- Removing properties means that BetterSabers will automatically use the default values shown in the Example Preset
- It is recommended to look at the included presets to understand how a final preset looks.
- All comments (human readable text that start with 2 slashes) should be removed when saving the file as a preset  
- The final preset file must be a `.json` file for it to be recognized by BetterSabers

## Example Preset

The Example Preset goes over how a preset functions

``` json title="ExamplePreset.json"
// The Basic Structure of a Preset (1)
{
  // Metadata (2)
  "Metadata": {
    "Name": "Example Preset",
    "Author": "Your Name Here",
    "Version": "1.0.0"
  },

  // OuterColor (3)
  "OuterColor": [1, 1, 1],
  "Mult": 1000,

  // InnerColor (4)
  "InnerColor": [1, 1, 1],
  "Desat": 1,

  // Light (5)
  "LightColor": [1, 1, 1],
  "LightIntensity": 100,
  "LightPulseIntensity": 0.25,
  "LightFalloffOffset": 0.1,
  "LightFalloffRadius": 10,

  // Shape (6)
  "Width": 0.03,
  "LengthMult": 1.0,
  "TipLength": 0.075,
  "TipMinWidth": 0.2,

  // Trail (7)
  "BaseMotionMult": 0.25,
  "BaseWidthMult": 1.1,

  // Pulse (8)
  "PulseAmplitude": 0.25,
  "PulseIntensity": 0.15,

  // Enforce Style (9)
  "EnforceStyle": "Standard",

  // Example Extra Parameter (10)
  "ExtraParams": [
    { "ID": 38069024, "Values": [2, 4, 0.005, 1.5] }
  ]
}
```

1. Removing properties means that BetterSabers will automatically use the default value shown here.  
It is recommended to look at the included presets to understand how a final preset looks.  
<br>All comments (human readable text that start with 2 slashes) should be removed when saving the file as a preset  
<br>The final preset file must be a .json file for it to be recognized by BetterSabers

2. Where you name your preset aswell as crediting yourself as the author.  
Version is a string, by default it will use the version of the plugin.

3. Changes the color of the Edge of the saber blade.  
(Color0)

4. Changes the color of the Core of the saber blade.  
(Color1)

5. Controls the light emitted onto the world.  
LightPulseIntensity is multiplied by 3.6x for unstable sabers.

6. Controls the shape of the saber.  
LengthMult multiplies the existing length of the saber.  
For consistency, unstable sabers have a 1.69x multiplier on the Width aswell as having 0.1 added to the TipLength in here.

7. Controls the trail of the saber.  
Overall trail length is controlled by the end user and therefore cannot be changed through presets.

8. Controls the pulsing/flickering of the saber.

9. Forces the saber style/stability. Value can be either "Standard" or "Unstable".  
By default this option isnt included to allow a preset to work for either Stable or Unstable sabers.

10. For advanced creators who want to edit params not normally exposed by the plugin.  
Most creators can just delete this section.