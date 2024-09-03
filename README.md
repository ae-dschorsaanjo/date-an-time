# Date an' Time
This is a webpage that shows the current date and time with customizable colors. Written specifically to be streamed to a TinyTV2 ("cover" mode through).

![example](https://github.com/user-attachments/assets/a9c95ca4-5f15-44e0-ba60-afcaa50646ff)

The date is displayed in YYYY-MM-DD (ISO) format and the time is hh:mm:ss (24h clock). The available colors all come from the [Dracula Color Scheme]()

## Keyboard Functions

- ` ` (space): pause the time
- `g`: switch to a random colors
- `f`, `b`, `h`: change the foreground, background or highlight color respectively. After pressing this, you can change the color by pressing `` ` ``, `-` or a number. (default: white, gray, pink)  
  Available colors:
  - `` ` ``: transparent
  - `1`: black
  - `2`: gray
  - `3`: white
  - `4`: red
  - `5`: orange
  - `6`: yellow
  - `7`: green
  - `8`: cyan
  - `9`: purple
  - `0`: pink
  - `-`: blue
- `r`: toggle automatic random colors; color scheme will change every 10 minutes (default: on)
- `y`: switch to predefined white-shadows-on-black color scheme (foreground and background are gray, highlight is white)
- `s`: change the scaling to better fit either the TinyTV2 or the PC (default: TinyTV2)
- `t`: toggle background; the background is a GIF with 1% opacity that changes every 0.5 seconds. This is here in case something requires "visible" changes more frequently than 1 second (default: off)
- `u`: toggle the HUD which displays the current state (default: off)

Besides these, you can also click on the date to show this README.

## License

This code is licensed under the BSC 3-clause license (see: [LICENSE](./LICENSE)).
The optionally displayed GIF is licensed under the CC0 license and can be found here: https://commons.wikimedia.org/wiki/File:Frequency_divider_animation.gif
