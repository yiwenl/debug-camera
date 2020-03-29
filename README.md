# debug-camera
Tool function to show the frustum of the camera 

![Demo](demo.png)


### Usage 
`DebugCamera(camera, color/*optional*/)`


### Example
```
import DebugCamera from 'debug-camera'

...

render() {
  ...
  DebugCamera(this.camera, [1, 0, 0])
}
```