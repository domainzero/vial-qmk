# The Key V2

![The Key V2](https://massdrop-s3.imgix.net/product-images/stack-overflow-the-key-v2-macropad/FP/U2LJ18sQ1uQuHzg2Quk5_PC-copy.png)


The Stack Overflow "The Key V2" is a 3 button macropad based on atmega32u4 with Kailh Black Box switches.

> Last year, we brought Stack Overflow’s iconic April Fool’s joke to life. Advertised as the new (and only) way to copy and paste on the site, it was an ultra-compact macropad called The Key. The punchline-turned product was a huge hit, selling over 10K units and earning a nearly 5-star average review. Now, we’re back with a second act: The Key V2. The same size as its portable predecessor, this punchline-turned-product has a few notable changes—including an acrylic case to accent its two built-in RGB LEDs. Plus, we made it hot-swappable, so you can easily change out the switches for a truly custom experience. And just like the original, a portion of all proceeds from The Key V2 will go to the data-driven social startup digitalundivided. 

Keyboard Maintainer: [Drop / Massdrop](https://github.com/Massdrop/qmk_firmware)

Hardware Supported: Massdrop, Inc. **The Key V2**

Hardware Availability: Limited Release - https://drop.com/buy/stack-overflow-the-key-v2-macropad


Make example for this keyboard (after setting up your build environment):
```bash
make massdrop/thekey_v2:vial
```

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).
Make example for this keyboard (after setting up your build environment):

## Bootloader

Enter the bootloader as follows:
* **Bootmagic reset**: Hold down the "Stack Overflow" key, the "left-most" or furthest from the USB plug while inserting the USB cable for a few seconds. The LEDs will **NOT** turn on.
* **Physical reset button**: Briefly press and hold the reset button while pluggin in the USB port. The LEDs on the back will **NOT** turn on. Depending on your case revision, you may have to remove the 4 screws on the back plate to access the switch OR you can use the associated access hole on newer releases.
