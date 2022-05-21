---
layout: post
title:  "Welcome to Polaris"
date:   2022-05-19 14:26:01 +0200
categories: polaris
---
Hi, <br>
In this Post I am going to give you a short introduction to Polaris, a very cool programming language with Shell Scripting capabilities.
### Why?
Did you ever write bash scripts, like install or build scripts. I wrote a lot for some of my projects and I concluded that bash is the demonic evil in this world! That's where Polaris came in and cooled me down. I finally found peace in making Scripts which were easy to write. <br>
<br>
### Where can I find Polaris?
Polaris is made by a mastermind, a walking brain (with arms), and got published on [github](https://github.com/Innf107/polaris). If you look at the repo, you can see the install.sh script. That's all you have to execute. If you don't know what Github is and how to use it, I am going to guide you through the steps to get polaris working on your Unix machine. <br>
<br>
### How to install Polaris?
```
git clone https://github.com/Innf107/polaris.git
cd polaris
./install.sh
```
Aaand you are done. After you started that install script it prompts you with <br>
```Install binary to: /usr/bin/polaris```<br>
You can just press return and go on. When the script asks you to copy the files with sudo you type "yes" and type in your sudo password. After that, the script is finished.<br> You have polaris installed!


### Hello World!
As the traditions of the ancient ones taught us, if you learn a programming language, start with "Hello World!"
To create your first Polaris Program create a file<br>
```hello-world.pol```<br>
Now you type <br>
```print("Hello World!");```<br>
And you can execute that file with polaris like so:<br>
```polaris hello-world.pol```<br>
Aand BAAM! You just created your first Program in Polaris. <br>
Wow, that was intense, time for a break? Naahh you want to learn more isn't that right?<br>
So you executed your first program in the terminal with polaris before the script. You can also execute the script with <br>```./hello-world.pol```<br> but for that, you have to use a #! to your binary of polaris. If you didn't change the install script the binary is in <br>```/usr/bin/polaris```<br>
So at the first line of your script type <br>
```#!/usr/bin/polaris``` <br>
To make the script executable go into your terminal and type <br>
```chmod +x hello-world.pol```<br>
Now you can run your beautiful Hello World like a pro with ```./hello-world.pol```

### What Now?
ENDLESS POSSIBILITIES!!!<br><br>
You are free in doing whatever you want to do. At first, I would suggest you go to the polaris-tutorial repo on [github](https://github.com/Sebull-git/polaris-tutorial) and look at some of the example scripts. There you get a pretty good understanding of how this wonderful language works, more polaris tutorials like this will appear on here sometime in the future. 
