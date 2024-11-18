# sliding_up_panel_custom
[![pub package](https://img.shields.io/pub/v/sliding_up_panel_custom.svg)](https://pub.dartlang.org/packages/sliding_up_panel_custom)
[![GitHub Stars](https://img.shields.io/github/stars/SiKirillo/sliding_up_panel_custom.svg?logo=github)](https://github.com/SiKirillo/sliding_up_panel_custom)
[![Platform](https://img.shields.io/badge/platform-android%20|%20ios-green.svg)](https://img.shields.io/badge/platform-Android%20%7C%20iOS-green.svg)

**IMPORTANT:** This is a fork of [this](https://github.com/akshathjain/sliding_up_panel) with some new features. The goal is to keep it up to date with Dart language changes. If you have any suggestions for improvement, I will be glad to see you in pull requests.

A draggable Flutter widget that makes implementing a SlidingUpPanel much easier! Based on the Material Design bottom sheet component, this widget works on both Android & iOS.

<p>
  <img width="205px" alt="Example" src="https://raw.githubusercontent.com/SiKirillo/sliding_up_panel_custom/master/assets/example.gif"/>
  <img width="220px" alt="Example App Closed" src="https://raw.githubusercontent.com/SiKirillo/sliding_up_panel_custom/master/assets/exampleclosed.png"/>
  <img width="220px" alt="Example App Open" src="https://raw.githubusercontent.com/SiKirillo/sliding_up_panel_custom/master/assets/exampleopen.png"/>
</p>

<br>

## Differences
Main differences from the previous [sliding_up_panel](https://pub.dev/packages/sliding_up_panel) version:
- PanelController notify listener
- You can change the max height of the panel
- onAttached callback
- onPanelMaxHeightUpdated callback

## Installing
Add the following to your `pubspec.yaml` file:
```yaml
dependencies:
  sliding_up_panel: ^2.1.1+1
```

## How to use
Visit [this](https://pub.dev/packages/sliding_up_panel) to see detailed information on how to use this plugin