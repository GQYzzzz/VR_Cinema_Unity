## VR Cinema Social Environment (with VR headset)

### Author
- Qianyun Gong (UoN)
### Instruction
- Import the '.unitypackage' file into an unity 3D project.
- Import the 'XR Toolkit' to your project.
- Connect the VR headset to the project (e.g. Oculus Quest 2).
- Run the project in the headset and use the hand controllers to control your movement and play the video.

### How to test through mouse clicking?
1. In the canvas, change the ticked scrip from 'Tracked Device Graphic Raycaster' to the 'Graphic Raycaster'
![CanvasChange.png](resources%2FCanvasChange.png)


2. In the EventSystem, change the ticked scrip from 'XR UI Input Module' to 'Standalone Input Module'
![EventSystemChange.png](resources%2FEventSystemChange.png)


3. Click run and control the video player seen in the camera by mouse clicking.


### Demo
[VideoExample.mp4](resources%2FVideoExample.mp4)