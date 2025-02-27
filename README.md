# RigCon
Extension Board for the ClockworkPI uConsole to connect ham radio equiptment

## Features
- Rig Interface similar to DigiRig
    - Audio interface
    - UART interface
    - PTT
- Additional external USB Port (500mA max)
- RTC

This project is heavily based on [DigiRig-mobile](https://github.com/softcomplex/Digirig-Mobile) (GNU GPL v3) to provide an audio, ptt and uart interface for digital modes for ham radio. The CM108 was replaced with an CM108B and the 2-port USB controller was replaced with a 4-port USB controller to accomodate the additional external USB Port. The pinout of the audio jacks, solder pads for configuration and test pins were reused 1:1 to allow an easy reuse of exisiting peripherals and support for a wide range of transceivers.
