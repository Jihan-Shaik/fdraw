# f(draw)

Draw any curve and get its equation y = f(x), ready to paste into Desmos.

**Live:** https://jihan-shaik.github.io/fdraw/

## Features
- Fits each stroke with the simplest polynomial that hugs it, or a piecewise function with Desmos-style domains when that fits better
- Copy button: equations paste straight into Desmos and reproduce the same graph
- Intersections between all visible curves and the axes, with coordinates on hover
- Per-curve derivative (f′) and inverse (x = f(y)), with a one-one check
- Zoom, pan, extend curves across the whole view, light and dark themes

## How it was built
I came up with the idea, specified the features, and tested and iterated on it. The code was written with Claude, Anthropic's AI assistant.

One self-contained HTML file with no dependencies.
