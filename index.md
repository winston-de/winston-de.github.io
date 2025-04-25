---
title: "Winston de Jong"
---


### About me:
Hey there, I'm an undergraduate student at Rose-Hulman institute of technology, studying Electrical Engineers with minors in Computer Science and Robotics. Hoping to find a career where I can make a difference in people's lives.

### Blog:
I enjoy writing about random topics I know too much and documenting some of my life experiences.

{% for post in site.posts %}
<a href="{{ site.url }}{{ post.url }}">{{post.date | date: "%-d %B %Y" }} | {{ post.title }}</a>
{% endfor %}

### Curriculum:

#### Scratch:

{% for sc in site.curriculum_sc %}
<h4><a href="{{ site.url }}{{ sc.url }}">{{ sc.title }}</a></h4>
<p>{{ sc.description }}</p>

{% endfor %}


### Projects:

#### Files Community
I spent a couple years as one of the lead developers on the Files for Windows project, and put countless hours into it. I take a ton of pride in the work I did on this project, and it's amazing to see how far it's come. 
[Website](https://files.community/);

[![ReadMe Card](https://github-readme-stats.vercel.app/api/pin/?username=files-community&repo=Files&title_color=87ceeb&text_color=87ceeb&bg_color=181818)](https://github.com/files-community/Files)

#### Simple Times
One of my old hobbies, back when I had free time, was developing watch faces for my Garmin smartwatch. Simple Times was fairly succesful. and I take a lot of pride in it. I no longer maintain it, so it's open sourced for others to play around with.

[![ReadMe Card](https://github-readme-stats.vercel.app/api/pin/?username=winston-de&repo=Simple-Times&title_color=87ceeb&text_color=87ceeb&bg_color=181818)](https://github.com/winston-de/Simple-Times)


#### Brick Breaker
A simple brick breaker game I made for my programming class years ago. Not very impressive, but I had fun making it. 

![ReadMe Card](https://github-readme-stats.vercel.app/api/pin/?username=winston-de&repo=Brick-Breaker&title_color=87ceeb&text_color=87ceeb&bg_color=181818)
![](\assets\images\brickbreakergame.png)

[Try it out here!](/Brick-Breaker/) 