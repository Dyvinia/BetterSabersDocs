# Setup & Installation

## Kyber V2 Installation

1. Download the [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)

2. Download the latest version of [BetterSabers](https://www.nexusmods.com/starwarsbattlefront22017/mods/16?tab=files)

3. Drag and drop the `.zip` file into the Kyber V2 Launcher

## Frosty Installation

1. Download the [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)

2. Download the latest version of [BetterSabers](https://www.nexusmods.com/starwarsbattlefront22017/mods/16?tab=files)

3. Open the `.zip` file and drag `BetterSabersPlugin.dll` Into the `Plugins` Folder

## Using the Manager

1. Select individual presets on the left and/or select a preset pack on the bottom right.

2. Configure the other settings to your desire
    - `Name` will change the name of the generated mod
    - `Trail Length` changes the length of the saber trails (motion blur)
        - The optimal value is dependent on your monitor's refresh rate, but is mostly up to personal preference
        - Shorter trails/lower values look better with higher refresh rate monitors due to the saber moving less per frame
            - `0.5` is optimal for 60hz displays
            - `0.35` is optimal for 144hz displays
            - `1.0` is the default value in the game set by DICE
    - `Show Advanced Options` shows options that may be not relevent to most users
        - `Light Intensity` changes the overall intensity of light emitted onto the surrounding world

    - `Auto Select Presets` will automatically select the appropriate color for the sabers on the list on the left based on the auto select pack selected in the dropdown below


## Troubleshooting

- When opening a bug report, make sure to check the log (`%AppData%\BetterSabersManager\log.txt`) and upload/paste it to something like [pastes.dev](https://pastes.dev/)


## Installing Presets

Drag and drop presets to automatically install them

<div style="text-align:center">
  <video autoplay muted loop playsinline>
    <source src="../../assets/images/AutoInstallPresets.mp4" type="video/mp4">
  </video>
</div>

### Manual Installation

1. Locate the `Presets` folder
    - Pressing ++f12++ in the BetterSabers Manager window
    - Going to `Help` > `BetterSabers Folder` in Frosty Mod Manager
    - Pasting `%APPDATA%\BetterSabersManager\Presets` into File Explorer

2. Drag the downloaded preset folder into the `Presets` folder.
