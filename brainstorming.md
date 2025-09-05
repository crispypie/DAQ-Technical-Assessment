# Brainstorming

This file is used to document your thoughts, approaches and research conducted across all tasks in the Technical Assessment.

## Firmware

### Wednesday 3 September
To be honest I have no experience using docker so that has been my primary challenge today. I've been consulting youtube and official documentation to get a grasp on it and the concept of containerisation.

### Friday 5 September
I've just managed to get docker running. I've faced several errors over the past two days which I've had to overcome which I'll provide an overview of below:
    1. Unable to locate dbcppp directory -> this was caused by me importing it into the overarching daq-technical-assessment directory meaning that when I ran docker from the firmware directory it wasn't able to see the contents of the parent folder. I solved this by moving it to the firmware directory.
    2. Missing certain dependancies -> I had to install certain dependencies like libxml2-dev which weren't obviously tied to the dbcppp package.
    3. Syntax -> this was my primary issue as I wasn't at all familiar with the docker or make file syntax. I've had to teach myself the fundamentals of the syntax to get this project up and running.

I overcame these challenges with a mix of reading official docker documentation, forum posts and generative ai (chatgpt).


## Spyder

## Cloud