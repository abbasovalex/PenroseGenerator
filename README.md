# PenroseGenerator

This script generates SVG files containing Kite and Dart Penrose Tilings.

https://en.wikipedia.org/wiki/Penrose_tiling

## To run

`python penrose.py [shape] [number generations] [file name]`

This will generate Penrose tilings of type P2. They have two main initial shapes - [star and sun](https://en.wikipedia.org/wiki/Penrose_tiling#Deflation_for_P2_and_P3_tilings). 

The script will generate `[number of generations]` files. Each will be a successive generation of the tiling.

### Sun Configuration

Here are screenshots of the SVG files generated by: `python penrose.py sun 6 sun_tiling.svg`

Initial configuration:

![initial config](img/sun0.png)

Generation 1: 

![gen1](img/sun1.png)

Generation 2:

![initial config](img/sun2.png)

Generation 3:

![initial config](img/sun3.png)

Generation 4:

![initial config](img/sun4.png)

Generation 5: 

![initial config](img/sun5.png)

### Star configuration

Here is a screenshot of the last SVG file generated by: `python penrose.py star 6 star_tiling.svg`

![star tile](img/star5.png)
