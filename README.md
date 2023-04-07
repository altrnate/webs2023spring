## Prose Response ##
For my project, I wanted continue the theme of my portfolio thus far. To bring this idea into a webspace, I would like to follow a similar model to my visual 
project. My orginal idea for doing this was by using a gravity simulator to make words correlating with the icons I used in my visual product to fall, creating a jumbled 
chaotic pile of words. I wanted to make the word "Mundane" remain suspended in the middle of the page, so the reader is inclined to click that one specifically. As I 
suspected, I ended up needing to scrap this idea because it was far too advanced given I have never touched code before. I than transitioned towards where my project 
ended up going, with words randomly scattered around the page and one central "mundane" button. I origninally tried doing this by using individual "href" elements that I 
wanted to place around the screen. The code originally looked like this:
<img width="1128" alt="original attempt to make links" src="https://user-images.githubusercontent.com/122398220/230682819-f59cce32-8227-4cbc-a8b1-194a9a3ba235.png">
I quickly realized that this method was going to be increadibly repetative and time inefficient, so I began looking into automating this process. This lead me to 
encorporate JavaScript in my project, as it is not possible to do automatic processes with CSS, at least that I could find. This took an increadiblt amount of trial and 
error, as I was already struggling to understand HTML/CSS, let alone a new language. Nevertheless, with pleanty of visits to Stack Overflow, I was able to get the Words 
randomly scattered around the page exactly like I wanted using this code: <img width="1128" alt="index JS" src="https://user-images.githubusercontent.com/122398220/230683384-a7c4d588-1c4a-44b8-bb53-d4de531e24ed.png">
In this script, not only is the position of the boxes/words randomized, but the color is randomly selected from a red-green spectrum, as well as a random selection of 
font, so the end product looked like so: <img width="1128" alt="homepage for peer" src="https://user-images.githubusercontent.com/122398220/230683675-9fb5145f-1d6f-477e-ac09-1316498ad1d2.png">


Now that I had the homepage looking how I wanted it, I began working on the subpages. For each subpage, I wanted an icon that represented the idea as well as a statistic 
related to the topic. For the pages that had more than one paragraph, I originally had issues with the paragraphs displaying side-by-side, however this was fixed by 
grouping them into a "div." I then added a button that would take you back to the homescreen, however, I was having issues with the button automatically centering itself 
in the middle of the screen like so: <img width="1128" alt="home button in middle of screen" src="https://user-images.githubusercontent.com/122398220/230683872-8ca40287-317e-4c3f-8d77-ce025fbefa24.png">
<img width="1128" alt="home button in middle of screen code" src="https://user-images.githubusercontent.com/122398220/230683897-8186015a-b823-4379-be31-baad05f62b86.png">
After some trial and error, I ended up updating the styles sheet to <img width="241" alt="button fix" src="https://user-images.githubusercontent.com/122398220/230684041-043fd46a-2718-48d1-a7ea-cd91572f3b16.png">
This not only moved the button to the top, but it also changed the background color and the size of it. This produced the final subpage of: <img width="1128" alt="final subpage" src="https://user-images.githubusercontent.com/122398220/230684106-f2fb008d-90c2-4cf3-a5b8-46362f015283.png">
With the code looking like: <img width="1128" alt="Subpage example" src="https://user-images.githubusercontent.com/122398220/230684120-091bb056-fd2b-4b98-98b9-08845bc1cd92.png">
<img width="1128" alt="style sheet" src="https://user-images.githubusercontent.com/122398220/230684360-e414f334-60c2-45cd-97ae-dc28c9f4b8b5.png">
As you can see, I made the code each page as simple as possible, mainly to make the most of my time. 

When submitting for peer review, the biggest complaint was that the central button, while still drawing to the eye, was not big enough. This can be seen in responses 
from jannawohl and suchiattota

<img width="599" alt="jannapeer" src="https://user-images.githubusercontent.com/122398220/230684966-fae5017f-5ebc-4197-8773-e2f5de7c8f91.png">
<img width="585" alt="suchiattotapeer" src="https://user-images.githubusercontent.com/122398220/230684978-b47c1a24-9bed-4a7a-bf69-6dad2c41ff83.png">

This was a very easy fix, as all I needed to do was update the scale, producing this: <img width="1128" alt="peer revision" src="https://user-images.githubusercontent.com/122398220/230685036-0b6e8c59-88c9-43e7-b5b8-ea63b4a88b84.png">

**Final Thoughts**

Overall, I am very proud of myself for what I was able to accomplish in this project. Prior to this, my only experience with coding was using Visual Basics in 9th grade, so I was really going into this blind. This were many points during the project that I needed to step away due to frustration, but I was able to push through it and get to the final product. Although this may have been one of my most diffiuclt projects of University, I was still able to do it. That being said, I will be haappy to delete Visual Studio when the course concludes; I'm pretty sure coding isn't for me.
