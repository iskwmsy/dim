# dim

dim / 3D Application based on SVG for graphic designers.  
Based on concepts of SVG, bezier curves, B-spline curves, perspective projection, orthographic projection, oblique projection.

https://dim.cog.ooo/dim.html

You can easily import (copy & paste) 2D path images from Adobe Illustrator CC (or other vector graphic software that uses SVG clipboard) to a 3D space and view, transform, extrude, revolve, sweep, map to a spline or a surface, and export (copy & paste) the result back to Adobe Illustrator. 3D matrix operations are applied to vector data. No rasterize.  
Path data are stored as a simple array of 3D coordinates and you can switch the interpolation algorithm between Linear, B-Spline(Cubic), B-Spline(Quadratic), Cubic Bezier. B-Splines will be deconstructed to cubic bezier on SVG rendering and exporting.
It also has a set of vector graphic tools. Pen, Polygon, Star, Ellipse, Doodle, Pixel Art, Spiral, Cycloid, that works inside the 3D space.

Inspired from Adobe dimensions(3.0J),  
"SiNYO Beta" by Hajime Tachibana,  
Takenobu Igarashi,  
"3D Graphics Programming from Scratch" by Gustavo Pezzi (https://pikuma.com),  
"The Continuity of Splines" by Freya Holmér (https://youtu.be/jvPPXbo87ds),  
"B-Spline Decomposition" by designcoding(https://www.designcoding.net/b-spline-deconstruction/)  
Concept of "Workplane" from Modo by Foundry  
"Interface Craft" by Josh Puckett (https://www.interfacecraft.dev).
