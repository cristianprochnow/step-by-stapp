# Step by StApp
📱 First app with Flutter, featuring the famous and so loved number counter!

# 📚 What I Learned

## Folders

### `.dart_tool/` & `.idea/`
Folders for workspace and environment configuration. They are folders that we commonly not change content, so, at this moment, let these untouched.

### `android/` & `ios/` & `web/` & `windows/`
Folders with configuration and additional content for Flutter build into these systems. Here you'll add settings to interact with OS core and deeper functionalities.

### `lib/`
Here is where the magic happens 🧙🏼‍♂️. The code you'll write will be here.

## Functions

### `runApp()`
This is the function that runs your Flutter app inside SDK. Without this, process will not be initiated.

After import design package from Flutter (i.e. `import 'package:flutter/material.dart';`) you're able to call `runApp()` and start development.

As params it receives your master Widget, where your application is within.

## Concepts

### Widget
Basically, all we see (and also what we not see, at some moments, but we'll talk about this later) within a Flutter app is a widget. Since a button until the whole screen.

For start a screen, we can set `Container()` component as master component and then start all the magic putting inside it the widgets.

## Tricks

### Reset OS configs
If in some situation you desire reset the configuration applyed at OS folders, you can simply run `flutter create .` inside your app root directory after delete OS folders.
