# DMRV-Gamepad-Skin
A skin i made for the dual shock 4 viewer at https://gamepadviewer.com/

All source images are from https://gamepadviewer.com/ and i did not make them myself.

## How to add the skin
just copy the contents of `theme.css` and paste it to `Custom CSS` section of the browser scene with the gamepad.
Paste the values after everything that is already there (after all of the obs defaults)

`theme.css`:
```css
.controller.ds4{
  background-image: url(https://raw.githubusercontent.com/MatteoGodzilla/DMRV-Gamepad-Skin/main/base-edit.svg);
}

.ds4 .button{
  background-image: url(https://raw.githubusercontent.com/MatteoGodzilla/DMRV-Gamepad-Skin/main/face-edit.svg);
}

.ds4 .face {
  background-image: url(https://raw.githubusercontent.com/MatteoGodzilla/DMRV-Gamepad-Skin/main/dpad-edit.svg);
}

.ds4 .bumper{
  background-image: url(https://raw.githubusercontent.com/MatteoGodzilla/DMRV-Gamepad-Skin/main/bumper-edit.svg);
}
```
