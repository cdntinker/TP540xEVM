# TPS540x Evaluation Board

(This project started as a result of the truly awful EVM design from TI for these chips.)

This little circuit should work with either the TPS5403 or TPS5405 from Texas Instruments.

Both chips will accept up to 28V input.

The TPS5403 wants 4.5-28V & outputs 3v3 up to 1.7A.

The TPS5405 wants 6.5-28V & outputs 5v0 up to 2A.

# The 3 boards

## Standalone
Basically, a standalone voltage regulator board...

## Module
A tiny little voltage regulator module (daughterboard)...

There is also a symbol/footprint/3D model set in ***KiCAD Customs*** for this module.

## Carrier
Like **Standalone**, but using **Module** instead of parts on the board...
