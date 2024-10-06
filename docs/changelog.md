# Changelog

## v2.1.0
- Prevent scrolling when hovering over a (closed) combobox
- Blur the background of dialog windows to improve text readability
- Add version checker to the manager itself
- Button to open bug reports page
- Update checker opens the latest version page
- Support for Kyber V2
- Various fixes

## v2.0.3
- Blur entire window when dragging in preset
- Improvements to resource and assembly loading
- Added prompt to select the executable manually if SWBF2 cannot be autolocated
- Various fixes

## v2.0.2
- Fix Light Intensity not working
- Fix crashes when Light Intensity is set too high

## v2.0.1
- Fix issue when switching packs in Frosty after using BetterSabers

## v2.0.0
<h3><strong>New UI</strong></h3>
- Easier to read
- More Responsive

<div style="text-align: center">
  <video style="max-width: 700px" autoplay muted loop playsinline>
    <source src="../assets/images/v200.mp4" type="video/mp4">
  </video>
</div>

<h4>Updated Preset format</h4>
- New `EnforceStyle` option
    - Forces the saber style/stability. Value can be either `Standard` or `Unstable`
    - Omitting the option allows users to use the preset on any type of saber
- Renamed `Color0` and `Color1` to more accurate names

<h4>Moved Presets to centralized directory in Appdata</h4>
- `%APPDATA%\BetterSabersManager\Presets`
- Can be found [here](/tutorials/installation/#manual-installation){ target="_blank" }

<h4>Other Changes</h4>
- Embedded debug info to allow for better troubleshooting
- Improved Performance
- Rewritten as a .NET 8 standalone application which connects to a Frosty Plugin

## v1.4.2
- Frontend Trail Multiplier
    - Increases Trail Length value while in the frontend
- Fix minor issues

## v1.4.1
- Export Packs using ++ctrl+e++
- Fix minor issues

## v1.4.0
<h4>Major Updates to UI</h4>
- New button in Mod Manager window to conveniently open the saber manager
- Add author subtitle to presets and packs
- Sabers are sorted alphabetically (configurable)
- Increased size of window

<div style="text-align:center">
  <video width="600" autoplay muted loop playsinline>
    <source src="../assets/images/v140.mp4" type="video/mp4">
  </video>
</div>


<h4>Other Changes</h4>
- Added Pink Saber color
- Updated [Pack format](../tutorials/auto-preset/)
- Improved loading times
- Added support for unstable custom params
- Improved generated mod description
- Solved crashing issues

## v1.3.3
- Update formatting in generated mod description
- Various fixes

## v1.3.2
- `Auto Select Presets` dropdown now remembers the last selected pack
- Add open folder button
- Various fixes

## v1.3.1
- Inform the user when presets/packs are unable to load
- Various fixes and QoL

## v1.3.0
- Major update to BetterSabers window
    - New Dropdown for [Auto Select Presets](../tutorials/auto-preset/)
    - Added Light Intensity option
    - More space for options
- New Folder structure, user will be prompted to transfer files to new folder.
- Added `LengthMult` property: Multiplies the existing length of the saber.
- Added `LightPulseIntensity` property: Changes the flickering of the light.
- Adjust default light falloff offset
- Various other changes and fixes

## v1.2.1
- Fixes with preset loading
- Support for name overrides
- Various fixes

## v1.2.0
- New options for [Auto Select Preset](../tutorials/auto-preset/)
- Option to change name of generated mod
- Proper Error checking when loading presets
- Update window styling
- Various fixes and QoL

## v1.1.1
- Link to new Docs Page
- Updated BetterSabers Yellow
- Various fixes and QoL