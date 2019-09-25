# Complete-Uninstall-Xcode
This is the guide to manually uninstall xcodes and alternative xcodes 

Source :- https://stackoverflow.com/a/53575585/10422074

For a *complete* removal of *Xcode 10* delete the following:

 1. `/Applications/Xcode.app` 
 2. `~/Library/Caches/com.apple.dt.Xcode`
 3. `~/Library/Developer` 
 4. `~/Library/MobileDevice`
 4. `~/Library/Preferences/com.apple.dt.Xcode.plist`
 5. `/Library/Preferences/com.apple.dt.Xcode.plist`
 6. `/System/Library/Receipts/com.apple.pkg.XcodeExtensionSupport.bom`
 7. `/System/Library/Receipts/com.apple.pkg.XcodeExtensionSupport.plist`
 8. `/System/Library/Receipts/com.apple.pkg.XcodeSystemResources.bom`
 9. `/System/Library/Receipts/com.apple.pkg.XcodeSystemResources.plist`

but if you don't want to lose all of your customizations, consider saving these files or folders before deleting anything:

 1. `~/Library/Developer/Xcode/UserData/CodeSnippets`
 2. `~/Library/Developer/Xcode/UserData/FontAndColorThemes`
 3. `~/Library/Developer/Xcode/UserData/KeyBindings`
 4. `~/Library/Developer/Xcode/Templates`
 5. `~/Library/Preferences/com.apple.dt.Xcode.plist`
 6. `~/Library/MobileDevice/Provisioning Profiles`


#### Note :- Dont Delete `~/Library/Developer/PrivateFrameworks` else u will face crashes on new xcode installations
