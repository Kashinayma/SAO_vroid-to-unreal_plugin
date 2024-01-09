# VRM4U
Runtime VRM loader for UnrealEngine4

**For packaging, please download from UnrealEngine_VRM4UPlugin repository.**

## Description
VRM4U is importer for VRM.
Also it can load models on runtime.

[Document is here(I'm sorry, it's a google translation.)](https://translate.google.com/translate?um=1&ie=UTF-8&hl=ja&client=tw-ob&sl=ja&tl=en&u=https%3A%2F%2Fruyo.github.io%2FVRM4U%2F)

## Features
|||
|----|----|
|![2](https://github.com/ruyo/VRM4U/wiki/images/shot/03.png)|![2](https://github.com/ruyo/VRM4U/wiki/images/shot/04.png)|
|![2](https://github.com/ruyo/VRM4U/wiki/images/shot/01.png)|![2](https://github.com/ruyo/VRM4U/wiki/images/shot/02.png)|

- Import VRM file
- Animation
    - Generate bone, blendshape, swing bone, collision and humanoid rig.
    - Switch swing bone type PhysicsAsset/VRMSpringBone.
- Material
    - MToon simulated material. No postprocess.
- Mobile
    - Vanilla UE4Editor can use VRM on mobile by using BoneMap reduction.
    - Available on Forward/Deferred.

## Requirement
 - UE4.20 - UE4.27
 - Windows, Android, iOS, Mac(by ProjectBuild)
 - **For packaging, please download from UnrealEngine_VRM4UPlugin repository.**

## SampleMap
- VRM4UContent/Maps/VRM4U_sample.umap
![3](https://raw.githubusercontent.com/wiki/ruyo/VRM4U/images/samplemap.png)

## Usage
 - Drag and drop VRM file.

||
|----|
|![2](https://github.com/ruyo/VRM4U/wiki/images/overview.gif)|



