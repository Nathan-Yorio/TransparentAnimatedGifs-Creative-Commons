# Want to have something like this on your github readme page?


# Incapable of creating your own animations?
# Great! Steal them from creative commons!

# Step 1. Go find a gif.

- the easiest way to get yourself a nice animated gif is to know how to search for them
- Google images happens to provide all the tools you need. Observe:

- download that gif!


# Step 2. Figure out what the background color of the gif is
- there are a million tools you can use to figure ou what the hexadecimal value of your gif's background is
- I personally just dumped it into ppt and eyedropped off of it, but I'm sure there's a malicious chrome extension or something you can download to do that too

- Well, there we have it, it sure is actually red. We care about the hex value of: `#FD0000`


# Step 3. Remove the background from the gif

- head on over to something like [EZGif.Com](https://ezgif.com/effects)

- dump the gif in and upload it


- scroll down to replace color with transparency:
- dump in the RED hex value we just found, this works best if it is a solid color and the gif isn't too crunchy to extract one color


- can slap some filters on it if you want then hit apply

- you should now get a mostly transparent gif to use for whatever you want because it is publicly licensed

- take that gif and dump it in github somewhere and then imbed it into the page with some custom styling like so

```CSS
<p align="center">
<img src="" width="100" height="100" />
</p>
```

- and there it is!
<p align="center">
<img src="" width="100" height="100" />
</p>