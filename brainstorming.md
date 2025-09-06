# Brainstorming

This file is used to document your thoughts, approaches and research conducted across all tasks in the Technical Assessment.

## Firmware

### Wednesday 3 September
To be honest I have no experience using docker so that has been my primary challenge today. I've been consulting youtube and official documentation to get a grasp on it and the concept of containerisation.

### Friday 5 September
I've just managed to get docker running. I've faced several errors over the past two days which I've had to overcome which I'll provide an overview of below:
    1. Unable to locate dbcppp directory -> this was caused by me importing it into the overarching daq-technical-assessment directory meaning that when I ran docker from the firmware directory it wasn't able to see the contents of the parent folder. I solved this by moving it to the firmware directory.
    2. Missing certain dependancies -> I had to install certain dependencies like libxml2-dev which weren't obviously tied to the dbcppp package.
    3. Syntax -> this was my primary issue as I wasn't at all familiar with the docker or cmake syntax. I've had to teach myself the fundamentals of the syntax to get this project up and running.

I overcame these challenges with a mix of reading official docker documentation, forum posts and generative ai (chatgpt).

### Saturday 6 September
Today I attempted to complete stage 1. Again, today was a big learning day in terms of figuring out how to interact with docker beyond just writing code for it and getting it up and running. I learnt a lot about the array of commands that you can use in the docker terminal. I used chatgpt to assist with writing the bulk of my main file as I simply didn't have time to read about all of the ins and outs of using dbcppp. It still has some bugs which are preventing full functionality. 

Unfortunately I didn't get through nearly as much of this technical assessment as I would've liked. I probably spent too much of my time on learning as pretty much all of the content was foreign to me. In hindsight I probably should've jumped into programming earlier with less knowledge and learnt more through trial and error. That being said I'm pleased I have a better understanding of docker now and I'm on my way to understanding dbcppp.


## Spyder

## Cloud