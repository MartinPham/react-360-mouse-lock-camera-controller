# @martinpham/react-360-mouse-lock-camera-controller

Provide Pointer Lock Camera Controller for your React 360 project. Now you can rotate camera inside 3D world freely using your mouse moves.

## Demo

[Chess world](https://martinpham.github.io/react-360-keyboard-camera-controller/)


## Installing

```sh
yarn add @martinpham/react-360-mouse-lock-camera-controller
```

## Integrating

```sh
import MouseLockCameraController from '@martinpham/react-360-mouse-lock-camera-controller';

...

r360.controls.addCameraController(new MouseLockCameraController(r360._eventLayer));
```

