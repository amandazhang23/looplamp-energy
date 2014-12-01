# LoopLamp

## About
The light up the loop lamp is a collaborative project between many organizations. This repository contains the information needed to setup up the Software for your own lamp. For more info, contact [Hunter Owens](mailto://hunter@hunterowens.net).


## History
At one point, this repository was a Node based webapp that relied on a node package with bindings to the Raspberry Pi GPIO board. These bindings no longer work with the new version of the [lights](http://www.adafruit.com/product/306), so we have start using bit addressing and python (see `paint.py`). 

## Setting up the lights
You may want to consult the [Adafruit Guide](https://learn.adafruit.com/digital-led-strip).

### Wiring
![wires](https://learn.adafruit.com/system/assets/assets/000/001/589/medium800/raspberry_pi_diagram.png?1396774138)

### Programming
The lights are bit-addressable. See `paint.py` for the conversion chart. You will need the [RPi](https://pypi.python.org/pypi/RPi.GPIO) library installed. 
