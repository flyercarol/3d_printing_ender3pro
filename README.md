# 3d_printing_ender3pro
Git for Ender 3 Pro prints
- Marlin compiled bins are located [builds_marlin2.0_e3p_v4.2.7]
  - Marlin V2.0.9 is compiled for Ender 3 Pro with Creality silent motherboard V4.2.7
  - Built on 20220302

- Printed and collect-worthy stl files located in you know, [stl] folder
  - e3p_upgrades : worthy upgrades for Ender 3 Pro
    - I don't own these stl, they are downloaded from Thingiverse and copyright belong to the authors unless stated otherwise
  - background_stand : Extremely useful A3/A4 paper holder to quickly erect a portable background for photography


# For beginners
0. Use octoprint with Raspberry Pi to gain control over your print status.
I recommend using Raspi 3B+/4B/02W for better video streaming and connect you pie to 5GHz Wifi, so the video streaming do not throttle over 2.4GHz Wi-Fi bandwidth.

0a. Level your bed.

1. If you do not yet know how to draw 3D models and output stl files, [Thingiverse](https://www.thingiverse.com/) is a great place to start with.
Numerous generous designer share their designs over there and I recommend you buy them a coffee if they saved you some time!
After you downloaded or designed your first model and output as .stl files, you now want to move on to print it on your 3D printer!

2. You will need a slicer, to tell the 3D printer how to print them one layer at a time.
You can think of it as the printer lives in a 2D world, which progresses layer by layer at Z-axis.
Slicer software tells it where and when to move the nozzle, and how much filament should be extruded.
I recommend [Cura](https://ultimaker.com/software/ultimaker-cura), a popular and free slicer software with a lot of buttons and dials, perfect for beginners up to amateurs!
You can use some default settings first and then start to tweak them according to your environment.
- If you live in a cold area, you may want to get a thermal box/jacket for your printer to prevent warping
- I highly recommend using "Brim" settings in the bed adhesion
  - It ensures better adhesion to bed for your printed model, uses less filament and can be easily removed (especially compared to raft)

3. Now you want to start printing, Level your bed!
Print some X or squares around your bed to test the bed level.
Once done perfectly, you rarely need to redo it unless your ambient temperature changes a lot, or you always move your printer around.

5. Start with calibrating esteps using some calibration cube.

6. More to come! Have fun at the mean time.



