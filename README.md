![pic0](https://user-images.githubusercontent.com/29318142/34314744-ea5fda62-e7b1-11e7-9e4b-4f3935440ba4.png)

I have this setting on my computer for a while now and before I forget again. Here are the event dialog scripts for OOO. Anyone who wants to translate OOO can use and clone the files.

You can modify everything in the lua script. The lua programming is pretty straightforward and some of the codes are even documented and categorized so if you're having trouble with the text space, don't worry about it. You can have as many space as you needed if modify the lua script.

> Ex: call_WinMsg( ID.name, ID.txt, ID.voice, "" );

I haven't figured out the images yet so you'll have to do those. The images are stored in phyre container and the format is in GXT. In theory you can extract the GXT image inside the phyre files by removing the header then modify the GXT image and then re-insert it back to the phyre container. Try ScarletConvert for converting GXT.

The rest of the text (menu) are somewhere in the awb files, I think... I'm not sure.

## Simple how-to
- Dump your copy of the game, if mai good, if nonpdrm then you'll have to decrypt the `ux0:app/PCSG00456` with VitaShell
- Copy the file `ux0:app/PCSG00456/Data/CRIFS/imh.cpk` to your computer
- Use [CPKTools](https://drive.google.com/open?id=1bowod7FFJ49FJKv_koBCiBHGn6tc_9vz) to unpack the cpk file
- Clone or download repo and paste it in the extracted `imh.cpk`. Overwrite existing files when asked.
- Once done translating simply repack cpk file with CPKTools. See *Build* if you're having problems like game having errors upon startup, etc.

## Info:
- **Platform**: PSVita
- **JP Title**: 魔法科高校の劣等生 Out of Order (Mahouka Koukou no Retousei - Out of Order)
- **EN Title**: The Irregular at Magic High School - Out of Order
- **Game ID**: PCSG00456

## Build:
- **Data align**: 2048
- **Coding**: UTF-8
- **Dir. Mask**: false
- **ForceCompress**: false

## Screenshots:
![ss1](https://user-images.githubusercontent.com/29318142/33984112-78db8952-e0f1-11e7-8227-a21b93639fa0.png)
![ss2](https://user-images.githubusercontent.com/29318142/33984113-791205fe-e0f1-11e7-9dd9-7cb758d643a4.png)
![ss3](https://user-images.githubusercontent.com/29318142/33984114-794528e4-e0f1-11e7-9a0e-a8f7d551ed14.png)
![ss4](https://user-images.githubusercontent.com/29318142/33984116-7977c394-e0f1-11e7-8ddc-1d0211c4bad6.png)

## Credits:
- CPKTools
