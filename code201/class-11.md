# Reading 11

## Audio and video content

### Evolution of A/V

Traditionally, A/V was supported in the browser using installable plug-ins like Flash and Silverlight. These have become obsolete and have since been replaced by HTML's native A/V support.

### The `<src>` and `<controls>` elements

In the `<video>` HTML tag, these attributes provide the origin of the video (on the filesystem, on the web, etc.) and the ability to control playback, respectively.

### Importance of fallback content

Fallback content is necessary because not all browsers support HTML-native video. It can also help when bandwidth is limited and the video cannot be rendered.

### A story about `<audio>` and `<video>`

One day, I was browsing the web. I wanted to watch a video included in a website, but I was using a computer at the library that had disabled this feature for security reasons. I instead had to make use of the metadata attributes in the `<audio>` and `<video>` tags so that I could find out what the sound and video was trying to show me.
