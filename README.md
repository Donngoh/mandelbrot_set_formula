One of the amazing discoveries in the realm of mathematics that not only does the simple equation Zn+1 = Zn2 + C create the infinitely complex Mandelbrot Set, but we can also find the same iconic shape in the patterns created by many other equations. 
In fact, the phenomenon of Mandelbrot universality meant that anytime we iterate a function that in some portion, at some scale, resembles the parabolic function Z2, then we will find small copies of the Mandelbrot Set in the map of that function.

To understand in a graphical way, 
Imagine Coordinate system [X,Y]
For each point calculate a new coordinate based on some simple formula. Repeat this infinite times. 
Each starting point where the series of number converges (moves closer to a specific point) gets painted black, each point that diverges (gets further and further away) gets painted in a colour that depends on how fast it diverges.
Now the weird part is that the starting point has an infinitely high "sensitivity", no matter how little you change it, the outcome can change dramatically. (The butterfly effect basically, wich also is true for weather on earth).
Even weirder is that if you zoom in you'll find that the mandelbrot set is made from an infinite number of deformed versions of itself, but none of them are exactly the same, the deformation is different every single time.

To very roughly illustrate that repeated aspect, consider just a 1D system (aka a line) and a function x => x².
If you start with X=1, the first iteration results in 1, the next in 1 again, and so in forever: the number never runs away, so that point is black.
If you start with 0.9, the next value is 0.081, and then 0.006561, and each iteration is a bit smaller — so that also doesn't run away, and you paint that black. On the other hand, if you start with 1.1, the next value is 1.21, and then 1.4641, and then ~2.14 — the numbers keep getting bigger and bigger, and so you paint that white.
If you work it out, you'll see that all values between -1 and 1 (including those endpoints) are black, and all the other points are white. Not super interesting, but what's very slightly more interesting is that you can zoom in on this border as much as you want. 0.9998 is black, but just 0.0002 away is the border; zoom in a bit more and 0.9999999998 is black, but just 0.0000000002 is the border. 
Even though the border isn't particularly interesting, it's cool that you can zoom in arbitrarily close to it. It's just too bad that it happens to always look the same no matter how much zooming in you do lol!

The Mandelbroit set is basically that, but in a 2D space and with an infinitely intricate border.
