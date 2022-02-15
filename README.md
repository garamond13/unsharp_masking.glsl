# Post upscale unsharp masking shader for mpv
This is mpvs original image sharpening algorithm ported into the shader, in order to work only after upscaling is done.

You can change the sharpening strength by changing the `param` value.

If you place this shader in the same folder as your `mpv.conf`, you can use it with `glsl-shaders-append="~~/unsharp_masking.glsl"`.
