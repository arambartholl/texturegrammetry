# Texturegrammetry Workshop, Aram Barthol 2016

**Code by Tyler Stefanich, UCLA Gamelab**

Project page at [arambartholl.com/texturegrammetry](https://arambartholl.com/texturegrammetry/)

Texturegrammetry is a workshop format which lets the user play with the graphics of the popular computer game Minecraft. With the help of a [processing](http://processing.org) script and a few clicks it is possible to swap out all Minecraft textures at once. The new texture set is derived from a randomized selection of tiles copied from a single picture file. Depending on this source picture the look of the game can change drastically from hyper colorized to full abstraction etc. Please find a full tutorial on how to make your own texture set including link to script below. In relation to this project it is important to mention the early works of the net.art collective [JODI](http://archive.joid.org/). With pieces like "[SOD](https://www.youtube.com/watch?v=24KQiy0U_Uk)" they were one of the first ones to modify game graphics, turning a popular video game like Wolfenstein-3D into an abstract work of art.

This workshop was conceived under my guidance at the [UCLA Gamelab](https://dma.ucla.edu/events/calendar/index.php?ID=975) during my time at [UCLA](https://dma.ucla.edu/) in June 2016. Shoutout to Tyler Stefanich who wrote the processing script. The name *Texturegrammetry* was coined by the participant Lee Tsuman and is based on Photogrammetry which is a process to generate a singĺe 3D model from many photographs. In case of Texturegrammetry we generate many texture graphics for a 3D game from a single image file.

Thanks everyone! Make your own Minecraft texture set today!

**Quick start:**

1) Place your "screenshot.png" in the folder "image-source"

2) Run the processing script. (finished when tile blinking)

3) Zip the contents of "your-minecraft-texture-from-1.9" and place it in Minecraft 1.9 resource folder.

**Full Instructions:**

All the software for this workshop is Java based, which means you can create texture sets on all platform: **Windows, Mac or Linux**. All you need is a [Minecraft](https://www.minecraft.net/en-us/download/) installation (free test account), [Processing](https://processing.org/) & [Java](https://www.java.com/en/download/).

1) Download and install **[Minecraft](https://www.minecraft.net/en-us/download/)**. Sign up for a Minecraft account and you'll be able to test the game for 120 min. (no need to buy a license for this workshop)

2) Download and install** [Processing](https://processing.org/download/)**. Start Processing to see if it is running. (Windows user, ignore the warnings, choose other options and run program.)

3) Both of these programs require [**Java**](https://www.java.com/en/download/) which is most probably already installed on your computer. In case not, get the [latest version here](https://www.java.com/en/download/).

4) The script was custom made for the **Minecraft version 1.9**. Therefore you need to setup this version. Launch Minecraft, **login** (register an account, 2h free playtime). In the launcher interface go to "**Installations**", press "**New**", type in any name, select **game version 1.9** from the drop down menu, press create. Start this installation 1.9 you just created by hitting "**play**". Select "single player" and "create new world" -> "create new world". You are now in the game. (controls: WASD, ctrl, space + mouse look)

5) Download the **TexturegrammetryMaster.zip** file and unzip. Open the Processing script file "TexturegrammetryWorkshopmaster.pde" (or drag drop on Processing window)

6) Swap out the file "screenshot.png" in the **image-source folder** with a new source picture of your choice. Important! It needs to be a .png image file with the actual name "**screenshot.png**". Please leave the folder & name structure inside the TexturegrammetryMaster folder untouched.

7) Hit the **play button** in the top bar of the Processing interface. The moment the script has finished the job a small blinking window will show all the generated texture tiles. It is done already at this moment.

8) Compress the contents of the folder "your-minecraft-texture-from-1.9" into a single **zip file**, with your name of choice like "new-textures.zip". This is your texture set. (Do not zip the whole folder)

9) In Minecraft hit escape to open the menu, go to "Options" -> "Resource Packs" -> "**Open Resource Pack folder**". This will open the location on you computer where you will need to **drag and drop your "new-textures.zip"** file.

10) Your texture pack will appear in the "Resource Packs" option menu once you close it and open it again. Then press the little play button on it to **move it to the active packs on the right side**. Hit "Done" (this might take a few seconds to load). Then -> "Done" -> "Back to game"

Done! Your beautiful textures should show up all around you!
