### Bodymovin

+ đ 60 FPS rendering, looks super nice
+ đ Can manipulate animation, replay on demand, adjust pauses between loops, etc
+ đ Resolution independent vector rendering
+ animation data file is `24KB | 3KB gzipped`

- âšī¸ bodymovin.js must be loaded once on any page with a bodymovin animation 
  `191KB | 44KB gzipped`

- âšī¸ Must initiate animation with javascript

  â


### Animated gif

+ đ Super easy to drop into page
+ đ Can easily add to emails, etc
+ gif file is `16KB`
+ rendered out at 2x so it doesn't look terrible on retina displays, then resized to original dimensions
+ âšī¸ no control of playback, just loops indefinitely

- âšī¸ lowest quality of animation / color / rendering of 3 options
- âšī¸ no transparent background, will need to re-render for every background option




### Video file (mp4)

+ đ both smaller and higher quality than gif file
+ mp4 file is `11KB` 
+ rendered out at 2x so it doesn't look terrible on retina displays, then resized to original dimensions

- playback control possible in javascript, but by default just loops indefinitely
- requires video tag:
   ```<video loop muted autoplay playsinline><source src="..." type="video/mp4"></video>```
- âšī¸ no transparent background, will need to render for every background option

