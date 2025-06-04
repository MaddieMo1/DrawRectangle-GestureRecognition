# Draw Rectangle & Gesture Recognition Unity Package

This repository contains a small Unity example packaged as a `.unitypackage`. It demonstrates how to draw a selection rectangle on screen, select objects and recognize simple mouse gestures.

## Package Contents

The package includes the following key files:

- `Assets/ZH/Scripts/ECS04/DrawRectangle_ZH.cs` – draws a rectangle on screen, handles selection and implements basic gesture commands.
- `Assets/ZH/Scripts/ECS04/手势识别/GestureRecognition_ZH.cs` – tracks mouse movement to recognize four simple directions (up, down, left, right).
- `Assets/Scenes/ECS04.unity` – example scene that shows the scripts in action.
- Several materials under `Assets/ZH/Materials` used for visualization.

## How to Use

1. Open an existing Unity project or create a new one.
2. From the menu choose **Assets → Import Package → Custom Package...**
3. Select `Unity 屏幕线框绘制、物体选择、手势识别.unitypackage` from this repository and import all assets.
4. Open the scene `Assets/Scenes/ECS04.unity` and press Play.
5. Try dragging with the mouse to draw a rectangle, select objects and test the gesture recognition (move the mouse up, down, left or right).

## Further Learning

The project can be used as a starting point to explore:

- Expanding the gesture recognition logic with more complex algorithms (e.g. `$1 Recognizer`).
- Improving the selection behaviour or adding object manipulation in `MoveVrithmetic()` inside `DrawRectangle_ZH.cs`.
- Understanding how Unity's `GL` class works in `OnPostRender()` for custom drawing.

Feel free to adapt the scripts and scene to fit your own needs. The code is relatively small and easy to modify.

