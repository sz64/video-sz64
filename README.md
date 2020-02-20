# video-sz64
video-sz64 created by GitHub Classroom

## Overview
This package will allow users to input a twitter handle and be returned a video of the twitter handles tweets for the day. 


## Use
The way to interact with the package is shown in main.py. To summarize, the user must create a class object, and call the tweet2vid function of that object, and a folder will be created with the associated video. 


## Design Decisions
Currently the class can only handle 5 requests at a time. This in most cases will not bottleneck the app unless the twitter handles called have hundreds of posts in a day. This also depends on the user's computer specs as it runs multiple processes for each request. To be safe the number 5 was chosen so even the simplest of machines could run the code. 
