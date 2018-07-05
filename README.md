# Awesome Flutter Snippets 
Awesome Flutter Snippets is a collection of commonly used Flutter classes and methods. It increases your speed of development by eliminating most of the boilerplate code associated with creating a widget. Widgets such as `Stateless` and `Stateful` can be created by typing the shortcut `stlss` and `stful` respectively.
<br>
## Features
- Speeds up development 
- Eliminates boilerplate 
- Supports complex widgets (Eg: Custom Clipper and Custom Paint)
<br>

| Shortcut | Expanded              | Description                                                                                                                                                                             |
| -------- | --------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| stlss    | Stateless Widget      | Creates a Stateless widget                                                                                                                                                              |
| stful    | Stateful Widget       | Creates a Stateful widget                                                                                                                                                               |
| bld      | Build Method          | Describes the part of the user interface represented by the widget.                                                                                                                     |
| init     | InitState             | Called when this object is inserted into the tree. The framework will call this method exactly once for each State object it creates.                                                   |
| dis      | Dispose               | Called when this object is removed from the tree permanently. The framework calls this method when this State object will never build again.                                            |
| rasm     | Reassemble            | Called whenever the application is reassembled during debugging, for example during hot reload.                                                                                         |
| dcd      | didChangeDependencies | Called when a dependency of this State object changes                                                                                                                                   |
| duw      | didUpdateWidget       | Called whenever the widget configuration changes.                                                                                                                                       |
| cc       | Custom Clipper        | Used for creating custom shapes                                                                                                                                                         |
| cp       | Custom Painter        | Used for creating custom paint                                                                                                                                                          |
| lsb      | ListView.Builder      | Creates a scrollable, linear array of widgets that are created on demand.Providing a non-null `itemCount` improves the ability of the `ListView` to estimate the maximum scroll extent. |
| csv      | Custom Scroll View    | Creates a `ScrollView` that creates custom scroll effects using slivers. If the `primary` argument is true, the `controller` must be null.                                              |

<br>

## Requirements
Vscode: "^1.24.0"
<br>
## Known Issues
At this time, there are no known issues. If you discover a bug or would like to see a shortcut added, please create a pull request at our GitHub page. 

## Release Notes

### 1.0.0
Initial release of Awesome Flutter Snippets 
