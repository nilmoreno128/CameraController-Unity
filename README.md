# Simple Camera Controller
A Unity asset providing smooth and customizable camera controls for 3D games, including the ability to follow specific objects upon clicking them.

## Features
- **Smooth Camera Movement**: Control the camera with mouse and keyboard input.
- **Plug-and-Play**: Simple integration—drag and drop into your scene.
- **Customizable Settings**: Easily adjust speed and position limits.
- **Follow Objects**: Configure objects to be followable.

## Installation
1. Download the `CameraController.unitypackage` file from this repository.
2. Open your Unity project and navigate to **Assets > Import Package > Custom Package**.
3. Select the `CameraController.unitypackage` file and click **Import**.

## How to Use
1. Import the asset as described above.
2. Drag the `CameraController` prefab into your scene.
3. Configure the camera in the **Inspector**:
   - Adjust movement speed and limits.

### Configuring Followable Objects
To enable the "follow object" feature:
1. Attach the `CameraFollowController` script to any object you want the camera to follow.
2. When the object is clicked during gameplay, the camera will dynamically track it
