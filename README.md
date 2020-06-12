# vss-conky
My personal conky setup, with date, 12-hr time, CPU and RAM usage.

Based on AweGuy22's [simple-conky-clock](https://github.com/AweGuy22/simple-conky-clock). Uses Product Sans font by default—install link [here](https://befonts.com/product-sans-font.html).

Runs on my secondary display by default. To adjust:
- If you have multiple displays, adjust the xinerama_head option to get it on the display of your choice.
- If you have a single display, removing the xinerama_head option altogether should make it show up on your main display.

Issues:
- If placed on the primary display, the information is partially obscured by the dock in Ubuntu—adjust the gap_x option.

Example:
![example](https://raw.githubusercontent.com/vicksahni/vss-conky/master/example_display.png)
