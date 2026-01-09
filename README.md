# Unity VR/XR Project

## Description
This is a Unity-based VR/XR project developed as part of a major academic project at RVITM.

## Quick Start - APK Installation
If you just want to run the application without Unity:

1. Download the APK file from the repository
2. Transfer it to your Android device
3. Enable "Install from Unknown Sources" in your device settings
4. Install the APK
5. Launch the application

**Note:** This is an Android VR/XR application and may require a VR-compatible Android device.

## Prerequisites
- Unity Editor (2021.3 or later recommended)
- Git
- Windows OS
- VR Headset (if testing VR features)

## Installation

### Clone the Repository
```bash
git clone <repository-url>
cd project
```

### Open in Unity
1. Open Unity Hub
2. Click "Add" and select the project folder
3. Open the project with a compatible Unity version
4. Wait for Unity to import all assets and packages

## Project Structure
```
Assets/
├── MultiSet/          # Custom assets and scripts
├── Resources/         # Runtime resources
├── Scenes/           # Unity scenes
├── TextMesh Pro/     # TextMesh Pro assets
└── XR/               # XR/VR related assets

Packages/             # Package dependencies (managed by Unity)
ProjectSettings/      # Project configuration
```

## Features
- XR/VR Integration
- Input System implementation
- Custom scene management
- TextMesh Pro integration

## How to Use
1. Open the project in Unity
2. Navigate to `Assets/Scenes/` to find available scenes
3. Double-click a scene to open it
4. Press the Play button in Unity Editor to test

## Development

### Adding New Scenes
- Create scenes in `Assets/Scenes/` folder
- Add to build settings via File → Build Settings

### Input Configuration
- Input actions are configured in `InputSystem_Actions.inputactions`
- Modify using the Input Actions editor window

## Building the Project

### Pre-built APK
A pre-built APK file is available in the repository for direct installation on Android devices.

### Building from Source
1. Go to File → Build Settings
2. Select Android as your target platform
3. Configure player settings (File → Build Settings → Player Settings)
4. Click "Build" to generate a new APK or "Build and Run" to deploy directly to a connected device

## Technologies Used
- Unity Engine
- Unity XR Plugin System
- Unity Input System
- TextMesh Pro

## Contributors
- MOKSHITH KY GOWDA

## License
[Add your license here]

## Acknowledgments
- RVITM (RV Institute of Technology and Management)

## Support
For issues or questions, please open an issue in the repository.

---
*This project was developed as part of a major project at RVITM*
