# MonkeyFinder

MonkeyFinder is a cross-platform mobile application built with .NET MAUI. It allows users to browse and explore information about various monkey species.

![2024-09-11_14h52_56](https://github.com/user-attachments/assets/6a849f98-c24b-48c0-9e9c-4e80f2a445ff)

## Features

- View a list of monkey species
- See detailed information about each monkey
- Cross-platform support (iOS, Android, Windows)

## Prerequisites

- .NET 6.0 SDK or later
- Visual Studio 2022 or later with the .NET MAUI workload installed

## Getting Started

1. Clone the repository
2. Open the solution in Visual Studio
3. Build and run the application on your desired platform (iOS, Android, or Windows)

## Project Structure

- `MonkeyFinder/`: Main project folder
  - `Platforms/`: Platform-specific code
  - `Resources/`: Application resources (images, icons)
  - `View/`: XAML views
  - `ViewModel/`: View models
  - `Model/`: Data models
  - `Services/`: Business logic and data services

## Key Files

- `AppShell.xaml`: Defines the application's shell and navigation structure
- `MainPage.xaml`: The main page of the application
- `DetailsPage.xaml`: Page for displaying detailed information about a monkey

## Configuration

The application uses various configuration files for different platforms:

- Windows: `Package.appxmanifest`
- Android: `AndroidManifest.xml` (not shown in the provided code snippets)
- iOS and MacCatalyst: Configuration is handled in the respective `Info.plist` files (not shown in the provided code snippets)

## Permissions

The application requires the following permissions:

- Internet access
- Location access (coarse and fine)

These permissions are declared in the `AssemblyInfo.cs` file for Android:
