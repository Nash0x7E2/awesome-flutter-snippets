# CHANGELOG

# Changelog

All notable changes to this project will be documented in this file.

## [Changes]

### 4.0.0

- **Breaking: Change `testWdigets` to `f-testWidgets` to better align with function snippets**
- Support for `group` test function `f-group`
- Support for app localisation import `importAL`
- Support for Flutter 3
    - Migrate to super initialisers
    - Not on Flutter 3? The Flutter 2.xx branch is up to date and ready for you :)
- Fixed Lint issue - Added `const` to applicable widgets

### 3.0.3

- Use State
    
    createState on statefulW snippet (Thank you [@marcossevilla](https://github.com/Nash0x7E2/awesome-flutter-snippets/commit/b18505ae59128ce8c2ff4cc60100603dc11259d5))
    

### 3.0.2

- Removed trailing whitespaces (Thank you @leoshusar https://github.com/Nash0x7E2/awesome-flutter-snippets/pull/45)
- Make widgets default to Container only (Thank you @Ascenio https://github.com/Nash0x7E2/awesome-flutter-snippets/pull/43)

### 3.0.1

- Support for `Listview.builder`
- Support for `GridView.count`
- Support for `GridView.extent`

### 3.0.0

- Update all widgets to null safety
- Update engine to `1.56.0`

### 2.0.4

- Add Flutter test import (Thank you @arthurdenner https://github.com/Nash0x7E2/awesome-flutter-snippets/pull/16)
- Support for unit and widget test functions (Thank you @TNorbury https://github.com/Nash0x7E2/awesome-flutter-snippets/pull/20)
- Added support for Listview.Separated (Thank you @timilehinjegede https://github.com/Nash0x7E2/awesome-flutter-snippets/pull/26)
- Fixed inheritedW (Thank you @ianwith https://github.com/Nash0x7E2/awesome-flutter-snippets/pull/22)

### 2.0.3

- Support for `BehaviorSubject` (Thanks @sinadarvi https://github.com/Nash0x7E2/awesome-flutter-snippets/pull/7)
- Support for `TweenAnimationBuilder`
- Support for `ValueListenableBuilder`
- Fixed various bug fixes and typos

### 2.0.2

- Resolved issue [#6](https://github.com/Nash0x7E2/awesome-flutter-snippets/issues/6)

### 2.0.1

- Removed Stateful and Statless Widget since they are included with DartCode.
- Added Material App.
- Added Cupertino App.

### 2.0.0

- Changed prefixes to use a keyword associated with the widget/function (in camel case)
- Bug fixes

### 1.0.6

- Added support for debug print
- Added support for to string
- Added support for importing Cupertino package
- Added support for importing Material package (PR #2)
- Added child logic to Stateless and Stateful widgets snippets (PR #3)

### 1.0.5

- Adjusted tab stops to improve efficiency and workflow
- Removed blank Containers from builders in favor of a tab stop with semi-colon
- Added trailing comma at the end of child parameter

### 1.0.4

- Fixed formatting
- Removed unused tabs
- Corrected spelling errors

### 1.0.3

Added support for: - Stream - Sink - Inherited Widget - Mounted - NoSuchMethod

### 1.0.2

Added support for: - Stateful Builder - Orientation Builder - Layout Builder - Single Child Scroll View - Future Builder

### 1.0.1

Added support for: - Stream Builder - Animated Builder - Custom Scroll View - Listview.Builder

### 1.0.0

- Initial Relase