# PixelArtTool_3Dto2D
 Transform a 3d animated model to a 2d sprite sheet with toon lighting.

#How to use:
1.) Import Character+animation into the MODELS folder. Change Rigging to Legacy. Change Textures to Legacy import from model. Attach 3d material. 
2.) Add and position character into the REND scene. Change the animation method to always animate.
3.) Use the CAPTURECARD script to create the sprite sheets. Export to EXPORT => SpriteSheets folder. 
4.) Change to point filter, no compression, sprite 2d, sprite mode multiple. Use Sprite Editor to cut the sprite sheet to size
5.) Drag the Regular Sprite Stack into the game scene. When prompted to create animation set the folder to EXPORT => Animations
6.) Go to the Mats_SpriteAni folder and create a new material and assign the Normal Map sprite sheet to the material. 
7.) Character is ready to use! To export to another project, copy the \PixelArtTool_3Dto2D\Assets\EXPORT folder to your new project. After the folder has been imported you can now delete the \PixelArtTool_3Dto2D\Assets\EXPORT\EXAMPLE folder. 

Notes to self:
This was initally built on unity version 2021.3.11f1
Characters used Mixamo and Fuse
