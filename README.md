# LEDcoffeecoaster
This is my first product that I used my 3D printer to print out the structure of the coaster. 
Materials use to create this product: 
- 9V battery
- Switch
- white LED strip light
- a couple of resistors (if needed) 

There are several ways to power up the device:
 - The first way, I thought about powering up this device is by using a voltage divider by setting the output of the LED stip light across the output of the 1.5K resistor. 
   The 1.2K ohh resistor will be connected in series with the 1.5K resistor. 
   But for this circuit configuration is for low current (1-30mA) application. 
   One of the problems I was facing is that the brightness of the LED was too dim. 
   So, I did some discovery that it takes 3 LEDS to draw approximateky 20mA from a 12V battery source. 
   So, I just use a small enough resistor to connect the LED strip light in series with the 9V battery source. Sure enough, it worked and the LED strip light is working at full capacity. 
   
