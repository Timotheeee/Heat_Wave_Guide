# Heat Wave Guide
a few tips and tricks to reduce gaming PC power consumption to make heat waves less annoying (mostly applicable for those with a high-end Nvidia GPU)

## The easiest one: limit FPS of games running in the background
Just do this:
<img src="https://github.com/Timotheeee/Heat_Wave_Guide/blob/main/fps%20limit.png?raw=true"/>

Now your PC won't use as much power when you tab out of a game. You can also limit FPS of active games to something that is only slightly higher than your monitor's refresh rate, as there's no point in rendering 400 fps if you can't see them.


## Monitoring power consumption
For the next part of the guide, I recommend installing HWmonitor so you can see if the changes actually make a difference: https://www.cpuid.com/softwares/hwmonitor.html

## Idle GPU power consumption
If you have a high-end Nvidia GPU and more than 1 monitor there is a good chance your GPU is using a lot of power (40-60W) while idling. This is because for some reason Nvidia cards don't go into power saver mode automatically on systems with multiple monitors. This can be fixed with this program: https://www.guru3d.com/files-details/nvidia-profile-inspector-download.html


after running it, right click the "show overclocking" button, click "multi display power saver" and set it up like this:

<img src="https://github.com/Timotheeee/Heat_Wave_Guide/blob/main/display.png?raw=true"/>

In my case, my GPU went from idling on 50W down to just 20W. You will have to disable this and then re-enable it every time you want to play a demanding game, because while it's active your GPU will run at a much lower frequency. (although if you play a game that's easy to run while power saver mode is active, your GPU will use a lot less power!)

## lowering CPU voltage
This one doesn't help much but if you don't mind losing a bit of performance during heat waves, you can underclock your CPU a bit and lower its voltage to reduce power consumption.

## play old games
If you're really desperate to keep your room cooler, play older games that don't use up your hardware as much, until the heat wave ends.
