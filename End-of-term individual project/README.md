# AR game - Portal to Pixels
Players need to explore and find treasures by combining everyday objects and online images using the Snapchat app. The goal is to find an AR object (a flying bird🦜) in AR that matches the background sound within a specified time.

### 🎬 Video URL: https://youtu.be/HA2jxKHFjMk


## Introduction
This project was created using Snap AR Lens Studio. With the help of Snap AR's marker tracking feature, I achieved the AR effect of associating different images with 3D models. This functionality allows hidden AR objects to appear in everyday objects (such as Polaroid photos and books) and online images (such as Instagram pictures). Players can open my lens in the Snapchat app to start the game. By pointing their device at the images on everyday objects or online images, they can recognize the AR objects and follow the clues to find the next hidden image. I aim to expand the game space infinitely through this project, allowing players to start the game in any location.


## Process
### 1. Getting started with AR
Through the lessons, I was introduced to AR for the first time and successfully implemented the effect of a red cube.

Next, I searched online for ways to create AR games and learned about methods using Unity, Spark AR, and Snap AR. Among them, Snap AR allows for the creation of lenses using Lens Studio software, which can be viewed directly in the Snapchat app. So, I decided to use Snap AR to create my final project.

Snap AR Lens Studio provides various templates and pre-made scripts, such as room scanning to generate AR objects, object recognition using machine learning, and face and hand tracking. This convenience in creation opened up my creative ideas.

SnapAR URL: https://learnar.snap.com/student/catalog?lang=en-US


### 2. Choosing the AR Effect
The "Marker" technology intrigued me the most during my learning process. When the lens detects a marker image, it displays an AR effect, and the AR object can move along with the marker image. Through experimentation, I discovered that the marker image can be a physical image, such as a Polaroid photo or an image in a book, or an online image, such as a picture on a phone or computer screen. This led me to envision a project where different locations would generate different AR objects, creating a sense of a hidden world behind everyday life.

Marker URL: https://docs.snap.com/lens-studio/references/templates/marker/image-marker

![image](https://git.arts.ac.uk/22010390/jpg/blob/main/%E6%88%AA%E5%B1%8F2023-06-09%2023.09.09.png)


### 3. Iteration of ideas
Initially, I had the idea to create a short film that narrates from a first-person perspective while concealing the presence of AR. The film would depict me taking photos with my phone and discovering the existence of virtual objects in various places, such as in books, billboards, or within the phone itself, creating a sensation of living in a virtual world. If the 3D models were all monsters👹, this feature could also evoke a feeling of being surrounded by terror.

However, just as I was about to start executing this idea, I suddenly thought of developing a search-based game. Players would need to use AR to find hidden AR objects within items on a tabletop. The AR objects in this project would provide clues for the next step. For example, by flipping open a book and seeing a robot🤖️, the next model might be found by searching for a robot image on a webpage. This way, players would progress step by step, finding the target models. Additionally, I could incorporate unrelated distractor objects in certain locations to add complexity to the game.


### 4. Production and Completion
First, I created a project in Lens Studio and imported target images for "marker tracking" and "image tracking" from the Object panel. Then, I downloaded 3D models from Sketchfab or created my own. I imported the 3D models into the project (preferably in glTF format, but if it's in OBJ format, manual material addition is required) and adjusted their size accordingly. I placed the models under the image hierarchy, so they would only appear when the images were recognized.

I set up a total of 16 models, and here is the correct path to successfully complete the game:
(Background bird chirping sound was added to guide players to find the bird model)

1. The player uses AR to recognize Polaroid A, where a golden plant🌳 appears, guiding the player to find Polaroid B with a Cannes Golden Palm chair💺.

2. The player uses AR to recognize Polaroid B, revealing a fish🐟 and guiding the player to find Polaroid C or D by the seaside.

3. The player uses AR to recognize Polaroid C, revealing a beach umbrella🌂 and guiding the player to find Polaroid D by the seaside. The player uses AR to recognize Polaroid D, revealing a book📖 and guiding the player to open the book on the tabletop.

4. Flipping open the book, the first page's AR recognition reveals a right-facing arrow➡️, guiding the player to continue flipping.

5. Several distracting models, including a butterfly🦋 and a black cat🐱, appear in the first few pages. On page 23, the AR recognition of a banana🍌 is the key clue.

6. Continuing to flip, the player finds a painting in the book featuring a banana. The AR recognition of the Instagram icon guides the player to open Instagram on their phone📱.

7. After opening Instagram, the player visits my profile (yutianweii), where the AR recognition reveals an aurora effect, guiding the player to find a picture of the aurora.

8. Scrolling down a bit on my profile, the player finds a picture of the aurora and the AR recognition of a cup with the NASA logo.

9. Searching for the NASA page on Instagram and starting from the most recent posts, the player's AR recognition reveals planets🌍, meteorites, and the NatGeo logo.

10. Searching for the NatGeo page on Instagram, the AR recognition reveals an elephant🐘, guiding the player to find a picture of an elephant.

11. By using AR to recognize the picture of the elephant on the NatGeo page, the player discovers the flying bird🦜, indicating successful completion of the game.

![image](https://git.arts.ac.uk/22010390/jpg/blob/main/%E6%88%AA%E5%B1%8F2023-06-09%2023.02.02.png)

![image](https://git.arts.ac.uk/22010390/jpg/blob/main/%E6%88%AA%E5%B1%8F2023-06-09%2023.02.42.png)

After adjusting all the effects, click on "send to Snapchat" in the software, open the corresponding lens in Snapchat on your phone, and use it to recognize images in the physical space and on the internet to view the effects.


## Presentation

![image](https://git.arts.ac.uk/22010390/jpg/blob/main/%E6%88%AA%E5%B1%8F2023-06-09%2022.53.43.png)

![image](https://git.arts.ac.uk/22010390/jpg/blob/main/%E6%88%AA%E5%B1%8F2023-06-09%2022.54.01.png)

![image](https://git.arts.ac.uk/22010390/jpg/blob/main/%E6%88%AA%E5%B1%8F2023-06-09%2022.54.10.png)

![image](https://git.arts.ac.uk/22010390/jpg/blob/main/%E6%88%AA%E5%B1%8F2023-06-09%2022.54.19.png)

I invited a friend Yufei to play, and she mentioned that this game resembles "Tiger-Team" that we used to play as children. "Tiger-Team" is a series of novels written by Austrian author Thomas Brezina. The books came with special "Tiger Decoding Cards" that, when placed on an electronic notepad within the book, would reveal hidden solutions. I believe that with the help of AR, this combination of reading and gaming can be further developed and enhanced.

![image](https://git.arts.ac.uk/22010390/jpg/blob/main/%E6%88%AA%E5%B1%8F2023-06-09%2023.29.20.png)

![image](https://git.arts.ac.uk/22010390/jpg/blob/main/%E6%88%AA%E5%B1%8F2023-06-10%2000.16.23.png)


## Conclusion 
This game is an open-world game that connects the physical space with the virtual space through AR. It doesn't limit the player's game space and encourages them to explore the world freely. I believe that AR has brought new possibilities to this world, and through AR, I experienced the feeling of blending reality and virtuality. AR breaks our inherent way of seeing things and makes me realize that there are more possibilities around us.

Due to the size limitation of snapAR lens studio projects (within 50MB), I didn't set up more locations or import more models. If there were no restrictions on project size, I could incorporate more locations, apps, web searches, and other tools to design the game. If the game were turned into a platform and opened up for collaboration with others, everyone could set up models in different places, both online and offline. This would make the presence of hidden models in any corner of the world very interesting.

Upon reflection, I think that if I abandon the treasure hunt game mode, I can use this concept to tell stories. For example, recognizing models and scenes from family photo albums, enriching the reading experience by recognizing the contents of books, or applying it to exhibition spaces and commercial activities. This reflects the richness of AR applications, and in the future, I will continue to explore this field if given the opportunity.


## Reference 
1. SnapAR: https://learnar.snap.com/student/catalog?lang=en-US

2. Marker: https://docs.snap.com/lens-studio/references/templates/marker/image-marker

3. Sketchfab: https://sketchfab.com/feed

4. Mixkit: https://mixkit.co/

