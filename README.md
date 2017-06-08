This is a fork of Otacon's CX10-WD drone control software [here](https://github.com/Otacon/wifi_china_drone_controller)

The plan is to fix errors then port this project to a different language


# README #

This is a sample application to control Cheerson CX10-WD drone from desktop using keyboard or a XInput Device (i.e. XBoxController)

Download from [Here](https://drive.google.com/open?id=0B1mGvcEpWz16aE9Sd3gzQnoxMk0) the Latest version

### Stream/Record Video ###

In order to stream or record video you need to download [FFPLAY and FFMPEG](https://ffmpeg.org/download.html) for your platform and
put the two binaries (ffmpeg and ffplay) contained in the archive in the same folder of the drone_protocol.jar.
i.e.

C:\users\sample\Desktop\cx10\ will contain
* drone_protocol.jar
* ffmpeg.exe
* ffplay.exe

or on MacOSX/Linux
/users/sample/Desktop/cx10/ will contain
* drone_protocol.jar
* ffmpeg
* ffplay


### Keyboard Controls ###

* Up arrow = Take Off
* Down arrow = Land
* W, A, S, D = forward, backward, strafe
* I, J, K, L = altitude, yaw (turning)
