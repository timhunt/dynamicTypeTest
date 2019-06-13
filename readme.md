# dynamicTypeTest Ionic app

This is an absolutely minimal Ionic app to explore why Ionic ignores the iOS
[Dynamic Type Sizes settings](https://developer.apple.com/design/human-interface-guidelines/ios/visual-design/typography/) 
even though it seems to respect the [Android](https://material.io/design/typography/#type-scale)
[equivalents](https://material.io/design/usability/accessibility.html#layout-typography). 

Created in relation to this Moodle Mobile App bug:
https://tracker.moodle.org/browse/MOBILE-2097

Basically, this app just shows the contents of [src/pages/home/home.html](src/pages/home/home.html)
when you lanuch the app. You can the compare how that is rendered with
