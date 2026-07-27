# Output from Blender to Unity

There are a few steps you need to do to make sure your object comes through to Unity as expected

## Prepare your object for export


### 1. Centring and Grounding

Your object should be in the center of the scene, If not, it may be hard to find and manipulate in Unity.

The base should also be on the ground

- Move your object so that its centered and on the ground.

![robot centered in Blender](images/center.jpg)

![robot on ground in Blender](images/ground.jpg)

### Size

Although you can scale up objects in Unity, it is best practice to make them the correct size in Blender first to avoid creating extra work and confusion

This is particularly important if you object needs to be a specific size

With your object selected, open the **items menu** (shortcut n) and look at the **dimensions**

- Scale the object up until it is the correct size

![](images/size.jpg)

### Scale

Now that we have scaled up the object you can see its scale is no longer 1.

We need to reset this to stop it returning to the original scale in Unity 

- Select the object, choose **Object > Apply > All Transforms** (shortcut Alt + A)

![](images/apply.jpg)

You should see the scale now reset to 1.

## Export as fbx

No we have prepared our model we can export it.

You can export to different formats, but fbx is currently the best way to export for Blender.

- Select your model
- Choose **File > Export > FBX

![Export FBX file in Blender](images/export.jpg)

- Change **Path Mode** to **copy**

![path mode copy](images/path_mode.jpg)

- Select **Embed textures**

![embed button](images/embed.jpg)

- Enable **Selected Objects**

![selected object tickbox](images/selected.jpg)

You can now save the file to somewhere convinient, or better still, inside the **Assets** folder in your Unity project.

## Import to Unity

You can now import your object into Unity

- If it is not there already, drag your fbx file into the Assets panel in your project.

I have added mine to its own folder to keep things neat.

![Assets panel in unity](images/assets.jpg)

You can now drag your robot into your Unity scene or the Hierarcy, but it may be missing its textures.

## Fix textures


