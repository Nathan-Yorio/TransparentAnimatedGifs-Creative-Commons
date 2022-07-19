# Want to have something like this on your github readme page?

<p align="center">
<img src="https://github.com/Nathan-Yorio/TransparentAnimatedGifs-Creative-Commons/blob/54480c1ce2c72e2628c1b1c96ef86b4d92e6ff5a/resources/pentakisdodecahedron.gif" width="100" height="100" />
</p>

# Incapable of creating your own animations?
# Great! Steal them from creative commons!

# Step 1. Go find a gif.

- the easiest way to get yourself a nice animated gif is to know how to search for them
- Google images happens to provide all the tools you need. Observe:
![](https://github.com/Nathan-Yorio/TransparentAnimatedGifs-Creative-Commons/blob/54480c1ce2c72e2628c1b1c96ef86b4d92e6ff5a/resources/mandelbrot_result.png)

- download that gif!

# Step 2. Figure out what the background color of the gif is
- there are a million tools you can use to figure ou what the hexadecimal value of your gif's background is
- I personally just dumped it into ppt and eyedropped off of it, but I'm sure there's a malicious chrome extension or something you can download to do that too
![](https://github.com/Nathan-Yorio/TransparentAnimatedGifs-Creative-Commons/blob/54480c1ce2c72e2628c1b1c96ef86b4d92e6ff5a/resources/eyedropper1.png)


- Well, there we have it, it sure is actually red. We care about the hex value of: `#FD0000`
![](https://github.com/Nathan-Yorio/TransparentAnimatedGifs-Creative-Commons/blob/54480c1ce2c72e2628c1b1c96ef86b4d92e6ff5a/resources/eyedropper2.png)

# Step 3. Remove the background from the gif

- head on over to something like [EZGif.Com](https://ezgif.com/effects)

- dump the gif in and upload it
![](https://github.com/Nathan-Yorio/TransparentAnimatedGifs-Creative-Commons/blob/54480c1ce2c72e2628c1b1c96ef86b4d92e6ff5a/resources/upload.png)

- scroll down to replace color with transparency:
- dump in the RED hex value we just found, this works best if it is a solid color and the gif isn't too crunchy to extract one color
![](https://github.com/Nathan-Yorio/TransparentAnimatedGifs-Creative-Commons/blob/54480c1ce2c72e2628c1b1c96ef86b4d92e6ff5a/resources/replace-background.png)

- can slap some filters on it if you want then hit apply
![](https://github.com/Nathan-Yorio/TransparentAnimatedGifs-Creative-Commons/blob/54480c1ce2c72e2628c1b1c96ef86b4d92e6ff5a/resources/filters-and-such.png)

- you should now get a mostly transparent gif to use for whatever you want because it is publicly licensed
![](https://github.com/Nathan-Yorio/TransparentAnimatedGifs-Creative-Commons/blob/54480c1ce2c72e2628c1b1c96ef86b4d92e6ff5a/resources/processed_image.png)

- take that gif and dump it in github somewhere and then imbed it into the page with some custom styling by adding in the permalink like so:
```CSS
<p align="center">
<img src="https://github.com/Nathan-Yorio/TransparentAnimatedGifs-Creative-Commons/blob/54480c1ce2c72e2628c1b1c96ef86b4d92e6ff5a/resources/mandelbrot.gif" width="100" height="100" />
</p>
```

- and there it is!
<p align="center">
<img src="https://github.com/Nathan-Yorio/TransparentAnimatedGifs-Creative-Commons/blob/54480c1ce2c72e2628c1b1c96ef86b4d92e6ff5a/resources/mandelbrot.gif" width="100" height="100" />
</p>
