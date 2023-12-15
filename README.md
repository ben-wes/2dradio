# 2dradio
2d radio button abstraction for Pd vanilla

_(based on dynamic patching of a row of vradios and their value and visibility management through clone)_

## Usage:
* create 2d radio area with `[2dradio <columns> <rows>]`
  * (max of 32 x 32 suggested since dynamic clone resizing does weird things otherwise)
* `[bang(` outputs current position
* `[set <x> <y>(` sets position without output
