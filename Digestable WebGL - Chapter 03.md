# Digestable WebGL - Chapter 0.3: Laying the Groundwork for Drawing

## How About Some Shapes?

Drawing onto the WebGL canvas is our next step, but first it's important to talk about how WebGL defines things we can actually draw.

In WebGL we have 3 types of things we can draw, *points*, *lines* and *triangles*. These can be described by X, Y, and if working in 3D space, Z coordinates. More accurately we can break this down into:

- **POINTS** (point geometries)
- **LINES** (line geometries)
- **LINE_STRIP** (acontinuous series of lines)
- **LINE LOOP** (a continuous series of lines that ends where it starts)
- **TRIANGLES** (triangle geometries)
- **TRIANGLE_STRIP** (back to back triangles)
- **TRIANGLE_FANS** (triangles that share a singular starting vertex )


As you can see WebGL is a big fan of caps lock. The most common geometry type is arguably the triangle; from any complex model or set of geometries you can subdivide these into triangles. Take this Dolphin for example:

![A wonderful triangulated dolphin](https://upload.wikimedia.org/wikipedia/commons/f/fb/Dolphin_triangle_mesh.png)

## Drawing Things

In order to draw things in WebGL, it is first necessary to begin to grasp some concepts. In this chapter they will just be briefly introduced but they are explained in detail in the following chapters. The first thing to get aquainted with are ***shaders***. The second thing that is useful to understand are ***typed arrays***. We've touched on shaders very briefly at the begining and we'll be slowly introducing them over the next few chapters. Two brief explanations:

- [**Shaders**](http://www.html5rocks.com/en/tutorials/webgl/shaders/) : A program that often runs on the GPU to determine how an graphics should be rendered onto the screen.
- [**Typed Arrays**](http://www.html5rocks.com/en/tutorials/webgl/typed_arrays/) : Typed arrays are a view onto underlying in memory data. They allow for the efficient passing of binary data from JavaScript to WebGL (shaders). Officially part of the ECMAScript 2015 specification ([according to MDN](https://developer.mozilla.org/en/docs/Web/JavaScript/Typed_arrays)).

Using these two powerful technologies we are able to achieve fast rendering speeds and reasonable graphical performance even on the web. However shaders are more complex than dealing with 'fixed functions', but also provide a lot more flexibility. Next chapter we'll draw our first




## Credits and Sources

1. Nvidia - [What’s the Difference Between a CPU and a GPU?]( http://blogs.nvidia.com/blog/2009/12/16/whats-the-difference-between-a-cpu-and-a-gpu/)


## Image Credits

[Dolphin - Public Domain]](https://upload.wikimedia.org/wikipedia/commons/f/fb/Dolphin_triangle_mesh.png
