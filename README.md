# 2dradio
2d radio button abstraction for Pd vanilla

## Usage:
* create 2d radio area with `[2dradio <x> <y>]`. (max of 32 x 32 suggested since internal clone resize doesn weird things then)
* `[bang(` outputs current position
* `[set <x> <y>(` sets position without output
