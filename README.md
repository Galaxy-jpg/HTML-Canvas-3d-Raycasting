# HTML Canvas 3d Ray Casting

### **Table Of Content**
- [Description](#Description)
- [Explanation](#Explanation)
    - [Understanding Ray casting](#Understanding-Ray-casting)
    - [How to do Ray Casting](#How-to-do-Ray-Casting)
- [How to Help](#How-To-Help)

## **Description**

HTML Canvas 3d Raycasting explains itself in the title. Its a HTML file that is able to render out 3d objects by using a raycasting method. It is completely in one file, but can be broken apart for personal use.

## **Explanation**

The main goal is to transform a 3d point to a 2d point with a focal lenth.

### **Understanding Ray Casting**

> Ray casting is the methodological basis for 3D CAD/CAM solid modeling and image rendering. It is essentially the same as ray tracing for computer graphics where virtual light rays are "cast" or "traced" on their path from the focal point of a camera through each pixel in the camera sensor to determine what is visible along the ray in the 3D scene. - [Wikipedia](https://en.wikipedia.org/wiki/Ray_casting)

To put it simply, ray casting is the act of grabbing points in a 3d space and drawing a line to the camera from that point. Where ever the line intersects the plane/screen, is where we draw the point on a 2d plane/screen. This is a very simple way of showing 3d grpahics.

### **How to do Ray Casting**

We start with our with our first point, in this example we will use ``(100,100,100)``. Our camera will be at ``(0,250,0)`` which we get from our focal length being 250. 

We can use the formulas

`` X Projected = Focal length * x / z + Focal Length``

`` Y Projected = Focal Length * y / z + Focal Length``

After we fill in our variable with the information said above, our X Projected and Y Projected will be about 71.43. We can repeat this entire process for each point to get our shapes vertexs.

We can do edges by just drawing the lines from each point like before, edges/lines don't get effected by ray casting.

## **How To Help**

As much as I think this project is done, here is a few things you can do to help this project out!

- Optimizating code
- Rotation of Object
    - Using mouse
- Lighting
- Texturing

I will be working on all of these on my own time, but have no set date for when any of these will be implement.
