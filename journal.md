FlashPit

A diy 3d printed steering wheel and paddle setup.


# Day 1 - 
Made a basic steering wheel model.
![steering v1](https://hc-cdn.hel1.your-objectstorage.com/s/v3/e13646c0662973d28895bdcb4cd34937489918e3_screenshot_2025-04-29_at_12.17.41___am.png)

# Day 2,3 - 
Made the middle rod kinda thing and made its joints. 

![steering v1](https://hc-cdn.hel1.your-objectstorage.com/s/v3/168a2237d0dd289ba18ed3deebfaef5ba1373bc2_screenshot_2025-04-29_at_10.42.56___pm.png)
![steering v1](https://hc-cdn.hel1.your-objectstorage.com/s/v3/6915d83101760e254f7d72160301b2df9e740bb1_screenshot_2025-04-29_at_10.42.45___pm.png)

# Day 4 - 
Completed the cadding of the steering wheel and made a logo for it!
<br>
![steering v1](https://hc-cdn.hel1.your-objectstorage.com/s/v3/4586c4cbe92fb2565290c0f55cd18f436b40894e_screenshot_2025-05-03_at_11.29.14___pm__1_.png)
![steering v1](https://hc-cdn.hel1.your-objectstorage.com/s/v3/bdcaddd59bea0f635881cc112b65a657ff887564_screenshot_2025-05-03_at_11.26.46___pm.png)
![steering v1](https://hc-cdn.hel1.your-objectstorage.com/s/v3/a2f27c057b4a908347a7bd489e1af4ea03c4e6e6_screenshot_2025-05-03_at_11.13.19___pm__1_.png)

# Day 5
Made rod system for the steering wheel.
I was a lil busy, but somehow managed to do a little work. So yeah, i decided to use wood for the base of the steering wheel which will bear all the electronics, reason - pla is not that hard/heavy, wood is. 
![steering com](https://hc-cdn.hel1.your-objectstorage.com/s/v3/6aa589e2254cbba159f0250b9fdb8c02d9370aa1_screenshot_2025-05-05_at_12.44.11___am.png) 
![steering com](https://hc-cdn.hel1.your-objectstorage.com/s/v3/cd747a69a4780011bf3ca64dfdc2f4de52a02466_screenshot_2025-05-05_at_12.44.27___am.png) 
![steering com](https://hc-cdn.hel1.your-objectstorage.com/s/v3/2e5a32f9089ec7e8b5843c9da62151469a4dd96f_screenshot_2025-05-05_at_12.45.42___am.png)

# Day 6
Did some little work today and made a cad model for the pedals (brake, accelerator). Also did some research today and setttled on using a ky-040 rotary encoder with 80 and 16 tooth gt2 pulleys, why? coz the encoders send pulses to the arduino for every revolution they make, so the PPR of this encoder is 20, means that it sends 20 pulses per revolution. Which is kinda low, see this thing as FPS, so yeah its PPR was pretty low which will give a sort of "laggy" feel while using it. The encoders with 100< are suitable for smooooth working but they are pretty much out of my budget. So did a lil hack, i made a pulley system rather than connecting the rod directly to the encoder's shaft. So the rod will have a gt2 pulley with 80 teeth and the encoder will have a 16 teeth gt2 pulley, so the 16 teeth pulley will make 5 revolutions for every rotation made by the 80 teeth pulley (80/16 = 5). So this way the encoder will rotate 5 times for every rotation the steering makes (5x the previous one time). So yeah this way the PPR of the encoder became 5x (20*5 = 100), which is 100 PPR, the desired configuration. Yeah thanks im a genius ik. 
Also decided to use wooden boards with clamps as the base rather than the 3d printed box, as wood is heavier/stronger. 
I also figured out the way to make the accelerator and the break to work without using the potentiometers, for which i'll have to sell my soul to pay, the thing is LITERALLY 10K PER PIECE??
So yeah i decided to use analog hall sensors with hinges and springs for it, hall sensors simply measure magnetic field, so i'll stick a magnet to the pedal base and a sensor to the base' top, so this way it will have precise observations + its really cheap(20 inr per piece) + i already have magnets for it.

![pedals](https://hc-cdn.hel1.your-objectstorage.com/s/v3/54fdb20722f017046dcfc2d85e59512dd548b5b0_screenshot_2025-05-05_at_8.23.36___pm.png)
