# js30
30 JS projects for practice

I'm going to do the Wes Bos 30 JS projects because they seem fun. 

[Source repo from Wes Bos](https://github.com/wesbos/JavaScript30)

Thanks for sharing these, Wes! 


## Process
I deleted all the solutions. I'll read the description of what I'm supposed to do, then try and accomplish it on my own.

If I get stumped, I'll watch some of the video to help me get over the obstacle.

I'll keep a log here of my progress and note when I needed to watch the video. Honour system, I promise I'll tell!

## 01 - JavaScript Drum Kit
I need to hook key events up to matching audio tags and kbd tags. Both of those tags have matching keycodes so I can just listen for keyups on the window and if there's a matching element, play the audio and attach the playing class. When it's done, remove the playing class from the kbd el.

I wrote two functions. One plays the audio. I also added a feature so that if there's currently playing audio, it is stopped and the seeking is set back to 0. That way you don't have a bunch of overlapping audio playing. The other function removes the playing class from the keyboard divs.

I've done this one before so it wasn't too bad. Fun project!

## 02 - JS and CSS Clock

This seems pretty fun. I haven't tackled this before but I feel like it'll be mostly math. Let's see how I do. I plan to use interval functions for all three hands and then at those intervals I'll increase the rotation by 6 degrees (360/60 is 6). Okay. Here I go.

Wow that was harder than I thought. The fun part was the math. I wrote a function that returns the number of degrees to set each hand to so it would match the current time. My first approach was just to rotate each hand at a certain interval, but I realized I'd forgotten to set the correct time at the start. 

I call the function once on load, to set the time. Then I pass it to an interval that occurs once a second. The function sets each hand to the correct position. I'm sure there's a more elegant way to do the math, but this works for now. 

All in all, lots of fun. Time for bed.