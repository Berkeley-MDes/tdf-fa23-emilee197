# Emily Lee's GitHub Repository

# Report 3 - Week of 09/11/2023 #
It's the last stretch of project 1! With the final deliverables of our project finalized, this week has been a big mental battle in just determining how ambitious I want to take this project and understanding what my limits are, in consideration of very tight time constraints. I wanted to challenge myself to create a completely novel design because I was inspired by the work of my other classmates and the demos our faculty mentors had walked us through. Since I actually don't have a phone stand, I wanted to still create a phone stand for personal use but one that a couple new requirements:
- fit my aesthetic (I love simple, yet cute designs!)
- simultaneously allow for charging since I am often on video call, which kills my battery quickly
- can fit my air pod case since I sometimes misplace it after removing the actual air pods for use

On Friday, I began the ideation process. In Asia, it is really popular to have animals model the design of many practical objects. Phone stands are one of them, and I remember seeing adorable ones being sold in stores when I traveled back to Taiwan over the summer. Right before the pandemic happened, I traveled to Japan for the first time and had the opportunity to see the beautiful shrines in Kyoto. One memorable thing was how reverant foxes were considered at these temples as a symbol of luck and protection. Thus, I wanted to combine these ideas to create a fox-shaped phone stand. Below are sketches of a couple ideas I played around with. I am also new to sketching, so these took over 4 hours as I struggled to figure out how to incorporate perspective correctly to convey the ideas I had. 

<p float="left">
  <img src="https://github.com/Berkeley-MDes/tdf-fa23-emilee197/blob/main/photo/sketch1.jpg" alt="1st sketch of first iteration" width="40%" />
  <img src="https://github.com/Berkeley-MDes/tdf-fa23-emilee197/blob/main/photo/sketch2.jpg" alt="2nd sketch of ideation" width="40%" /> 
</p>

The design of the fox remains the same in both designs, with the peak of the nose acting as the point of contact with the phone to keep it held at certain height, and the gap between the head and tail creating the container for the air pods. The main decision came down to how the base should be designed, since it had to be elevated to allow for the phone to charge and the wire to not snap. I wanted to challenge myself to laser cut the design so I had to plan ahead on what was practical to create through this methodology. Sketch #1 on the left incorporated a simple easel design to create height, which would be easy to implement as a simple piece to cut out and insert into the main base. Sketch #2 on the right utilized a thicker base box on the bottom to create the height needed to allow for phone charging with the wire. I liked the orientation of the foxes more in Sketch #2, but I didn't like how clunky the entire design looked. Sketch #1 was more feasible but I didn't like how the foxes leaned back and the overall designed also seemed a bit crude. 

I presented the sketches to my dad over the weekend to get his thoughts, and he gave me a great idea to find a compromise between the two sketches. Instead of creating a whole base, I could instead just create two "legs" to elevate the platform and lock them into the platform with inserts to increase stability of the entire structure if it was lifted. Below was a rough sketch of the new idea:

<img src="https://github.com/Berkeley-MDes/tdf-fa23-emilee197/blob/main/photo/sketch3.jpg" alt="3rd sketch of first iteration" width="40%" />

I liked this iteration a lot more than the first two, but I still think the overall look didn't fit the aesthetic I was going for; I wasn't satisfying my first requirement and wanted a redesign. I kept thinking of different ways to remove unnecessary pieces to the stand and eventually turned to exploring different orientations of the fox itself. By positioning the foxes legs further and acting as the stand for the phone, I could keep using the nose as the point of stabilizing the phone angle and remove a separate base all together. Below is the sketch of my final idea:

<img src="https://github.com/Berkeley-MDes/tdf-fa23-emilee197/blob/main/photo/iteration_v2.jpg" alt="second iteration sketch" width="40%" />

I loved the simplicity of this design a lot more and could picture how the pieces could come together through laser cutting. Now the challenge lied in getting this modeled in Rhino and ensuring the dimensions lined up to that of my phone. I went into the Makerspace to get Cody's opinions and advice on how to approach this problem, since I didn't even know how to start modeling this. He gave me a direction to work with, which I noted down in purple in the sketch above.

The next step was figuring out the exact dimensions between different components to ensure the phone stand was actually functional and responsive to the dimensions of my phone. In this process, I tested and measured the optimal angle (70 degrees) for my phone to be leaning at during video calls. I also measured the height at which the phone needed to be supported by the nose of the fox to ensure it wasn't too low, where the phone would be likely to flip back. Using the angle and length, I calculated the distance needed between the fox's legs and nose. For the air pod case portion, the box not only needed to have dimensions that fit the airpod case but also required me to calculate the slots in the fox for these pieces to go through. One problem that I encountered was accounting for the width of the material itself. All my previous dimensions purely focused on the internal area or volume but didn't account for the width of the plywood the stand would actually be built with. Using the scrap wood in the Makerspace, I used calipers to take 7 measurements of the plywood and calculated the average thickness (~0.22 inches). I added this measurement onto certain sides of the box (as indicated in purple ink in the sketch below) so that the box pieces would be long enough to have inserts that fit into the slots of the fox.  
<p float="left">
  <img src="https://github.com/Berkeley-MDes/tdf-fa23-emilee197/blob/main/photo/dimensions.jpg" alt="second iteration sketch" width="40%" />
  <img src="https://github.com/Berkeley-MDes/tdf-fa23-emilee197/blob/main/photo/dimensions2.jpg" alt="second iteration sketch" width="40%" />
</p>

I originally wanted to do raster engraving on the front of the fox to give it a more elegant design but in order to do that, I would need the inserts to only go through half the fox and not pierce through the other side. I realized that this wouldn’t be possible, unless I just did a really deep rastering to act as the slots, but I was apprehensive of how this would turn out. Therefore, I just decided to go with the original idea of cutting out the slots all the way through the fox platforms. 
The next step was the most difficult, which was actually modeling the fox into Rhino. This was a really laborious process, where I struggled with different techniques, such as slowly drawing polylines from points to eventually using interpCrv to draw faster curves. Cody provided me with a lot of guidance on how to underlay a picture and use it to model the curves off of. After drawing the fox, I extruded it to a width that was equal to the length of the plywood. I modeled a phone based on my iphone13 mini’s dimensions to mimic what the stand should look like during use. After I finished modeling it in Rhino, I had to create the 2D laser cutting prints. I have seen an Unroll command in Rhino but I was suggested against using it since my shape wasn’t super complex. Instead, I just manually compressed each object back to a 2D shape and laid them out on an axis, which can all be seen in the image below. 

<img src="https://github.com/Berkeley-MDes/tdf-fa23-emilee197/blob/main/photo/rhino3Dprint.png" alt="rhino 3d model" width="40%" />


The last step was exporting it into Adobe Illustrator and changing the line widths and colors to the correct settings. Unfortunately, it was here when I came upon a very odd realization: my fox was almost 18 inches long. This was likely the biggest phone stand to ever exist. It wasn’t a scaling issue since the inserts in the fox still matched the dimensions of the air pod case it was holding, so it didn’t logically make sense to me since the entire fox didn’t look that big in comparison to the phone in the rhino rendering. I had to go back into Rhino and start remorphing the points of the fox to become smaller, while still maintaining the angle the phone would be leaning at and the distance between the fox’s legs and nose. I was finally able to get it to around 11 inches, which was the minimal dimensions that would still allow me enough space to cut out the box inserts. I finally moved it back to Illustrator and imported it onto the computers to laser cut. Here, I also encountered some issues setting up the right settings to properly cut through. Even though my test cut went smoothly, my first full cut failed to cut through all the way. Even with an exacto knife, I was unable to cut it out. I tried laser cutting a second time on a new part of the wood, but I had the same issue, despite changing the settings to increase the power and lower the speed. Only certain pieces, such as the inserts and the parts of the foxes that were closer to the edges, came out cleanly. I was advised to try laser cutting in the same position a second time, but it only burned my piece more and failed to go all the way through. Eventually, I ended up taking an hour to slowly cut out the pieces, which explains why there is a lot of wood splintering on the back of the foxes. 

<p float="left">
  <img src="https://github.com/Berkeley-MDes/tdf-fa23-emilee197/blob/main/photo/lasercut1.JPG" alt="second iteration sketch" width="40%" />
  <img src="https://github.com/Berkeley-MDes/tdf-fa23-emilee197/blob/main/photo/finalFront.jpeg" alt="second iteration sketch" width="40%" />
</p>
<img src="https://github.com/Berkeley-MDes/tdf-fa23-emilee197/blob/main/photo/finalSide.jpeg" alt="second iteration sketch" width="60%" />


Overall, this project really challenged me with working with tools and understanding them to a degree high enough to manipulate them in a collaborative fashion. Rhino, Adobe Illustrator, and laser cutting all surprised me with new problems that I didn’t encounter before but pushed me to really ask questions from my peers and design specialists for further help. I tried to transfer my Rhino designs into Grasshopper but because this was new to me as well, I ran out of time trying to figure out how to convert the drawings into a bRep in Grasshopper where I was hoping to change the parameters and have them respond in Rhino. The picture on the bottom left is an image of the start of my Grasshopper file where I tried importing each piece of the stand separately. Ideally, I would have loved to be able to model my phone in Grasshopper, as well as the fox so I could see what would happen if I could change the distance between the fox’s nose and legs, or the entire size of the fox itself. However, I am glad that I was at least able to play with the parameters within Grasshopper using the original files the instructors gave us to fit the specific dimensions of my phone, as shown in the bottom right image. Since this was the triceratops level requirements, satisfying this was a huge motivation for me to try to push my boundaries in what I could design. 

<p float="left">
  <img src="https://github.com/Berkeley-MDes/tdf-fa23-emilee197/blob/main/photo/foxInGrasshopper.png" alt="first try to parametrize rhino objects in grasshopper" width="45%" />
  <img src="https://github.com/Berkeley-MDes/tdf-fa23-emilee197/blob/main/photo/GrasshopperControl.png" alt="second iteration sketch" width="45%" />
</p>


Next time, I would love to learn how to import or even build my figure directly from Grasshopper to enable the parameter functionalities. I also wish my designs had cut out more cleanly on the laser cutters, but I am still proud of my final product and the fact that I was able to create a novel design from scratch when I came in with zero background experience with these tools. Feel free to check out the video presentation of my project [here](https://www.youtube.com/watch?v=ImFG2MZH6ZM)! 


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

After sketching, I was unsure of how to proceed from the ideation point because I struggled with identifying how I could technically and concretely make these sketches into fruition. Because my background never touched most areas of engineering, I did not know what different methods or materials I could use to join certain parts or enable certain functionalities (i.e. adjustability, joints, etc). I hope to take the next week to explore different options that I can reimagine these designs with and do my best to redesign these within Grasshopper and Rhino. It was also really helpful to watch the video TJ filmed for us ("Cell Phone Stand Design, Evaluation, and Publication) to see a full workflow of a model's redesign.

This week, I also saw on Yahoo News (yes, not the most reliable but interesting nevertheless) that talked about how Steakholder Foods launched a new 3D modeling software for clients to use, hinting at a new era of 3d modeling customization! Steakholder Foods is a leader in 3D bio-printing technology that focuses on creating cellular agriculture meat products. It just announced the launch of its Light CAD Editor that offers a user-friendly interface that was designed to smoothly integrate with Steaholder Foods' fusion printers. This allows for clients to create, test, and reiterate 3D models for their bioprinters without other CAD training. This is a really interesting direction for 3D modeling in a completely different field that we normally see by allowing users to more closely mimic new food substances to other natural foods in helping us find new sustainable food production alternatives and addressing global food security. You can find the original press release [here](https://steakholderfoods.com/steakholder-foods-launches-3d-modeling-software-for-use-by-clients-ushering-in-a-new-era-of-3d-model-customization/)!

![Steakholder Foods 3D Modeling Software](https://steakholderfoods.com/wp-content/uploads/2023/09/screen-copy.webp)

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
