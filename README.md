# Emily Lee's GitHub Repository

# Report 2 - Week of 09/04/2023 #
This week's assignment to reiterate on our previous designs turned out to be a lot more difficult than before. The last week's assignment was more centered along technical understanding, in which all I had to do was watch tutorials and experimenting on the software itself. This week's requires more reflection and ideation on how to improve upon last week's design. The avenues as to which we could do this were so broad that I struggled with settling down how I wanted to proceed. The first idea I had was to completely engage in a novel redesign of the phone stand.

Every ideation always starts off with research, so I returned to the slide deck to review background details and user needs. I conducted further research to understand the problem space. For example, I looked into video shooting equipment and set-up to understand what regular YouTubers like to use in order to create a smooth video shooting experience. A [New York Times article](https://www.nytimes.com/2018/04/17/smarter-living/beginners-guide-phone-video.html) I stumbled upon summarized a couple pointers:
- Lighting (natural lighting or use external lights)
- Point of view (how is camera being angled? Use a tripod?)
- Improving audio (i.e. including USB mics)

![VideoMic](https://images.ctfassets.net/j7pfe8y48ry3/1fq7ryhVTeSGSyikgGcUKk/5f522ba878d5b35b5e9ada1cca26cfab/Screen_Shot_2018-06-18_at_5.11.21_PM.png)
![VideoLight](https://uploads-ssl.webflow.com/61005d24feea1014e5ad8d50/6265da095a148b649e1a1639_pexels-rodnae-productions-8370329.jpg.jpg)

I also watched a couple different knitting and crocheting videos on Youtube to observe what some of the standard practices in this domain are. One important thing that I extracted from this research process was that these video creators always include some, if not majority, of screen time on the actual hands and knitting pattern itself. This indicates that it is important for the video to not only capture the user's upper body but also provide an avenue to lower the orientation to focus on the pattern. 

By identifying different foundational needs of the user, I began sketching different ideas of prototypes to explore. The two sketches on the top of the page were just exploring different ways for the actual stand to be built. The bottom two sketches began experimenting with what focus areas the phone needs to capture. The sketch on the very bottom reflects the new user need for the phone holder height and orientation to be adjustable in order to account for different shooting angles. 
<p align="center">
  <img width="400" alt="Phone Stand Sketches of Different Prototypes" src="./photo/brain scribbles-3.jpg">
</p>

After sketching, I was unsure of how to proceed from the ideation point because I struggled with identifying how I could technically and concretely make these sketches into fruition. Because my background never touched engineering, I did not know what different methods or materials I could use to join certain parts or enable certain functionalities (i.e. adjustability, joints, etc).

# Report 1 - Week of 08/21/2023 #
We started off the semester running with our first project that primarily uses Rhino and Grasshopper. This was not only my first time using Rhino/Grasshopper but my first time ever using a 3D modeling software! Watching the demos was quite intimidating as everything from the basic interface to the complex code base seemed incomprehensible. I started off by watching Kyle's videos, which were incredibly detailed but because of my novelty to this domain, remained still too advanced. After struggling through the three videos, I scaled back my ego to start from the beginning...like the very basics. The Rhino introduction videos on how to even pan, zoom, and switch orientations was much more digestable and gave me hope that I could begin to tackle this software. 

I scheduled to print my phone stand on Monday morning so I had to have my file ready by Sunday night. Because of the time rush, I wasn't able to figure out how to change parameters in time through Rhino yet, so I ended up just making different customizations such as rounding of pieces and a "Mdes '24" raster. You can see them in the final photos below! I'm glad I did a test cut first with a little square because it didn't cut out at first, but after decreasing the speed to increase the power, the final pieces cut out perfectly by the second cut!


<p float="left">
  <img src="https://github.com/Berkeley-MDes/tdf-fa23-emilee197/blob/main/IMG_8654.jpg" width="33%" />
  <img src="https://github.com/Berkeley-MDes/tdf-fa23-emilee197/blob/main/IMG_8657.jpg" width="33%" /> 
  <img src="./weekly-reports/laser_cut_phone.jpg" width="33%" />
</p>

<!--
<img width="200" alt="Cool Phone Stand made of rocks" src="https://github.com/Berkeley-MDes/tdf-fa23-emilee197/blob/main/IMG_8654.jpg">
<img width="200" alt="Cool Phone Stand made of rocks" src="https://github.com/Berkeley-MDes/tdf-fa23-emilee197/blob/main/IMG_8657.jpg">
<img width="200" alt="Cool Phone Stand made of rocks" src="./weekly-reports/laser_cut_phone.jpg">
-->

Our class on Monday 8/28 was really helpful in understanding how to navigate some of the Rhino and Grasshopper files together. I was finally able to set my own parameters in Grasshopper and see them reflected in Rhino! This class helped to address one of the biggest problems I had over the weekend, which was understanding which files to open simultaneously in Grasshopper and Rhino to have the correct objects display.

<img src="RhinoGrasshopperParam.png" width="75%">

I have an iphone 13 mini, which has dimensions of 131.5 x 64.2 x 7.7 mm. I tried adjusting the parameters in grasshopper to reflect my own phone, but the first time I tried this, the programs crashed my laptop. The second time however, it worked, which is seen in the picture below in the lower right context box. I found it hard to adjust the slider bars to the exact measurements, so I ended up just finding the components in Grasshopper and manually typing in the exact measurements.

<img src="./photo/ParameterChange.png" width="75%" />

The following day on 8/30, I went into the Makerspace to work with my peers and ask for advice from the design specialists. This was definitely one of the most rewarding work sessions, just gathering insight from the specialist and knowledge sharing with my other classmates. Even through my other peers' processes, I was able to learn a lot. For example, when people laser cut using different material, such as acrylic, the width of the inserts had to be changed or else the pieces would be too loose! I was able to learn how to group together things to help organize parameters and write Python scripts in Grasshopper to create new objects or functions. I was even able to deactivate select functions that were not critical to help accelerate the loading process, which ended up helping my program run a lot faster and mitigate future program crashes. I even learned from Cody about the extents to which you could push Rhino and Grasshopper when you get comfortable with it. With his architecture background, he's been the primary engineer on projects designing stadiums and stations! With this, I feel like 3D software will continue to advance at a fast pace to enable even greater capabilities by incorporating VR and AR technologies. I heard about Gravity Sketch for the first time in one of my classes this week, and I think this is a prominent example of what direction 3D modeling software will continue growing in.

<p float="left">
  <img src="./photo/GrasshopperGrouping.png" width="40%"/> 
  <img src="./photo/RhinoGrasshopperPython.png" width="40%"/>
</p>

After all the adjustments, I finally learned how to bake from Grasshopper, to Rhino, and finally to Adobe Illustrator! This was the final Adobe Illustrator file of my 2D phone stand, which includes personalized dimensions to my iPhone 13 mini, as well as customized engravings on the bottom and back panels.

<img src="./photo/FinalAI.png" width=50%>

Overall, I thought this project was pretty challenging but pushed me to work closely with my peers and instructors/design specialists. Starting off with such a novel software that requires us to also integrate our newly acquired skills in laser cutting really pushed us to interact with a wide range of software and hardware. I think AI would have been most useful in grouping together functions in Grasshopper and creating quick summaries as to what the main purpose of each function does since is are patterns as to what components often go together in the software. This would have helped a lot when we opened the files to try to understand and change parameters, by obtaining a broader understanding of what each part was responsible for. AI could have also helped with generating more specific instructions when adjusting settings on the laser cutters. I saw that many people had to often do multiple test cuts to find the perfect power and speed to set the machines, and unfortunately ended up wasting a lot of material. If the AI system could be trained on inputs of varying material depths and types, it should be able to return a close estimate of what settings the laser cutter should be set to, in order to minimize charring or undercutting of the material. 
