# Night Vision Goggles
**In Short:** Created a set of binocular digital infrared night vision goggles inside of a rugged and water resistant frame.

IMG 5245
# The Process:
## Research
Night vision is expensive, very expensive. True military grade night vision, such as the Gen 3 standard, does not get cheaper with time or with the age of the unit. While the housings are strong, the actual light amplifier tubes can easily be damaged from intense lights or impact damage. To build my own light intensifier tube would have been impossible unfortunately, luckily I found a better solution.
FPV Drones used for acrobatic flight often find themselves in differing light conditions and crashes, as such, the cameras developed for these cameras are incredibly small, rugged, and most importantly, sensitive to the infrared spectrum. Some select manufacturers create these small infrared cameras which generate an analog signal that could be used to be sent over radio waves to a headset, but in my case, could go straight into an LCD screen.

## Design


At first I was going to create the housing for my goggles using onshape, but after many attempts that were too bulky or ugly looking, I searched to see if anyone else had made something similar. To my surprise, somebody had a similar idea and shared their 3D models on github. With some tweaks so that it would 3D print nicely, I was able to print parts for the housings using special ASA filament. ASA is tougher than the common PLA used in prints, and it is also waterproof.
IMAG 4798. jpeg

I bought two runcam FPV infrared cameras, along with two adafruit LCD displays. Because of the nature of the analog signal produced by the cameras, no other interface was needed. Instead, a direct link could be made from the camera to the screen which was accomplished simply with soldering.
IMG 4695 JPEG
IMG 4700 JPEG
IMG 4743 JPEG
Circuit.png

Next, I put nuts inside of the housing, using the heat from a soldering iron to melt them into place. This would allow the housings to easily be mounted to a common bar for a helmet mount in the future.
IMG 4807 JPEG

In order to allow the cameras to snugly fit in the housing, as well as to absorb shock, and to allow for adjustment based on the user eye distance, I printed the camera mount out of a plexable TPU filament.
IMG 4808 JPG

Now all that I had to do was to assemble the housing parts, with the electronics. This was surprisingly difficult due to how little space I had to fit all the wires, but I was able to fix this by trimming wires (cutting and re-soldering).
IMG 4880 JPEG
IMG 4881 JPEG

One final addition was to add a biconvex lens in front of the LCD screen. With it, the apparent size of the resultant image always stays the same as you move the goggles away. This keeps the illusion of depth and is the same technique used on VR goggles.

With the housings fully assembled, I could connect the power wire from both of them into the common arm. Afterwards, I mounted both via the nut from earlier.
IMG 4928 JPEG
IMG 4929 JPEG
IMG 4930 JPEG

Now mounted to a helmet, attached to a battery pack, and completed, I could try it on and test them. It worked remarkably well, and I was even able to observe hidden everyday phenomena like the grid of dots that are emitted by the Lidar unit on the iPhone for faceID.
IMG 5243.JPEG
 


