# dual-picameras-on-RasPi5
dual picameras on Raspberry Pi5

1. Open a terminal and enter this command to use the camera connected to CAM 0. The command has two arguments. The first is the camera that we wish to use, the second is a delay timer. By default the command will show a preview for five seconds. Using -t 0, the preview window will not auto-close. Instead we need to close the preview window to exit.

libcamera-hello –camera 0 -t 0

2. Open a second terminal and enter this command to use the camera connected to CAM 0. The command has two arguments. The first is the camera that we wish to use, the second is a delay timer. By default the command will show a preview for five seconds. Using -t 0, the preview window will not auto-close. Instead we need to close the preview window to exit.

libcamera-hello –camera 1 -t 0

3. Check that both cameras are working correctly. You should see two preview windows on the desktop. Move the cameras to obtain the shot that you require.

4. Close the preview windows.

