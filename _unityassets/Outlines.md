---
 name: Outlines Package
 tools: [AssetStore,C#, Unity,HLSL]
 image: https://assetstorev1-prd-cdn.unity3d.com/key-image/381ad586-b584-4143-ba7f-8dae6d617e93.webp
 description: Two custom ways to draw outlines listed for sale on the asset store.
---

{% include elements/button.html link="https://assetstore.unity.com/packages/slug/211485" text="Outlines Package on the asset store" block=true %}
## Outlines Package

Multiple, easy ways to draw outlines and highlights for your game. Perfect if you don't want to spend too much time customizing meshes to make them work with outlines.

**Description**

Package contains three solutions for rendering outlines. You can easily add any of these to your game.
Basic outlines shader - per object shader. Perfect if you need to outline only character or few game objects. You can also use it to outline whole layer of objects. Because of the UV baking tool that comes with the pack. You can create good looking outline even for flat shaded objects.

Edge detecion outlines - fully screen space shader. Perfect for making your whole game, or just selected objects, outlined. You are able to choose which objects have this outline, becouse it works 'per layer'.

Blur outlines - fully screen space shader. Perfect for higlighting objects.You are able to choose which objects have this outline, becouse it works 'per layer'.

**Technical Details**

Package contains three solutions for rendering outlines. All three ways work per layer, which means you can specify which objects should have outlines.

Basic outlines shader is per object shader. It can be added as a second material to your mesh or by using unity's render objects renderer feature.
Basic outlines shader can be used to draw outlines based on:
mesh normals
mesh vertex positions
baked normals from UV channel
baked normal maps
The package includes Tool for baking smooth normals into mesh UV channel, so you could easily use outlines even with flat shaded meshes.
This shader gives you also option for changing the outlines thickness based on the camera distance from the mesh, so you could more easily controll outlines visibility.

Edge detecion outlines shader uses custom renderer feature that calculates the edges of the objects based on the depth of the scene and meshes normals.
You can controll whether the objects should be visible behind other objects or not by adding depth mask. It is a fully screen space effect, but you can easily choose which objects are affected by this outlines.

Blur outlines shader also uses custom renderer feature that draws objects and then blurs them. You can choose between blur or simple outlines around the objects.
You can also controll whether the objects should be visible behind other objects or not by adding depth mask. It is also a fully screen space effect, but you can easily choose which objects are affected by this outlines.

### Screens

![alt text](https://assetstorev1-prd-cdn.unity3d.com/package-screenshot/b1a92384-3a8d-4f1d-aa9e-3b7d2eda9086.webp "Image1")
![alt text](https://assetstorev1-prd-cdn.unity3d.com/package-screenshot/2e6cda5f-8022-418a-8207-b085a3a55015.webp "Image12")
![alt text](https://assetstorev1-prd-cdn.unity3d.com/package-screenshot/aab05cd6-e2d6-4849-9d8d-081fc3d5be43.webp "Image2")
![alt text](https://assetstorev1-prd-cdn.unity3d.com/package-screenshot/7ec58151-141f-438c-b6d1-4200f0cbc569.webp "Image1")
![alt text](https://assetstorev1-prd-cdn.unity3d.com/package-screenshot/00476eff-d0a2-4eb4-a4be-30679d87c70a.webp "Image31")
![alt text](https://assetstorev1-prd-cdn.unity3d.com/package-screenshot/f4ea585c-bfe0-4188-be4a-fce6e96bb377.webp "Image41")