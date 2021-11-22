
# Youtube twitter feed


## About the system

Youtube has a page showing all the trending videos. [This](https://www.youtube.com/feed/trending?bp=6gQJRkVleHBsb3Jl) is the link to the page.


## Requirements gathering

**Candidate:** What factors decide the trend of the video?  
**Interviewer:** Trend is determined by number of likes, comments and views on a particular video.  

**Candidate:** Should the list of trending videos be personalized?  
**Interviewer:** Here you can assume that the list is not personalized. We have a global list of trending videos.  

**Candidate:** Time appears very crucial here. Let's say a video that was trending at some time in the past has again started to get more views now. Will it become trending again?  
**Interviewer:** That's a great question. Let's say in this case the video ll be trending again.  

**Candidate:** So based on the above requirement, an old video can become treding again.  
**Interviewer:** Precisely.

**Candidate:** Given that we have 3 parameters to decide the trend of a video, what is the order in which the parameters are considered?  
**Interviewer:** Well, you can choose any algorithm you wish to determine the trend score.


## Design thought process

