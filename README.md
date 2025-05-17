This is the repo that the ROBLOX plugin [Sulfur](https://create.roblox.com/store/asset/110633114361989/Sulfur) uses to track information like public auth keys, versions, etc.

[Current version can be found here](./version.txt)
[V1 Public AUTH Key](./public-key.txt)

# Documentation
## 1. Sulfur Quick Commands (SQC)
You can easily toggle specific FFlag's for your sulfur client by opening the ROBLOX Studio `Command Bar` in `Properties`.
Once open you can access the **SQC** by typing: 
```lua
_G.SulfurCMD:Do(FFlagName, boolean)
```
This will then toggle a FFlag to the given boolean. (Persistent)

| Status                                | FFlag Name                                                                                 |
| ------------------------------------- | ------------------------------------------------------------------------------------------ |
| `FFlagEnableSulfurPlusFeatures`       | ![Disabled](https://img.shields.io/badge/FFlagEnableSulfurPlusFeatures-false-red)          |
| `FFlagEnableAdvancedTextHighlighting` | ![Disabled](https://img.shields.io/badge/FFlagEnableAdvancedTextHighlighting-false-red)    |
| `FFlagEnableAnalyticsGraph`           | ![Enabled](https://img.shields.io/badge/FFlagEnableAnalyticsGraph-true-brightgreen)        |
| `FFlagAllowUserInputRegistry`         | ![Enabled](https://img.shields.io/badge/FFlagAllowUserInputRegistry-true-brightgreen)      |
| `FFlagEnableAutoSave`                 | ![Enabled](https://img.shields.io/badge/FFlagEnableAutoSave-true-brightgreen)              |
| `FFlagEnableTelemetry`                | ![Disabled](https://img.shields.io/badge/FFlagEnableTelemetry-false-red)                   |
| `FFlagEnableBetaFeatures`             | ![Disabled](https://img.shields.io/badge/FFlagEnableBetaFeatures-false-red)                |
| `FFlagAllowDocumentationKeybind`      | ![Enabled](https://img.shields.io/badge/FFlagAllowDocumentationKeybind-true-brightgreen)   |
| `FFlagEnableLiveCollaboration`        | ![Disabled](https://img.shields.io/badge/FFlagEnableLiveCollaboration-false-red)           |
| `FFlagAllowCustomShortcuts`           | ![Enabled](https://img.shields.io/badge/FFlagAllowCustomShortcuts-true-brightgreen)        |
| `FFlagEnablePerformanceProfiling`     | ![Enabled](https://img.shields.io/badge/FFlagEnablePerformanceProfiling-true-brightgreen)  |
| `FFlagEnableSyntaxErrorHints`         | ![Enabled](https://img.shields.io/badge/FFlagEnableSyntaxErrorHints-true-brightgreen)      |
| `FFlagEnablePluginTelemetryOptOut`    | ![Enabled](https://img.shields.io/badge/FFlagEnablePluginTelemetryOptOut-true-brightgreen) |
| `FFlagEnableUndoHistory`              | ![Enabled](https://img.shields.io/badge/FFlagEnableUndoHistory-true-brightgreen)           |
| `FFlagEnableExperimentalAPI`          | ![Enabled](https://img.shields.io/badge/FFlagEnableExperimentalAPI-true-brightgreen)       |
| `FFlagEnableSelectionBox`             | ![Enabled](https://img.shields.io/badge/FFlagEnableSelectionBox-true-brightgreen)          |
