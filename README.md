
TRR_Guide 
=======


TRR_Guide is a collection of textures made to be used as example with [TextureReplacerReplaced](https://github.com/HaArLiNsH/TextureReplacerReplaced)

All of these textures are made in a bigger format than the old textures used in TextureReplacer. The originals size for these textures was usually 1024x1024, but we aren't in the middle age anymore, we can use textures sized 4096x4096 :) 

ENJOY HD TEXTURES !  

And expect lots of changes here as TRR continue to grow :)

Instructions
------------

Put the differents files in the rights folders and you are ready.

For example put the folder "TRR_SuitGuide" in the "Suits" folder of TextureReplacerReplaced if you want to see all the different textures you can make to replace suits for your loved Kerbals

The folder MMcustomTexture is there to show you how to use the new MM.cfg compatibility system for your own mod. 

As you can see, the textures are saved in .png, this is clearly not the format you need to use for your finished textures. BUT, as we use big 4k texures and flat color for the guides, the compressed png weight less than a .dds. It takes more time to load but its a lot easier to share and you don't need a special plugin to be able to see them in your explorer. 


Something usefull to know about the size and the weight of the files : 

 4096x4096 .png no compressed = 64Mb
 4096x4096 .png compressed = 200Ko - 1Mb   (from a simple texture like the guide)
 4096x4096 .png compressed = 20Mb - 30Mb (from a full detail texture)
 
 4096x4096 .dds DXT1 = 10,6Mb  
 
 The same goes for the NormalMap (NRM) :
 
4096x4096 .png NormalMap compressed = 500-600Ko 
4096x4096 .dds DXT5 = 21,3Mb 

So my advice is : use compressed .png while you work on your texture, then when all is ready to be release online, save them in .png non compressed and convert them to .dds 

!!! BEWARE !!!! 

I don't think that making a full suits set composed of the 55 textures is a good idea if you plan to make a suits for each class of MKS.
A single full set can weight up to 650Mb, so if you plan to make 14 of them ...   :) 
The jetpack and visor are not meaned to be used to all the levels, just use them if you want a difference for your level 3 and 5. 

Of course, if you make your textures in 1024x1024 (or any size you want), you wont have the weight problem (but you will have old and tiny textures :p )

Usefull tools : 
[NormalMap-Online](http://cpetry.github.io/NormalMap-Online/)
Online tool for generating Normal, Displacement, Ambient Occlusion and Specular maps 

for windows :
[KSP to DDS texture converter] (http://forum.kerbalspaceprogram.com/index.php?/topic/88972-win-ksp-to-dds-texture-converter/ )
A great and simple tool to convert your .png to .dds 
Use dxt1 for normal textures without alpha and dxt5 for NRM.  

And of course : 
[Mod Development Links Compilation](http://forum.kerbalspaceprogram.com/index.php?/topic/85372-mod-development-links-compilation-some-links-do-not-work-formatting-broken/)




Licence
-------

Copyright © 2017 HaArliNsH

Permission is hereby granted, free of charge, to any person obtaining a
copy of this software and associated documentation files (the "Software"),
to deal in the Software without restriction, including without limitation
the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL
THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
DEALINGS IN THE SOFTWARE.