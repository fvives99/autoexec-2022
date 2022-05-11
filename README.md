## Launch Options

| **Command**  | **Description** |
| ------------- | ------------- |
| `-dev`  | Animations won’t be there anymore but can cause issues in performance. Disable/Remove this if you encounter problems. I personally do not recommend this setting. You should use this one at your own risk.|
| `+exec`  | Executes a cfg file on startup  |
| `-fullscreen` | The game will always launch in Fullscreen Mode. This is recommended if your windows keep re-adjusting to borderless Fullscreen or any other setting. |
| `-windowed` | The game will always launch in Windowed Mode. This is up to preference.
| `+cl_showfps 4` | Shows FPS in-game. This can also be achieved with steam overlay settings, NVIDIA, or RTSS.|


## Autoexec
1. Go to the games directory. (Usually in C:\Program Files (x86)\Steam\steamapps\common\Apex Legends\cfg)
2. Create there a new file called "autoexec.cfg" (without the Quotation marks)
3. Paste everything from [autoexec](https://raw.githubusercontent.com/deaFPS/apex-configs-by-deafps/master/autoexec.cfg) in it.
4. Rightclick on the game inside of Steam and go to "Properties".
5. Add the Launch Option "+exec autoexec.cfg" (without the Quotation marks)

## Superglide
Create 3 superglide.cfg files, each one named as follows:
> superglide1
> superglide2
> superglide2

### superglide1 file commands

- bind "CAPSLOCK" "+jump; exec superglide2.cfg" 0

- bind "MWHEELDOWN" "+jump" 0

If you're using scroll down as jump for b-hop replace with:

- bind "MWHEELDOWN" "+jump; +forward" 0

If that doesnt work in the autoexec.cfg, remove "//" infront of the command below to take effect 

- bind "mwheeldown" "+jump; +forward"	
### superglide2 file command

- bind "MWHEELDOWN" "+jump; fps_max 30; exec superglide3.cfg" 0

### superglide3 file command

- bind "MWHEELDOWN" "+duck; fps_max 190; exec superglide1.cfg" 0

## Videoconfig
1. [Copy](https://raw.githubusercontent.com/fvives99/autoexec-2022/main/Videoconfig/videoconfig.txt) videoconfig.txt
2. Paste this inside existing videoconfig.txt located in: "%USERPROFILE%\Saved Games\Respawn\Apex\local"
3. Make the file read-only by right click, properties, check Read-only attribute and hit apply.
