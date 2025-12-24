# Termux Android Application

## Overview
This is the Termux Android application - a terminal emulator and Linux environment for Android devices.

## Project Structure
- **app/**: Main Android application
- **termux-shared/**: Shared library utilities
- **terminal-emulator/**: Terminal emulation core
- **terminal-view/**: Terminal UI view component
- **build.gradle**: Root build configuration
- **settings.gradle**: Gradle module configuration

## Build System
- Uses Gradle with Android Gradle Plugin 4.2.2
- Multi-module Android project
- Modules: `:app`, `:termux-shared`, `:terminal-emulator`, `:terminal-view`

## Development Setup
This is an Android/Kotlin project that requires:
- Java Development Kit (JDK)
- Android SDK (for full compilation)
- Android build tools

In Replit, you can:
- Review and edit source code
- Read the project documentation
- Analyze the architecture and code structure

To build a full APK, you would need a complete Android development environment with SDK installed.

## Key Technologies
- Language: Kotlin/Java
- Build Tool: Gradle
- Platform: Android
- Repository: https://github.com/termux/termux-app

## Recent Changes
- Project imported from GitHub (2025-12-24)
- Set up development environment in Replit
- Added right sidebar with Termux Info features (2025-12-24)
  - Three tabs: Info, Package Sources, Setup Guide
  - Displays Termux version, Android version, device info
  - Shows default package sources and quick setup instructions
  - Info button added to left sidebar header to toggle right sidebar

## New Features Added
### Right Sidebar (Info Drawer)
- **Location**: Right edge of terminal, toggled from info button next to settings
- **Tabs**:
  1. **Termux Info**: Shows app version, Android version, device model and CPU
  2. **Package Sources**: Lists default package sources and how to customize
  3. **Setup Guide**: Quick reference for common setup tasks (apt, SSH, Python, storage)
