---
 name: Outlines Package
 tools: [AssetStore,C#, Unity,HLSL]
 image: https://i.ibb.co/8PWS8LZ/thumbail.png
 description: Two custom ways to draw outlines listed for sale on the asset store.
---

{% include elements/button.html link="https://assetstore.unity.com/packages/slug/211485" text="Outlines Package on the asset store" block=true %}
## Outlines Package

The package include two custom outlines shader that can be used for variety of different meshes and scenes without writing any code or shader.

**Per object outlines** shader can be used to draw outlines based on:
- mesh normals
- mesh vertex positions
- baked uvs
- baked normal maps

The package include custom little script that bakes into a choosen Uv channel smooth normals, so you can draw outlines using smooth normals and still have flat shaded mesh in your scene.

There is also a feature that lets you change the outlines thickness based on the camera distance from the mesh.

**Screen space outlines** uses custom renderer feature that calculates the edges of the objects based on the depth of the scene and meshes normals.

### Screens

![alt text](https://i.ibb.co/7KJVnn5/image-003-0000.jpg "Image1")
![alt text](https://i.ibb.co/j39SVNn/image-002-0000.jpg "Image2")
![alt text](https://i.ibb.co/6rmNvRJ/image-004-0000.jpg "Image3")
![alt text](https://i.ibb.co/djSNwhL/image-006-0000.jpg "Image4")
