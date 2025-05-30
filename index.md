---
title: "Winston de Jong"
---


### About me:
Hey there, I'm an undergraduate student at Rose-Hulman institute of technology, studying Computer Engineering a minor in Computer Science. Hoping to find a career where I can make a difference in people's lives.


### Projects:

#### Files Community
I spent a couple years as a lead developer on this project, during which I obtained and triaged feedback from clients on bugs they encountered and features they wanted, and tested and approved contributions made by other developers. I also debugged and fixed bugs reported by users, totaling hundreds of merged pull requests, and spearheaded the development of many features.


[Website](https://files.community/);

[![ReadMe Card](https://github-readme-stats.vercel.app/api/pin/?username=files-community&repo=Files&title_color=87ceeb&text_color=87ceeb&bg_color=181818)](https://github.com/files-community/Files)

#### Replit Platformer
Utilizing Replit Play, I developed a platformer that load a 2d map of tiles from a file, and loads/unloads them as the player moves across the screen. I used this as teaching material for a Python class for high schoolers.

[Website](https://github.com/winston-de/replit_platformer);

[![ReadMe Card](https://github-readme-stats.vercel.app/api/pin/?username=winston-de&repo=replit_platformer&title_color=87ceeb&text_color=87ceeb&bg_color=181818)](https://github.com/files-community/Files)


#### Simple Times
In high school, I developed several watch faces for Garmin watches accumulating over ten thousand users. My most successful was Simple Times, which I open sources since I no longer have the time to maintain it. I created created advertisement graphics, instructions, and product descriptions, all translated to three languages.

[![ReadMe Card](https://github-readme-stats.vercel.app/api/pin/?username=winston-de&repo=Simple-Times&title_color=87ceeb&text_color=87ceeb&bg_color=181818)](https://github.com/winston-de/Simple-Times)


#### Brick Breaker
A simple brick breaker game I made for my programming class years ago. Not very impressive, but I had fun making it. 

![ReadMe Card](https://github-readme-stats.vercel.app/api/pin/?username=winston-de&repo=Brick-Breaker&title_color=87ceeb&text_color=87ceeb&bg_color=181818)
![](\assets\images\brickbreakergame.png)

[Try it out here!](/Brick-Breaker/) 

### Posts:
I try to write about things I think might be helpful in the future.

{% for post in site.posts %}
<a href="{{ site.url }}{{ post.url }}">{{post.date | date: "%-d %B %Y" }} | {{ post.title }}</a>
{% endfor %}

### Curriculum:
I've taught occasional programming classes, and try to document what I do for my own reference, and for others if they find it useful. 

#### Scratch:

{% for sc in site.curriculum_sc %}
<h4><a href="{{ site.url }}{{ sc.url }}">{{ sc.title }}</a></h4>
<p>{{ sc.description }}</p>

{% endfor %}
