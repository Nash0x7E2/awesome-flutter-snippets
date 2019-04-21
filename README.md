# Awesome Flutter Snippets 
Awesome Flutter Snippets is a collection of commonly used Flutter classes and methods. It increases your speed of development by eliminating most of the boilerplate code associated with creating a widget. Widgets such as `StreamBuilder` and `SingleChildScrollView` can be created by typing the shortcut `streamBldr` and `singleChildSV` respectively.
<br>
## Features
- Speeds up development 
- Eliminates boilerplate 
- Supports complex widgets (Eg: Custom Clipper and Custom Paint)
<br>

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
| `customScrollV`      | Custom ScrollView        | Creates a `ScrollView` that creates custom scroll effects using slivers. If the `primary` argument is true, the `controller` must be null.                                              |
| `streamBldr`      | Stream Builder           | Creates a new `StreamBuilder` that builds itself based on the latest snapshot of interaction with the specified `stream`                                                                |
| `animatedBldr`    | Animated Builder         | Creates an Animated Builder. The widget specified to `child` is passed to the `builder`                                                                                                 |
| `statefulBldr` | Stateful Builder         | Creates a widget that both has state and delegates its build to a callback. Useful for rebuilding specific sections of the widget tree.                                                 |
| `oriantationBldr`  | Orientation Builder      | Creates a builder which allows for the orientation of the device to be specified and referenced                                                                                         |
| `layoutBldr`  | Layout Builder           | Similar to the `Builder` widget except that the framework calls the builder function at layout time and provides the parent widget's constraints.                                       |
| `singleChildSV`     | Single Child Scroll View | Creates a scroll view with a single child                                                                                                                                               |
| `futureBldr`   | Future Builder           | Creates a Future Builder. This builds itself based on the latest snapshot of interaction with a Future.                                                                                 |
| `nosm`   | No Such Method           | This method is invoked when a non-existent method or property is accessed. |
| `inheritedW`   | Inherited Widget          | Class used to propagate information down the widget tree. |
| `mounted`   | Mounted  | Whether this State object is currently in a tree. |
| `snk`   | Sink  | A Sink is the input of a stream. |
| `strm`   | Stream  | A source of asynchronous data events. A stream can be of any data type. |
| `toStr`   | To String  | Returns a string representation of this object. |
| `debugP`   | Debug Print  | Prints a message to the console, which you can access using the flutter tool's `logs` command (flutter logs). |
| `importM`    | Material Package | Import Material package.
| `importC`    | Cupertino Package | Import Cupertino package.
| `mateapp`    | Material App | Create a new Material App.
| `cupeapp`    | Cupertino Package | Create a New Cupertino App.

<br>

## Requirements
Vscode: "^1.24.0"

<br>

## Known Issues
At this time, there are no known issues. If you discover a bug or would like to see a shortcut added, please create a pull request at our GitHub page. 

## Release Notes

### 2.0.2
- Resolved issue  [#6](https://github.com/Nash0x7E2/awesome-flutter-snippets/issues/6)

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
Critical bug fixes:
- Adjusted tab stops to improve efficiency and workflow 
- Removed blank Containers from builders in favor of a tab stop with semi-colon
- Added trailing comma at the end of child parameter

### 1.0.4
- Fixed formatting 
- Removed unused tabs
- Corrected spelling errors 


### 1.0.3
Added support for: 
-  Stream
-  Sink
-  Inherited Widget
-  Mounted
-  NoSuchMethod


### 1.0.2 
Added support for: 
-  Stateful Builder
-  Orientation Builder 
-  Layout Builder
-  Single Child Scroll View
-  Future Builder


## 1.0.1 
Added support for: 
-  Stream Builder 
-  Animated Builder 
-  Custom Scroll View 
-  Listview.Builder

### 1.0.0
Initial release of Awesome Flutter Snippets 
