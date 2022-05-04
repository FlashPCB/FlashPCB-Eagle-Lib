# FlashPCB Library for Autodesk Eagle

[FlashPCB](https://www.flashpcb.com/) is a fast, affordable, and hassle-free AI powered PCB assembly service. We
developed this library to provide you with a high-quality, comprehensive selection of footprints and symbols that you
can use in your designs.

## Overview

This library of components is designed for use with
the [Autodesk Eagle CAD](https://www.autodesk.com/products/eagle/overview)
software. It contains components across a broad spectrum of categories:

- Capacitors
- CircuitProtection
- Connectors
- DevBoards
- Diodes
- Hardware
- ICs
- Inductors
- Misc
- Oscillators
- Resistors
- Sensors
- Switches
- Transistors

## Reasons to use the FlashPCB Library

Our PCB manufacturing process is optimized to work from these footprints and using these footprints is the only way for
us to manufacture your board with the parts you want.

That being said you are free to use this library in any design, even if you do not intend to use our service.

## How to use this library

### Download the library

Clone this repo using your favorite git client or download the zip file containing the library.

### Update Eagle's Library directories to recognize this library

[This tutorial](https://www.autodesk.com/products/eagle/blog/library-basics-install-use-sparkfun-adafruit-libraries-autodesk-eagle/#:~:text=Step%202%20%E2%80%93%20Update%20Your%20EAGLE%20Library%20Directory)
explains how to update Eagle's settings so that you can use this library. The tutorial explains how to use Sparkfun and
Adafruit libraries but the process is very similar for our library. Start at the section "Step 2 – Update Your EAGLE
Library Directory".

### Use these components in your Eagle PCB design

Specify your parameters in the value text for the components that you use. You can write something like `22k 1%` if
you're placing a resistor or by specifying a manufacturer's part number.

### Order your assembled board from FlashPCB

[Upload your finished board to our website](https://www.flashpcb.com/upload-board) to get started on the ordering
process. Our AI powered BOM generator can understand the value text `22k 1%` to find the best components that we have in
stock to match the footprint and the properties you specified. If you've specified a manufacturer's part number in the
value text our AI will find that component if we have it in stock or suggest a different component that matches the
specifications of the component specified.

Read [our docs](https://www.flashpcb.com/docs) for more information about the ordering process.

## Requesting additions to the library

Feel free to [create an issue](https://github.com/FlashPCB/FlashPCB-Eagle-Lib/issues/new) in GitHub if you would like to
request specific components added to our library. Additionally you can reach out to us
via [our site's contact page](https://www.flashpcb.com/contact).
