# Post scale unsharp masking shader for mpv
This is mpvs original image sharpening algorithm ported into the shader.
In order to work after scaling is done, although it still sharpens the image
even if you don't scale the video. The workaround for this is to use the shader
conditionally with profiles.

You can change the sharpening strength by changing the `param` value.

If you place this shader in the same folder as your `mpv.conf`,
you can use it with `glsl-shaders-append="~~/unsharp_masking.glsl"`.