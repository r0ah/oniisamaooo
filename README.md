I have this setting on my computer for a while now and before I forget again. Here are the dialog scripts for OOO. If you're planning on translating the game then feel free to clone the files. Once you're done translating the text repack the imh.cpk (see tools).

Concerning the text space, don't worry about it. You can have as many space as you needed if modify the lua script.

> Ex: call_WinMsg( ID.name, ID.txt, ID.voice, "" );

You can actually modify everything in the lua script. The lua programming is pretty straightforward and some of the codes are even documented and categorized. I think we have a potential renpy-application here that we can use to build with our own visual novel game, well except the 3d aspect of the game can be removed I guess. As long as you know what you're doing you could build your own light novel using OOO assets :)

With that said, it is possible to adapt the whole light novel. The only problem is that I don't know how to save the game without it going into the character select screen which then triggers the battle. There is also the issue with the character emotions. You'll have to supply each emotions per dialogs as needed. Not to mention character and bg arts. Aside from those issues isn't it nice to read the whole light novel in your PSVita complete with bgm? One can only wish.

Moving on, I haven't figured out the images yet so you'll have to do those. The images are stored in phyre container and the format is in GXT. In theory you can extract the GXT image inside the phyre files by removing the header then modify the GXT image and then re-insert it back to the phyre container. Try ScarletConvert for converting GXT.

The rest of the text (menu) are somewhere in the awb files, I think...

##Info:
- Platform: PSVita
- JP Title: 魔法科高校の劣等生 Out of Order
- EN Title: The Irregular at Magic High School - Out of Order
- Game ID: PCSG00456

##Build:
- Data align: 2048
- Coding: UTF-8
- Dir. Mask: false
- ForceCompress: false

##Tools:
- cpk.bms 
- CPKTools

##Credits:
 cpk.bms - QuickBMS http://quickbms.aluigi.org
 CPKTools - Alpha Localization Team CPK Tools
