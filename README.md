# Free Camera Controller  
A Unity asset designed to provide smooth and customizable free camera controls for 3D games. It includes the ability for the camera to dynamically follow specific objects when clicked, allowing for an intuitive and interactive player experience.

## Features  
- **Smooth Camera Movement**: Control the camera with mouse and keyboard inputs, offering a smooth and responsive experience.  
- **Plug-and-Play**: Quick and simple integration—just drag and drop the prefab into your scene and it’s ready to use.  
- **Customizable Settings**: Easily adjust movement speed, camera rotation limits, and position boundaries to fit the needs of your game.  
- **Follow Objects**: Enable the camera to automatically track specific objects in your scene when clicked, creating a more interactive and engaging gameplay experience.

## Installation  
1. Download the `CameraController.unitypackage` file from this repository.  
2. Open your Unity project and go to **Assets > Import Package > Custom Package**.  
3. Select the `CameraController.unitypackage` file and click **Import**.  

## How to Use  
1. Import the asset as described above.  
2. Drag the `CameraController` prefab into your scene to add the camera.  
3. Adjust the camera settings in the **Inspector** to customize the movement speed, rotation limits, and other parameters.  
4. To make objects followable:
   - Attach the `CameraFollowController` script to any object you want the camera to track.  
   - Click the object during gameplay, and the camera will follow it, offering a dynamic and responsive view of the action.
