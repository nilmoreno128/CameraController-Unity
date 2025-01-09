# Simple Camera Controller
A Unity asset providing a basic camera control system for 3D games.

## Features
- Smooth camera movement using the mouse and the keyboard.
- Customizable settings for speed and boundaries.
  
## Installation
1. Download the `CameraController.unitypackage` file from this repository.
2. Open Unity and go to **Assets > Import Package > Custom Package**.
3. Select `CameraController.unitypackage` and click **Import**.

## How to Use
1. After importing, drag the `CameraRig` prefab into your scene.
2. Adjust the properties in the Inspector:
   - Rotation speed.
   - Position boundaries.

### Example Code
```csharp
public class ExampleUsage : MonoBehaviour {
    void Start() {
        Debug.Log("Camera Controller is ready to use!");
    }
}
