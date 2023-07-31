+++
title = "Suntan telegram bot" 
description = ""
type = ["posts","post"]
tags = [
    "java",
    "dev",
]
date = "2023-07-31"
linktitle= "Suntan telegram bot"

categories = [
    "self-development",
    "pet-project",
]

+++

 {{< imgresize sand.jpg "300x300 Right" "Sand on the beach">}} 

## Overview

 In the past, I came across an article discussing the "Goltis{{< super "1">}} Scheme", a method to achieve a quicker suntan without experiencing sunburns. Over time, I often thought about how beneficial it would be to have more than just an image of this scheme. An interactive application or similar tool would enhance the experience and make it easier to understand and apply the technique effectively.

-----------------
## Realization
So after finishing another course, and still haviving some free time, I thought now is the time to finally do something about this scheme. And so I did. 
https://github.com/lublyanka/sun_tan_bot 

In this small project, I decided to create a Telegram bot instead of a standalone application. Using a Telegram bot seemed more convenient, as many of us already use the messaging app while spending time on the beach. Instead of installing something new on your phone, you can simply interact with the bot and get the information you need. This way, you can seamlessly integrate the suntan tips into your beach chat sessions and enjoy the sun responsibly.
It has support of three locale (ES, EN and RU)


#### Used technologies
* Spring boot
* JPA, Hibernate
* Maven
* Lombok 
* Junit5 + Mockito
* Telegram API library

#### Bot info
[Link to open the bot]( https://t.me/sun_tan_bot "Bot link")
 {{< imgresize bot_img.png "300x210 top" "Sand on the beach">}} 


-----------------
{{<super "1">}}{{< sub "also known as Vladimir Vuksta">}}
