#### v1.1.2 [2022-04-14]
- Add command to output internal and display names
  * See ["Console commands"](https://github.com/eideehi/valheim-automatics#console-commands) in the README for details.
- Add options to suppress automatic processing based on item count
- Add option to automatic refuel only when materials supplied
- Change 'Automatic Repair' not to work during game pauses
- Change 'Allow...(Custom)' options to evaluate for exact match if an internal name is specified, or partial match if a display name is specified
  * The "$enemy_boar" matches only "Boar", but "Greydwarf" matches "Greydwarf brute" and "Greydwarf shaman" in addition to "Greydwarf"
  * The same goes for TARGET for [Custom Map Icon](https://github.com/eideehi/valheim-automatics#custom-map-icons)
#### v1.1.1 [2022-04-10]
- Fix package task of mod files for Thunderstore
- Fix a bug in which the 'Repair Pieces' function continued to work even though the 'Automatic Repair' feature was disabled in the configuration
#### v1.1.0 [2022-04-07]
- Add the feature of 'Automatic Feeding'
- Add the feature of 'Automatic Repair'
- Add option to allow automatic opening/closing for any door
- Fix a bug where the generated items would be lost if Smelter could not find the container when 'Automatic Store' was enabled
- Fix a bug where the honey to be set over the maximum if Beehive could not find the container when 'Automatic Store' was enabled
#### v1.0.6 [2022-04-04]
- Fix a bug that prevented automatic pinning of player existing in the open air under certain conditions, judging that they exist in the dungeon
- Add elements added in patch 0.207.20 to be the target for automatic pinning
- Change the maximum value of the container search range in 'Automatic Processing' to 64
- Change to remove pins added by automatic pinning when some veins are destroyed
#### v1.0.5 [2022-03-28]
- Add shortcut key to perform searches for static objects
- Add shortcut key to enable/disable automatic door
- Fix a bug that caused dynamic pins to remain on the map when auto-pinning was disabled from the config
- Change the initial value of the 'Automatic Map Pinning' configuration
#### v1.0.4 [2022-03-18]
- Fix a bug fish were not pinned
- Fix a bug that caused pins to be deleted at unintended times
- Fix a bug in which automatic pinning of ship was enabled regardless of the config value
- Add the feature to customize the icons of pins added by auto pinning
  * There are no custom icons bundled with Automatics, please add your own
#### v1.0.3 [2022-03-16]
- Fix a bug where tamed animals continue to be pinned
- Add options for users to add map pinning targets (animals, monsters, flora, veins, and spawners)
  * As a result, elements added by mods are no longer automatic pinning unless this option is used
- Add an option to allow ships to be automatic pinning
  * This is dynamic pinning, but unlike other dynamic pins, the pins is saved in the save data
#### v1.0.2 [2022-03-15]
- Improvement of FPS drop due to Automatic Map Pinning
  * In particular, FPS is greatly improved in areas with a lot of flora, such as farms
- Reduce the processing load on Automatic Door
- Add Portal to the Automatic Map Pinning target
  * Portal is added to 'Allow Pinning Other Objects'
#### v1.0.1 [2022-03-06]
- Fix a bug that prevented some Tar Pits from being pinning
- Fix a bug in which automatic map pinning of static objects causes a significant drop in FPS
- Fix logic for determining if a vein is in ground
- Change the Automatic Map Pinning process is not called when the game is paused
- Change Automatic Door options so that Open and Close can be specified separately
#### v1.0.0 [2022-01-23]
- Initial release