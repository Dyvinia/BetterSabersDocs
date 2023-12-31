# Example Preset

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

  // Color0
  "Color0": [1, 1, 1],
  "Mult": 1000,

  // Color1
  "Color1": [1, 1, 1],
  "Desat": 1,

  // Light (3)
  "LightColor": [1, 1, 1],
  "LightIntensity": 100,
  "LightPulseIntensity": 0.25,
  "LightFalloffOffset": 0.1,
  "LightFalloffRadius": 10,

  // Shape (4)
  "Width": 0.03,
  "LengthMult": 1.0,
  "TipLength": 0.075,
  "TipMinWidth": 0.2,

  // Trail (5)
  "BaseMotionMult": 0.25,
  "BaseWidthMult": 1.1,

  // Pulse (6)
  "PulseAmplitude": 0.25,
  "PulseIntensity": 0.15,

  // Example Extra Parameter (7)
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
Version is a string, by default it will use the version of the plugin

3. Controls the light emitted onto the world.  
LightPulseIntensity is multiplied by 3.6x for unstable sabers

4. Controls the shape of the saber.  
LengthMult multiplies the existing length of the saber.  
For consistency, unstable sabers have a 1.69x multiplier on the Width aswell as having 0.1 added to the TipLength in here

5. Controls the trail of the saber.  
Overall trail length is controlled by the end user and therefore cannot be changed through presets

6. Controls the pulsing/flickering of the saber.

7. For advanced creators who want to edit params not normally exposed by the plugin.  
Most creators can just delete this section.