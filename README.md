# UnityAssetBundleDuplicateIdTest
Test Project for reporting AssetBundle duplicate id bug

Run the command in 

Assets/AssetBundles/Build AssetBundle

It should build two asset bundles variants, but it gives an error

* Building AssetBundle failed because hash collision was detected in the deterministic id generation.
Conflict happened between Asset "Assets/Variant1/Folder2/testfile1.txt" and "Assets/Variant1/Folder1/testfile1.txt".
* Failed to finalize AssetBundle!
* Failed to replace file AssetBundles/OSX/assetbundle1.var1
