# Stenography keyboard using a Raspberry Pico

## Material

|Part|Amount|
|---|---|
|Raspberry Pico|1|
|[3D Printed bottom plate][bplate]|1|
|[3D Printed top plate][tplate]|1|
|MX style Switches|30|
|1N4148 Diodes|30|
|[Top row key capps][trow]|12|
|[Middle row key capps][mrow]|12|
|[Bottom row key capps][brow]|6|
|Screws|12|

## Build order

1. 3D print the parts ([top plate][tplate]/[bot plate][bplate]/key capps)
2. Flash the Raspberry Pico with the [prk_firmware][prk]
2.1 Go to [prk_firmware][prk]
2.2 Get the latest version
2.3 Drag and Drop the firmware onto the Pico (the firmware will auto mount)
3. Drag and Drop the [keymap.rb][keymap] onto the Pico
4. Assemble the printed [top plate][tplate] and the switches
5. Solder the switches and diodes ([circuit][circuit])
6. Connect the switches to the Pico ([circuit][circuit])
7. Put everything together
8. Use [Plover][plover] to convert QWERTY on the Steno Keyboard to Steno 


[bplate]: https://github.com/JoelNymark/Steno-Ruby-Pico/blob/main/Models/Steno%20Case/stenoboard_top.stl
[tplate]: https://github.com/JoelNymark/Steno-Ruby-Pico/blob/main/Models/Steno%20Case/stenoboard_top.stl
[trow]: https://github.com/JoelNymark/Steno-Ruby-Pico/blob/main/Models/Steno%20keycaps/keycap%20Top%20Row.stl
[mrow]: https://github.com/JoelNymark/Steno-Ruby-Pico/blob/main/Models/Steno%20keycaps/keycap%20Middle%20Row.stl
[brow]: https://github.com/JoelNymark/Steno-Ruby-Pico/blob/main/Models/Steno%20keycaps/keycap%20Bottom%20Row.stl

[prk]: https://github.com/picoruby/prk_firmware/releases
[keymap]: https://github.com/JoelNymark/Steno-Ruby-Pico/blob/main/Src/keymap.rb
[circuit]: https://github.com/JoelNymark/Steno-Ruby-Pico/blob/main/circuit.png
[plover]: https://www.openstenoproject.org/plover/
