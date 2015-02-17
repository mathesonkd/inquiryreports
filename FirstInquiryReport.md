# First Inquiry Report

### Problem
I wanted to research how Pandora implements their Music Genome Project so that I can understand the set pieces 
to make my own personal Pandora implementation.

### Question
1. How does Pandora classify their songs?

2. How does Pandora recommend the next song?

3. Can I implement this?

### Resources
[University of Washington - Michael Rowe](http://courses.cs.washington.edu/courses/csep521/07wi/prj/michael.pdf)
[How Pandora Works](http://computer.howstuffworks.com/internet/basics/pandora.htm)

####1. Pandora's Classification
Pandora, unlike other music playlist sites, does not use collaborative filtering involved with user data. 
Pandora hires professional music listeners to spend 20-30 minutes on classifying a song (which can have 400 attributes). 
Pandora believes that the use of user data would "taint" the system they have in place, so they soley rely on the 
classification that their employees provide.
It is also worth noting that Pandora does not disclose the attributes they use to classify a song, as it is a trade secret.

####2. How does Pandora recommend a song?
Without the implementation of user data, Pandora relies on the classification of songs in oreder to recommend the next song
to the customer. In no way shape or form does the like/dislike button persuade what someone else might hear, it only limits
or promotes what you will hear.

####3. Can I implement this?
It goes without saying that the method that Pandora is using is complex and warrants a lot of man power. The first step would be to figure out how to classify songs my way. The use of User Data would be necessary to avoid time allocated to each individual song and would avoid the problem Pandora has, not uploading songs at a rate that can ever catch music that is being produced (only "worthy" music). Once the classification problem is solved putting the music in a database and selecting it based on the classification should be simple enough.
