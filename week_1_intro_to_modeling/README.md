
# Worksheet 1

## Introduction

These worksheets will walk you through the basics to get you started modeling in Blender.

They are  combination of text and videos, if you get stuck please ask for help. We all love making 3D content and are happy to share our knowledge.

You can also ask your neighbour for help, they may have faced the same issue as you.

Learning new software takes practice so please do the challenges in these worksheets to improve your skills.

## Install Blender

### On Your machine
You can download and install Blender for free for Mac, PC and Linux from here:

[https://www.blender.org/download/](https://www.blender.org/download/)

We will be using version 5.1, but as long as its version 5 you will be able to follow along with these worksheets.

### On Campus (2q24, 2q25)

You can find Blender on UWE's software launcher "Apps Anywere"

* Open [https://appsanywhere.uwe.ac.uk](https://appsanywhere.uwe.ac.uk)

* Search for **Blender** and press launch

![Launch blender in Apps anywhere](images/blender_apps.jpg)

![](images/blender_start.jpg)

## Mouse

We strongly recommend you get a mouse for 3D work.

You can buy one from the project room (2q20)

You can use a laptop trackpad but you will find it slower and more frustrating.

## 1. Interface

Most 3D software shares common elements called **Areas** in Blender, they can be in different locations and can be rearranged by the user

![](images/panels_annotated.jpg)

- **3D viewport** - Your 3D scene
- **Outliner** -  A list of all the object in your scene (Meshes, lights, cameras etc..)
- **Properties** - view and modify information about the selected object and the whole scene

### Saving

Remember to save you work often, it can be very frustrating to loose work in a crash.

- Save this new project by going to **file > save as**


This video walks you through the interface in more details:
[<img alt="video showing teh basic blender interface" src="images/video_1_interface.jpg">](https://uwe.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=80a2040a-d8e3-45c3-a3e8-b474009ba73d)

## 2. Navigation

In the 3D viewport you can move your editor camera:

* **Rotate** - Hold middle mouse button
* **Pan** - Shift + Hold middle mouse button
* **zoom** - mouse wheel


This video shows you how to use the above commands, and also how to emulate these if you don't have a mouse:

[<img alt="video showing how to move the camera in Blender" src="images/video_2_navigation.jpg">](https://uwe.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=eeedacf2-7294-4f4f-9f07-b47400a1cde4)

## 3. Move scale rotate

When you have an object selected in the viewport you can move, rotate and scale it. The hot keys are:

* **g** - move
* **r** - rotate
* **s** - scale

or you can use the button at the left of the screen

![move scale and rotate button in Blender](images/move_scale_rotate.jpg)

This video shows you how to use these tools:

[<img alt="video showing how to move, scale and rotate objects in Blender" src="images/video_3_move.jpg">](https://uwe.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=445a3070-a1d8-415c-9d01-b47400aa60ca)

## 4. Create and arrange primitives

Cubes, Cylinders and Spheres are all primitive shapes, you can create them from the top menu:

Add > Mesh

![primative mesh menu in Blender](images/add-mesh.jpg)

As soon as you have made a new shape an option box appears at the bottom right of the screen, this gives you the opportunity to change the properties of the object.

![Blender primative options](images/primative_options.jpg)

[<img alt="video showing how to create and manipulate primatives in Blender" src="images/video_4_primatives.jpg">](https://uwe.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=158b53eb-c292-485d-a469-b47400b092a6)

Make sure you have saved your project.

## 5. Challenge - Make a Rocket 

Just using primitive meshes, make a simple rocket

![Rocket model in Blender](images/rocket.jpg)

Try to do this yourself before looking at my solution video bellow:

[<img alt="video showing how to make a rocket in Blender" src="images/video_5_solution_1.jpg">](https://uwe.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=322889eb-eb28-4fdc-8c5c-b47400b315fe)


## 6. Collections and naming

As you add objects to your scene it is important to keep things organised, you can do this by renaming the meshes, and creating collections.


You can rename objects in the outliner by double clicking on them

![renaming object in outliner](images/rename.jpg)

You can create new collections to group your objects

![create new collection in Blender](images/new_collection.jpg)

Click and drag objects to add them to move them between collections.


For a video walkthough of this, watch this video:

[<img alt="video showing how to create collections in Blender" src="images/video_6_collections.jpg">](https://uwe.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=3ce44ef4-0611-43a7-b61c-b47400b73462)

## 7. Vertexes, faces and edges

Primitive meshes are made up of vertexes, edges and faces.

In Blender, you can switch between **Object** mode and **edit** mode using the **tab** key

In edit mode you can select and move the vertexes, faces and edges by selecting them in the top menu:

![vertex, edge and face buttons in blender](images/vertex_edge_face.jpg)

You can also select these using the number row on you keyboard

* **1** - Vertex
* **2** - Edge
* **3** - Face

With these selected you can move, scale and rotate them the same way as whole objects.

Double click edges or faces to select whole loops.

This video show this in more detail:
[<img alt="video showing how to manipulate vertexes, edges and facesin Blender" src="images/video_7_vertexes.jpg">](https://uwe.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=a81b9d35-2ad5-48ac-ac98-b47400bb54b8)

## 8. Triangle count and deleting

For the assignment you will need to stick to a triangle count. Each four sided face on your object (a quad) is made up of two triangles.

To find out how many triangles in your whole model turn on **Statistics** in the **Overlays** menu.

![statistics panel in Blender](images/statistics.jpg)

When deleting edges, select them, press the **delete** key on your keyboard and choose **dissolve edges**

[<img alt="video showing how to show the stats panel in Blender" src="images/video_8_poly_count.jpg">](https://uwe.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=0e590226-9aaa-4f09-bb8b-b47400c1b3fa)

> [!WARNING]
> Don't add new mesh primitives when in edit mode unless you are sure you want to.

## 7. Materials

We can add material to whole objects, or individual faces using by adding new materials in the **material property** area.

![add new material in Blender](images/material_properties.jpg)

You can then change the properties of the material, including the colour

![change the colour in of the material](images/colour_properties.jpg)

In this video I will show you how to add simple colours to your objects and different faces of your object:

[<img alt="video showing how to add different materials to your object in Blender" src="images/video_9_materials.jpg">](https://uwe.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=067bebdc-2b0d-4f6f-9fc1-b47400c81f12)

> [!TIP]
> Make sure you are in the correct shading mode.
> ![shading mode in Blender](images/render_mode.jpg)

In future worksheets we will delve deeper into adding images and texture painting.

## 8. Challenge - make a space station.

Using the skills you have learnt in this worksheet to make a low poly space station. It can be real or fictional.

Think about which primitive most closely resembles your object.

Add colours to your space station.

![Photo of the death star](images/Death_star1.png)

Save regularly!

We will cover more advance modeling tools in future weeks, but here are some tips if you want to add more detail to your primitive shapes

> [!TIP]
> Select the end face of a cylinder and select **poke face** from the face menu
> ![poke face in Blender](images/poke_faces.jpg)


> [!TIP]
> Make sure you are in the correct shading mode.
> ![add loop cut in blender](images/loop_cut.jpg)

## Extra resources

[Blender 5.1 Manual](https://docs.blender.org/manual/en/latest/index.html)

[Blender Cheat Sheet](https://raw.githubusercontent.com/nachazo/blender-cheat-sheet/main/blender-cheat-sheet.png)

[YouTube short course](https://www.youtube.com/watch?v=kVcY7K-JA1Y&list=PLn3ukorJv4vv9_e-htADGsPX9TMaQpHV8)

