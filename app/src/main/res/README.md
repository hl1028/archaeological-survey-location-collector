# Overview

This document provides a brief overview of the resources folder. This folder contains:

- Images
- Styles
- Colors
- Strings
- Layouts

## Changing the App Icon

To change the app icon, replace ic_launcher.png under all mipmap folders.

## Changing other icons used within the App

Any other icons and images that are used within the app will appear under the drawables folder. Replace all occurences of an icon or image to change it within the app.

## Style

The themes used within the app are present in styles.xml in the values folder.

## Colors

The color palette of the overall application, and other specific colors within the screens are defined in colors.xml under the values folder.

## Strings and Translations

The english strings are present at values/strings.xml. Turkish translations of the strings are present at values-tr/strings.xml.

To change a string, it would have to be changed in all strings.xml for every language.  A new language can be added parallel to the Turkish strings.

## Layouts

The XML layouts for all the screens are contained here.

- Splash screen
  - activity_splash.xml
  
- Finds and Paths list screen
  - activity_main.xml - The template for the screen. Defines the toolbar and the two floating action buttons for settings and new.
  - content_main.xml - The content that appears in the screen, which in this case is a list
  - bucket_list_entry.xml - The layout of each find that appears in the list
  - paths_list_entry.xml - The layout of each path that appears in the list

- Paths list screen
  - activity_

- Find entry screen
  - activity_data_entry.xml - The template for the screen containing the toolbar and placeholder for content
  - content_data_entry.xml - A scrollable layout with fields to take find input from the user
  - connection_settings_dialog.xml - Window containing field for configuring the Reach connection settings
  
- Path entry screen
  - activity_path_entry.xml - The template for the screen containing the toolbar and placeholder for content
  - content_data_entry.xml - A layout with fields to take path input from the user
  - connection_settings_dialog.xml
  
- Sync screen
  - activity_sync.xml - The template for the sync screen
