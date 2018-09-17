# A Frame Primitives

## Sequence

1. [Primitives](#primitives)
2. [Skins](#skins)
3. [Documentation](#documentation)

## Setup

Have students go to [upperlinecode.com/vr](https://www.upperlinecode.com/vr) in order to access an a-frame template.

If you're working with students who already are using a development environment like Cloud9 or who want to develop locally, they can also use git to clone the [template](https://github.com/upperlinecode/a-frame-primitives-template).

## Primitives

Have students read the code and predict what three visible things they'll be able to see BEFORE previewing the code. 

#### 3D Coordinates

Have students duplicate the existing a-sphere tag. Then see if they can change one piece of the position at a time to move the sphere to just a slightly different place. The goal is to learn how the three components of the position attribute work.

Debrief the x-y-z coordinate space.

#### Playtime

Challenge students to do any / all of the following
* Build a snowman
* Give him two coal spheres for eyeballs
* Make sure his head is slightly smaller than his chest, which is slightly smaller than his body

#### Takeaways

* VR - Render A-Frame primitives on the scene

## Skins

Have students search for equirectangular snow scene. Then add it to the src of the sky. **it's important to know that A-Frame often fails to load assets linked locally - use a CDN like glitch, upload them to GitHub and link to the hosted versions, or just link to the originals**

Here's an example:

```HTML
<a-sky src="https://cdn.glitch.com/235371b4-efb1-4cd8-8d8e-a718ccc422ca%2FWinterScene.jpg?1512076346764"></a-sky>
```

Note: the glitch workspace linked at the top of this lab already includes assets for a snow scene and a snow texture. 

#### Playtime

Have students search for two different snow textures, one for the snowman, and one for the ground (the plane).

#### Takeaways

* VR - Wrap primitives in design maps or skins

## Documentation

Guide students to the [documentation](https://aframe.io/docs/0.7.0/primitives/a-cylinder.html). Have them scroll to the bottom left and identify where they can find a cylinder.

**Ask students what critically important attribute (position) is missing from the documentation for a cylinder**.

Have students add a cylinder to their scene.

Encourage students to orient themselves to these other important and fairly simple 3D primitives:
* Cone
* Tetrahedron (a pyramid with a triangular base)
* Box

And these critically important 2D primitives:
* Plane
* Circle
* Triangle

#### Playtime

Challenges:
* Make a tree
* Make a hat for the snowman
* Make a log cabin house


#### Extension

* There are a lot of REALLY cool extras in the A-Frame [Registry](https://aframe.io/aframe-registry/). That includes a particularly obviously relevant [particle](https://www.npmjs.com/package/aframe-particle-system-component) system. At this point in the course, students have used APIs and loaded in Materialize, so introducing another library loaded in through a CDN should be fairly straightforward. There's even already a great [snow](https://ideaspacevr.github.io/aframe-particle-system-component/examples/snow/) example ready to go. 
