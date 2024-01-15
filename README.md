<p align="center"><img src="./res/icon/melon_128x128.png"></p>
<h1 align="center"><b>melonDS: Metroid Prime Hunters</b></h1>
<br>
    
Modded version of melonDS emulator to play Metroid Prime Hunters.

It's a bit of a hack but the goal is to make the game as fun as possible using mouse and keyboard.

I originally made this for controller but because there's no lock-on, it wasn't really fun to play.

### Instructions

-   Make sure to set all bindings to `None` in<br>
    `Config → Input and hotkeys → DS keypad`<br>
    _(click binding and press backspace)_

-   Game sensitivity lowest, headphones optionally

-   Find Metroid Prime Hunters related `Keyboard mappings` in<br>
    `Config → Input and hotkeys → Add-ons`<br>
    Recommended defaults have already been set, but feel free to change if you need to

    Notes:

    -   Pressing the window will capture your mouse. Use `ESC` to uncapture.
    -   The stylus gets places in the middle of the screen which can cause accidental presses
    -   Whilst holding virtual stylus button `Tab`, use your mouse to click around on the touchscreen
    -   Left and right mouse button are the same
    -   UI OK `F` will press "OK" on the touch screen, which will also jump and briefly break aiming
    -   UI left and right will also press on the touch screen, for scan visor messages
    -   When in map view, press `Shift` to zoom out and `LMB` to zoom in

    <br>
    ![](./metroid/keyboard.png)

-   When in-game, **make sure to set the aim sensitivty to the lowest!**<br>
    _Also recommended to set audio to stereo_

### Optional recommended instructions

-   Enable JIT to improve performance<br>
    `Config → Emu settings → CPU emulation → Enable JIT recompiler`

-   Render game at a high resolution<br>

    -   Disable `Config → Screen filtering`<br>
    -   `Config → Video settings`<br>
        Set `3D renderer` to `OpenGL`<br>
        Disable `VSync` for lower latency<br>
        Set `Internal resolution` to next highest for your monitor

-   My recommended screen layout<br>
    `Config → Screen layout → Horizontal`<br>
    `Config → Screen sizing → Emphasize top`<br>

-   Bind `Toggle fullscreen` to `F11` or something else<br>
    `Config → Input and hotkeys → General hotkeys`
