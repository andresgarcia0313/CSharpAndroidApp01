# CSharp Android App

This is a basic Xamarin Android project that displays a "Hello World" message on an Android device or emulator.

## Prerequisites

- [Visual Studio Code](https://code.visualstudio.com/)
- [.NET SDK](https://dotnet.microsoft.com/download)
- [Xamarin for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp)

## Project Setup

1. Clone this repository: `git clone [REPOSITORY_URL]`
2. Navigate to the project folder: `cd App`
3. Open the project in Visual Studio Code: `code .`

## Build and Run

To build and run the project, ensure you have an Android emulator running or a connected physical device. Then, execute the following commands:

```bash
avdmanager list avd
emulator -avd Pixel_7_Pro_API_33
dotnet build
dotnet run
```

This will display the "Hello World" message on the emulator or device screen.

## Project Structure

- `MainActivity.cs`: Contains the main logic of the Android application.
- `Resources/layout/Main.axml`: User interface layout.

## Contributing

Feel free to contribute to this project. Open an issue or submit a pull request!
