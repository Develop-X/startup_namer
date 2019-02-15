# myapp

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.io/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.io/docs/cookbook)

For help getting started with Flutter, view our 
[online documentation](https://flutter.io/docs), which offers tutorials, 
samples, guidance on mobile development, and a full API reference.

### Observations
* Material app. Material is a visual design language that is standard on mobile and the web. Flutter offers a rich set of Material widgets.
* The main method uses fat arrow (=>) notation, Use fat arrow notation for one-line functions or methods.
* The app extends StatelessWidget, which makes the app itself a widget. In Flutter, almost everything is a widget, including alignment, padding, and layout.
* The Scaffold widget, from the Material library, provides a default app bar, a title, and a body property that holds the widget tree for the home screen. The widget subtree can be quite complex.
* A widget's main job is to provide a build method that describes how to display the widget in terms of other, lower-level widgets.
The body for this example consists of a Center widget containing a Text child widget. The Center widget aligns its widget subtree to the center of the screen.
* The pubspec file manages the assets for a Flutter app. In pubspec.yaml
* Stateless widgets are immutable, meaning that their properties can't change—all values are final.
* Stateful widgets maintain state that might change during the lifetime of the widget. Implementing a stateful widget requires at least two classes: 1) a StatefulWidget class that creates an instance of 2) a State class. The StatefulWidget class is, itself, immutable, but the State class persists over the lifetime of the widget.
* ListView's builder factory constructor allows you to build a list view lazily, on demand.
