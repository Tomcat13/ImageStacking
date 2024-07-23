# ImageStacking
How to Use:
If you have a video, use the ExtractFrames.py file to get individual frames from the video.
Once individual frames are available, CenterLocation.py finds the centerpoint of the object being observed, in pixels, and returns an array of those x and y coordinates along with another pair of arrays which shows the change in x and y coordinates from the inital frame.


Background:
Recording some of my python code I'm using to stack images I take from my telescope

I'm about to start my graduate degree in Applied Data Science, and I'm doing this to improve some of my comp sci skills.
I love using my telescope, an 8in apeture Celestron CE.  Although I don't have any fancy cameras or censors (yet), its fun taking pictures to show friends and family what I was able to find.
Although image stacking software exists, I wanted to give it a try making some myself.
My current intentions are not to become a CV expert, so I'm unsure how far into this I'll progress, but so far I'm having a lot of fun learning CV libraries and practicing using them on my own images.

As of 7/23/24, I think this software would only be efficient for images with a single celestial focus point.  If there are multiple points this still might work, but I haven't tried it out yet.
As well, I currently have to manually filter out "bad frames."  Examples I've dealt with are gettign rid of frames that look like elipsies instead of circles, so hopefully before too long I'll figure out how to do an automatic filter that would disreguard those frames that have the most distortions.
