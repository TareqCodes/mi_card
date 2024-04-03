# mi_card

A new Flutter project.

## Getting Started

This is a basic Flutter application code.
The main() function is the entry point of the application, which calls runApp() with MyApp as an argument.
MyApp is a stateless widget (it describes part of the user interface which can't change over time) that returns a MaterialApp widget. MaterialApp is a convenience widget that wraps a number of widgets that are commonly required for applications implementing Material Design.
In the build method, a MaterialApp widget is returned with a Scaffold as its home. Scaffold is a widget that implements the basic material design visual layout structure. It provides APIs for showing drawers, snack bars, and bottom sheets.
The Scaffold has a SafeArea widget as its body which makes sure the application does not overlap with the operating system interfaces. Within the SafeArea, a Column widget is used. A Column widget is a layout widget that arranges its children vertically.
Inside the Column widget, there are a series of widgets including a CircleAvatar (a circle that represents the user), two Text widgets (for displaying text with different styles), and two Container widgets (a convenience widget that combines common painting, positioning, and sizing widgets).
Each Container widget contains a Row widget (a layout widget that arranges its children horizontally) with an Icon widget (a graphical icon widget drawn with a glyph) and a Text widget, separated by a SizedBox widget (a box with a specified size) for spacing.
Overall, this basic Flutter application displays a user's profile picture, name, job title, and contact details in a neatly arranged layout, following the Material Design guidelines. It's a great starting point for building more complex Flutter applications.

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
