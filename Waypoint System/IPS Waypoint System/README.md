# This version is specifically for IPS.

It includes a panel specifically for IPS `WPDeltas` and requires exporting some different variables.

Otherwise it is the same installation as the original located [here!](../Waypoint%20System/README.md)

## WPDeltas Panel
There are two version of the WPDelta panel available. Feel free to pick whichever one you want. You only need ONE.
- WPDelta_advanced.yolol will display your Deltas as a Number.
- WPDeltasText_advanced.yolol will display your Deltas as either OPENING/CLOSING.
- Both will display your Distance to the WP and your Speed.


## Differences
There are a few key differences noted below:

- You NEED to have the WPDeltas panel set up for WPDeltas to function correctly.
- You must include `X`, `Y`, `Z` and `S` in additional memory chips somewhere. There is 1 space left over on the Waypoint System memory chips, feel free to use that for one of these required global variables.


## Precompiled IPS
I have included precompiled version of IPS that exports X,Y,Z for you and the Velocity Addon. These are created by Fryke. His repo can be found [here!](https://github.com/Tmktahu/IPS)
