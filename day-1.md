# Daily Learning
## Morning Planning
<img alt="Cloudy morning" src="https://octodex.github.com/images/cloud.jpg" width="100" align="right">
## Review
# Hello World
## This is an `<h1>` header, which is the largest
### This is an `<h2>` header
#### This is an `<h6>` header, which is the smallest


Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
