Awesome Flutter Snippets is a collection of commonly used Flutter classes and methods. It increases your speed of development by eliminating most of the boilerplate code associated with creating a widget. Widgets such as `StreamBuilder` and `SingleChildScrollView` can be created by typing the shortcut `streamBldr` and `singleChildSV` respectively.  

<br/>

## Features

- Speeds up development
- Eliminates boilerplate
- Supports complex widgets (Eg: Custom Clipper and Custom Paint)

<br/>

<p align="center">
<a href="https://newsletter.neevash.dev/" target="_blank"><img width="700px" src="https://i.ibb.co/L8GY3D5/the-flutter-bi-weekly.png"/></a>
</p>

&nbsp;

| Shortcut   | Expanded                 | Description                                                                                                                                                                             |
| ---------- | ------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `statelessW`    | Stateless Widget         | Creates a Stateless widget                                                                                                                                                              |
| `statefulW`    | Stateful Widget          | Creates a Stateful widget                                                                                                                                                               |
| `build`      | Build Method             | Describes the part of the user interface represented by the widget.                                                                                                                     |
| `initS`     | InitState                | Called when this object is inserted into the tree. The framework will call this method exactly once for each State object it creates.                                                   |
| `dis`      | Dispose                  | Called when this object is removed from the tree permanently. The framework calls this method when this State object will never build again.                                            |
| `reassemble`     | Reassemble               | Called whenever the application is reassembled during debugging, for example during hot reload.                                                                                         |
| `didChangeD`      | didChangeDependencies    | Called when a dependency of this State object changes                                                                                                                                   |
| `didUpdateW`      | didUpdateWidget          | Called whenever the widget configuration changes.                                                                                                                                       |
| `customClipper`       | Custom Clipper           | Used for creating custom shapes                                                                                                                                                         |
| `customPainter`       | Custom Painter           | Used for creating custom paint                                                                                                                                                          |
| `listViewB`      | ListView.Builder         | Creates a scrollable, linear array of widgets that are created on demand.Providing a non-null `itemCount` improves the ability of the `ListView` to estimate the maximum scroll extent. |
| `listViewS`    | ListView.Separated | Creates a fixed-length scrollable linear array of list 'items' separated by list item 'separators'. |
| `gridViewB`    | GridView.Builder | Creates a scrollable, 2D array of widgets that are created on demand. Providing a non-null `itemCount` improves the ability of the `GridView` to estimate the maximum scroll extent. |
| `gridViewC`      | GridView.Count         | Creates a scrollable, 2D array of widgets with a fixed number of tiles in the cross axis. 
| `gridViewE`      | GridView.Extent         | Creates a scrollable, 2D array of widgets with tiles that each have a maximum cross-axis extent. 
| `customScrollV`      | Custom ScrollView        | Creates a `ScrollView` that creates custom scroll effects using slivers. If the `primary` argument is true, the `controller` must be null.                                              |
| `streamBldr`      | Stream Builder           | Creates a new `StreamBuilder` that builds itself based on the latest snapshot of interaction with the specified `stream`                                                                |
| `animatedBldr`    | Animated Builder         | Creates an Animated Builder. The widget specified to `child` is passed to the `builder`                                                                                                 |
| `statefulBldr` | Stateful Builder         | Creates a widget that both has state and delegates its build to a callback. Useful for rebuilding specific sections of the widget tree.                                                 |
| `orientationBldr`  | Orientation Builder      | Creates a builder which allows for the orientation of the device to be specified and referenced                                                                                         |
| `layoutBldr`  | Layout Builder           | Similar to the `Builder` widget except that the framework calls the builder function at layout time and provides the parent widget's constraints.                                       |
| `singleChildSV`     | Single Child Scroll View | Creates a scroll view with a single child                                                                                                                                               |
| `futureBldr`   | Future Builder           | Creates a Future Builder. This builds itself based on the latest snapshot of interaction with a Future.                                                                                 |
| `nosm`   | No Such Method           | This method is invoked when a non-existent method or property is accessed. |
| `inheritedW`   | Inherited Widget          | Class used to propagate information down the widget tree. |
| `mounted`   | Mounted  | Whether this State object is currently in a tree. |
| `snk`   | Sink  | A Sink is the input of a stream. |
| `strm`   | Stream  | A source of asynchronous data events. A stream can be of any data type. |
| `subj`   | Subject  | A BehaviorSubject is also a broadcast StreamController which returns an Observable rather than a Stream. |
| `toStr`   | To String  | Returns a string representation of this object. |
| `debugP`   | Debug Print  | Prints a message to the console, which you can access using the flutter tool's `logs` command (flutter logs). |
| `importM`    | Material Package | Import Material package.
| `importC`    | Cupertino Package | Import Cupertino package.
| `importFT`    | flutter_test Package | Import flutter_test package.
| `importAL`  | App localisation | Allows for the importation of app_localisation following [generation](https://docs.flutter.dev/development/accessibility-and-localization/internationalization).
| `mateapp`    | Material App | Create a new Material App.
| `cupeapp`    | Cupertino Package | Create a New Cupertino App.
| `tweenAnimationBuilder`    | Tween Animation Builder | Widget builder that animates a property of a Widget to a target value whenever the target value changes.
| `valueListenableBuilder`    | Value Listenable Builder | Given a ValueListenable<T> and a builder which builds widgets from concrete values of T, this class will automatically register itself as a listener of the ValueListenable and call the builder with updated values when the value changes.
| `f-group`    | Group | Create a group test function.
| `f-test`    | Test | Create a test function.
| `f-testWidgets`    | Test Widgets | Create a testWidgets function.

<br/>

## Requirements

Vscode: `1.56.0`

## Known Issues

At this time, there are no known issues. If you discover a bug or would like to see a shortcut added, please create a pull request at our GitHub page.

## Release Notes

### 4.0.0

- **Breaking: Change `testWdigets` to `f-testWidgets` to better align with function snippets**
- Support for `group` test function `f-group`
- Support for app localisation import `importAL`
- Support for Flutter 3
    - Migrate to super initialisers
    - Not on Flutter 3? The Flutter 2.xx branch is up to date and ready for you :)
- Fixed Lint issue - Added `const` to applicable widgets

### 3.0.3

- Use createState on statefulW snippet (Thank you [@marcossevilla](https://github.com/Nash0x7E2/awesome-flutter-snippets/commit/b18505ae59128ce8c2ff4cc60100603dc11259d5))

### 3.0.2

- Removed trailing whitespaces (Thank you [@leoshusar](https://github.com/Nash0x7E2/awesome-flutter-snippets/pull/45))
- Make widgets default to Container only (Thank you [@Ascenio](https://github.com/Nash0x7E2/awesome-flutter-snippets/pull/43))

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

Critical bug fixes: - Adjusted tab stops to improve efficiency and workflow - Removed blank Containers from builders in favor of a tab stop with semi-colon - Added trailing comma at the end of child parameter

### 1.0.4

- Fixed formatting
- Removed unused tabs
- Corrected spelling errors

### 1.0.3

Added support for: - Stream - Sink - Inherited Widget - Mounted - NoSuchMethod

### 1.0.2

Added support for: - Stateful Builder - Orientation Builder - Layout Builder - Single Child Scroll View - Future Builder

## 1.0.1

Added support for: - Stream Builder - Animated Builder - Custom Scroll View - Listview.Builder

### 1.0.0

Initial release of Awesome Flutter Snippets
