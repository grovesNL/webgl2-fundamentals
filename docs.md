webgl2fundamentals API Docs
==========================

These docs are an attempt to help explain some of the helper function
used in the articles on [webgl2fundamentals.org](http://webgl2fundamentals.org).

WebGL is a very low-level API and so using it is very verbose. To draw a simple
lighted cube can easily require 50-100 WebGL calls. Calls to create buffers
and put data in them. Calls to create that data in the first place. Calls to
create GLSL shader programs. Calls read attribute and uniform locations. Calls
to create textures, bind textures to texture units, bind buffers to attributes,
and set uniforms.

At some point this complexity makes it hard to concentrate on the topic at hand
and so helper functions can [reduce the number of lines need to
a smaller few](/webgl/lessons/webgl-less-code-more-fun.html).

[Functions for reducting the amount of code can be found here](/docs/module-webgl-utils.html).

If you're using WebGL to do 2D or 3D you'll likely need many math helper functions
in JavaScript as well.

[Functions for 2D math are here](/docs/module-webgl-2d-math.html).

[Functions for 3D math are here](/docs/module-webgl-3d-math.html).

Finally WebGL requires vertices to operate on. [Functions to generate veritces
for common shapes like spheres, cubes, planes, cones, etc can be found here](/docs/module-primitives.html).

#JSDoc3 Plea

These docs are generated with [JSDoc3](http://usejsdoc.org/). I find them very confusing to look at
and in some places frustratingly verbose. If you have any experience with JSDoc3 and know how to
make the docs more approachable and useful please [submit a pull request](https://github.com/greggman/webgl2-fundamentals)
or [file an issue with details](https://github.com/greggman/webgl2-fundamentals/issues).

