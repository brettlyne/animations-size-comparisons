### Bodymovin

+ 😃 60 FPS rendering, looks super nice
+ 😃 Can manipulate animation, replay on demand, adjust pauses between loops, etc
+ 😃 Resolution independent vector rendering
+ animation data file is `24KB | 3KB gzipped`

- ☹️ bodymovin.js must be loaded once on any page with a bodymovin animation 
  `191KB | 44KB gzipped`

- ☹️ Must initiate animation with javascript

  ​


### Animated gif

+ 😃 Super easy to drop into page
+ 😃 Can easily add to emails, etc
+ gif file is `16KB`
+ rendered out at 2x so it doesn't look terrible on retina displays, then resized to original dimensions
+ ☹️ no control of playback, just loops indefinitely

- ☹️ lowest quality of animation / color / rendering of 3 options
- ☹️ no transparent background, will need to re-render for every background option




### Video file (mp4)

+ 😃 both smaller and higher quality than gif file
+ mp4 file is `11KB` 
+ rendered out at 2x so it doesn't look terrible on retina displays, then resized to original dimensions

- playback control possible in javascript, but by default just loops indefinitely
- requires video tag:
   ```<video loop muted autoplay playsinline><source src="..." type="video/mp4"></video>```
- ☹️ no transparent background, will need to render for every background option

