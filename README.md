# U3 SDK

This branch introduces a way for `Localization` mods to translate Unturned or Workshop assets without the need of any other consumer input like manually copying files over.

There are 4 supported formats\
`Path/To/Asset/{Language}.dat` (Unturned's default near `Asset.dat`)\
`LocalizationRoot/Assets/{AssetGUID}.dat`\
`LocalizationRoot/Assets/Unturned/Path/To/Asset/{Language}.dat`\
`LocalizationRoot/Assets/Workshop/WorkshopId/Path/To/Asset/{Language}.dat`

Note: Yes I know there is no reason to name translation file `{Language}.dat` if its already in the corresponding LocalizationRoot, to anyone complaining there is in fact no reason to change it and require more work from translators (unless they can automate their stuff) except simply moving it to new folders like `Assets/Unturned`.