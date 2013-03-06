The code is from demo at http://people.mozilla.org/~bjacob/mdn_samples_webgl_sample8/index.html with some changes.
1. webgl-demo.js
   In updateTexture(), change gl.TEXTURE_MIN_FILTER from gl.LINEAR_MIPMAP_NEAREST to gl.LINEAR and remove gl.generateMipmap(gl.TEXTURE_2D) to make it work with chromium.
2. index.html
   Change the video source from Firefox.ogv to 720p_H.264_AAC.mp4(a 720P H264 Video).
   Change the canvas size from 640*480 to 1280*720.


Since the Video file is a little big, you can copy a similar video to the same directory as index.html and rename it to 720p_H.264_AAC.mp4.


