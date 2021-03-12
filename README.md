# hero-video

This is a template hero type site. Big hero section with a side nav. This project is ripped from Brad Traversy. He did wonderful work and I agree that the template is a great idea. I should have more, so I grabbed this one and made some changes. Here is a link to that video. [Brad Traversy](https://youtu.be/8MgpE2DTTKA). This template features a side nav menu and typical hero CTA info.

[img](https://github.com/Developer3027/hero-video/blob/main/glynn_coco_20210312_023507.png)

In addition, Brad used a video and a overlay using blend modes in css to amplify the video. I used the same approach, just different feel. I also included audio and included a small equalizer for a visual.

### Web Audio
In working with the web audio I found a security feature that I had to work with. You can use the audio tag and load up the music file. You can set attributes and have the player and controls which is awesome. In setting up the eq, I found this video to be very helpful. [Squeaky Tech](https://youtu.be/rY2v7HIWQEI). After getting the eq to work I found that the audio context requires user interaction. I am loading the music and creating the context upon load, before user interaction. This is ok for the player and if you just click play and listen to the whole song, no problem. However, if you press pause, then refresh the page, the audio context will suspend due to that interaction before page load and the context being set. This being the case I set a button to resume the audio context in the case that it becomes suspended.

### Resources
The video file I used came from [Pexel](https://www.pexels.com) Pexel by Suzy Hazelwood. The video was set to mute and loop.

The music I used was a total find while searching through Soundcloud by Glynn Coco. I am not big on hip hop or rap, but this song, given todays political climate, really inspired me in this project. I used functionality built into linux to get the song. I used audacity to modify it and put in the vinyl scratch and chop in spots. The one I created has it's own charm but I did it to wet the whistle and so the links are to Glynn Coco and the original file.

This was fun! Hope you enjoy.