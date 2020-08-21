# SPM 5.3 Resources Bug

In Xcode 12b5 when using Xcode Previews with a SPM package that has resources the preview stops working.

To see this in action
- clone the repo
- change the active target to SomeFeature
- try to preview the file `SomeFeatureView.swift` with and without the `foregroundColor` modifier applied

Note:
- this is broken whether or not you manually specify the resource in the `Packge.swift` configuration.
