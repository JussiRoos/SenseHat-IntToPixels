# Module to convert intigers (00-99) to pixel arrays which can be drawn to Sense HAT modules 8x8 pixel screen. 
**Put** `int_To_Pixels.py` in to your **project folder**.  
**Use** `from int_To_Pixels import intToPixels` To **import** the module to your code.  


Originally published at my former High Schools **[repo](https://github.com/Pohjois-Tapiolan-lukio/raspberry_pi-projects/tree/master/examples/sensehat/int_To_Pixels)**. I personally own te rights to this code so I'm creating a repo for it to be used again.  


Example of use:
```Python
# Exaple to print number 50 to Sense HAT modules screen in red color 

from sense_hat import SenseHat
from int_To_Pixels import intToPixels

sense = SenseHat()

# intToPixels(Intiger, foreground color as [R, G, B], background color as [R, G, B])
sense.set_pixels(intToPixels(50, [255, 0, 0], [0, 0, 0]))
```
