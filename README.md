# Caught-You
Have a doubt on your partner? Try this!!

## Inspiration
Last week, I met my school friend, he was feeling very sorrowful that day. As soon as I asked him the reason, he sobbed and wailed, "My girlfriend cheated on me!!". After focusing on the whole matter, I got to the decision that, I'm gonna help my other brothers too. I'll not let anyone break someone's heart. 
I thought, if I could make something that can catch the truth before the actual heartbreak, then many people can get aware and somehow they'll not feel it at that level.
This is my inspiration for this project. 



## What it does
It's a security camera, which makes you aware when someone else enters the room.
It can blow an alarm, capture anonymous objects whether its living or nonliving. It can also record as per the instruction of codes. One can easily operate it if he/she wants to find any moving object in the room out of their presence. 



## How I built it
In this project, I've simply used the available module of python i.e. OpenCV ([link](https://pypi.org/project/opencv-python/)) and WinSound (In-built module).
I've used Visual Studio Code as my IDE and GitHub as my Version Controller.
Here are some steps that I've followed while building:-
1) Imported both the modules, OpenCV and WinSound in the project.
2) CV2 will start the computer camera.
3) While the camera is turned on, Firstly I've organized two frames to get the differences between the static and the dynamic frame. 
4) Added some properties of capturing the motion, like grey, blur, contours for accurate capturing, etc.
5) Then added the constraints in the motion, so that the camera does not capture the unwanted movements.
6) Then I made the contours visible to the user so that he/she can justify what is the object, the camera is capturing.
7) I made the "q" alphabet, the key for destroying the camera, so that no one, other than the user can destroy it. 


## Accepting improvement
I'm accepting all the pull requests that makes this project better.
To make the similar environment as like my pc, just copy this [link](https://pypi.org/project/opencv-python/) and paste it in your terminal.
