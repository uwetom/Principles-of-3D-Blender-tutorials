# Texturing and uv unwrapping

In this worksheet will will expore the shading workspace, adding PBR textures to our model.

We will also have another look at manually UV unwrapping

## 1. Import a model

For this workshop we will use an existing model which we need to import.

- Download the following glb file

[cactus glb file ](assets/cactus.glb)

- Import it into a new Blender file using **File > import > gltf 2.0**

![Import gltf into blender](images/import.jpg)

This video shows you how to do this if you get stuck:

[<img alt="video showing how to import a glb file to Blender" src="images/video-import.jpg">](https://uwe.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=3bbbf082-bd84-4e70-b5ad-b49800fa60e0)

## 2. Apply image using Shader editor

We can now add an image texture to the cactus.

- Download the following image and move it next to your blender file.

[giraffe texture](assets/giraffe.jpg)

- Select the **shading** workspace

![shading workspace tab](images/shading_workspace.jpg)

- Create a new materials and rename it

![create a new material button](images/new_material.jpg)

- Create a new image texture node by selection **Add > Texture > Image Texture**

![add image texture](images/image_texture.jpg)

- Connect the color output of the**image texture** node to the  Base colour input of the **Principle BSDF** node 

![connect colour to base colour](images/connection.jpg)

- Press **open** on the image texture node, and select the giraffe image you downloaded earlier.

![open giraffe texture](images/Open.jpg)

You should now see the giraffe texture on your cactus

![Giraffe texture on cactus](images/giraffe_texture_applied.jpg)

If you get stuck, this video show you how to add the image texture.

[<img alt="video showing how to apply an image texture with the shader editor" src="images/video_image_texture.jpg">](https://uwe.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=9d4ab278-a796-48a7-8792-b49800fdda85)

## 3. Smart UV unwrapping










If you get stuck, this video show you how to use smart unwrap

[<img alt="video showing how to smart unwrap your uvs" src="images/video-unwrap.jpg">](https://uwe.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=8374253d-ee88-4488-9fb7-b498010ec217)

## 4. Node Wrangler and PBR textures









- [https://ambientcg.com/](https://ambientcg.com/)


If you get stuck, this video show you how to use the node wrangler

[<img alt="video showing how to use the node wrangler to apply PBS materials" src="images/video_node_wrangler.jpg">](https://uwe.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=83d906ee-555a-42ef-8ebd-b49801127522)


## 5. Challenge - Finish the Cactus

See if you can add textures to the soil and pot.

- Download pbr textures or just a base colour image
- Apply it to the pot and soil objects

## 6. Extra - Manual UV Unwrapping

Using smart unwrap normally gives you very good results, but if you want to go further and have more control over how your model unwraps this section will show you how to manually unwrap your model.

This video show you how to use manually unwrap your object

[<img alt="video showing how to manually unwrap your object" src="images/video_manual_unwrap.jpg">](https://uwe.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=a3eacb06-32dd-4273-bbd0-b49801150dad)

## 7. Resources

### free textures
You can download creative commons licenced prb textures from these sites without needing to login or create an account.
- [https://ambientcg.com/](https://ambientcg.com/)
- [https://polyhaven.com/](https://polyhaven.com/)

### Decals
You may want to apply decals to your models, they are useful for applying logos, or specific images as a layer over your main texture
- https://www.youtube.com/watch?v=TIkY5SFAusU


### Substance Painter
Substance painter is a powerful and fully featured tool for texturing models, I have made a serice of video showing the basic functionality
- [substance painter playlist](https://uwe.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?pid=3e0ac1c4-1ad4-4946-8318-b20d00e07035)

