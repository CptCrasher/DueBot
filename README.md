
## Inspiration

We were inspired because of the difficulty with being able to adapt to in person classes. We found it hard to keep track of what we had to do because this semester was the first one back in person, so we figured we should work on something to help students that suffer the same problem.

## What it does

Students and people-in-general have a hard time keeping themselves organized and on task. Our new software solution, the DueBot, is a planning program that allows users to create and add tasks that they have to get done. Once complete, they can check off the task! This program is available on both a website and as a discord bot that they can install on their discord servers. The website and discord bot interact between each other to ensure that the list of tasks can be accessed from either platform.
###
## DueBot Discord Commands
Bot prefix is `-`. This prefix is placed infront of a command call to issue a command e.g. `-command [parameters]`

### Adding/Removing headers and tasks
`addHeader` - adds a header to the list \
to use: `-addHask [name]` - adds header with name of [name] \
\
`deleteHeader` - deletes a header \
to use: `-deleteHeader [header name]` - deletes header of name [header name] \
\
`addTask` - adds a task under a specified header - must specify header to use \
to use: `-addTask [header] [task name]` - adds task [task] under [header]\
\
`deleteTask` - deletes a task under a specified header - must specify header to use \
to use: `-deleteTask [header] [task name]` - deletes task [task] under [header]

### List Commands
`bringList` - resends current list \
to use: `-bringList` 

`deleteList` - deletes current list \
to use: `-deleteList` 

### Check Commands
`checkTask` - checks off a listed task 
to use: `-checkTask [header name] [task name]` - checks task [task name] listed under [header name] - task and header must exist \
\
`uncheckTask` - unchecks a checked task 
to use: `-uncheckTask [header name] [task name]` - unchecks task [task name] listed under [header name] - task and header must exist


### Other Commands
`reminder` - sets a message to be sent after an inserted amount of time \
to use: `-reminder [seconds] [messsage]` - sends [message] after [seconds] and provides an article to improve study habits

###
###
###

## How we built it

We used flask to build the web application and used discord.py to create the discord bot. We divided the work to be able to cover the most ground efficiently. Everybody on our team had to learn new subjects but we were able to deliver a project we were all proud of.

## Challenges we ran into

We faced challenges with the communication between the Discord Bot and the Website as well as the database storage for users. In addition, there were a myriad of runtime errors due to the virtual environments for flask in addition to some of our members learning Flask on the go.

## Accomplishments that we're proud of

We made the discord bot work with commands and established a function that communicates and updates the website and the discord bot at the same time and learned Flask on the go.

## What we learned

We learned a lot about discord.py and flask and especially how they can work together (for many of us it was a first experience for these). We had to learn about threading to get both processes to run at the same time. We needed to understand and implement asynchronous methods in our program for it to work properly which was completely new. We also learned key teamwork abilities to be able to meet our deadlines. It was our first time creating a login page.

## What's next for DueBot

We can create personalized lists for each user and create a better user interface for the website. There are also more discord functions we can include that could be convenient for students, like pdf to png converters, or maybe even study music. We would also like to communicate between the website and the discord bot more seamlessly.

### Screen shots
Login Page
![Demo](https://challengepost-s3-challengepost.netdna-ssl.com/photos/production/software_photos/001/838/247/datas/gallery.jpg)

Homepage
![Demo](https://challengepost-s3-challengepost.netdna-ssl.com/photos/production/software_photos/001/838/242/datas/gallery.jpg)

Bot's List
![Demo](https://challengepost-s3-challengepost.netdna-ssl.com/photos/production/software_photos/001/838/251/datas/gallery.jpg)

Bot's Reminder
![Demo](https://challengepost-s3-challengepost.netdna-ssl.com/photos/production/software_photos/001/838/254/datas/gallery.jpg)

Bot Commands
![Demo](https://challengepost-s3-challengepost.netdna-ssl.com/photos/production/software_photos/001/838/370/datas/gallery.jpg)

Webpage List
![Demo](https://challengepost-s3-challengepost.netdna-ssl.com/photos/production/software_photos/001/838/248/datas/gallery.jpg)
