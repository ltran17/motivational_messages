# `motivational_messages`

In this Python tutorial, you will use APIs for YouTube and OpenAI to create motivational messages based on a popular content creator's videos.

### Intended Audience

This guide is geared toward junior data scientists and assumes comfort with Python and the Pandas package. Intermediate Python programmers will probably get the most out of this. Beginners can certainly follow along!

### Objectives

In this guide, you will
* Use YouTube's API to get metadata about videos on a YouTube channel
* Use an open source package to get transcripts from YouTube videos
* Use OpenAI's API for Chat GPT3
* Be exposed to motivational messaging -- take what works for you and leave the rest

### Contents

00. [API Setup](https://github.com/ltran17/motivational_messages/blob/main/notebooks/00-api-setup.ipynb): YouTube and OpenAI's APIs 
01. [Video Metadata](https://github.com/ltran17/motivational_messages/blob/main/notebooks/01-metadata.ipynb)
02. [Video Transcripts](https://github.com/ltran17/motivational_messages/blob/main/notebooks/02-transcripts.ipynb)
03. [Motivational Talks](https://github.com/ltran17/motivational_messages/blob/main/notebooks/03-motivation.ipynb)

### Why this tutorial

Tutorials and how-tos often gloss over the difficulties of learning a new skill and rarely mention the forehead-to-keyboard moments. Polished presentations make me think I'm alone in my struggles, and yet when I talk to real, live people, it is clear that I'm in very good company.

It is a standard task to be told to use an API with only available documentation to guide you. For both the YouTube and ChatGPT APIs, you will consult the documentation to create your private keys and create requests. I will not walk you through the process, but I will call out a couple of things that really slowed me down so that you can be on the lookout for them. It's a good bet that you will stumble over something completely different, and that is ok. 

### What motivated me to create `motivational_messages`

At the beginning of the pandemic, a group of my friends created the QuaranTeam: we streamed exercise videos three times a week to support and motivate each other since we could no longer meet at the gym. Our virtual meetings provided solace during some very hard days. As much as I needed the social support, the exercise also helped clear my mind and maintained -- improved! -- my physical and mental health. After trying out a variety of trainers, our favorite became [Sydney Houdyshell](https://www.youtube.com/@sydneycummingshoudyshell). 

The inspiration for this tutorial came from a conversation with the QuaranTeam as January 2023 kicked off and Sydney's messaging reflected the fresh start of a new year. She ends every workout with a cool down, and as she leads us through stretches, she free-styles a motivational talk. Her words can really hit home! I haven't been good about jotting down notes about what she said.

This project is its own New Year's resolution: keep track of Sydney's words of wisdom, but do it programatically. (I'm a data scientist, so, yeah, I'm scripting this and not writing it by hand.) An achievable, measurable goal! The notebooks in this repository reflect my journey as I deciphered two APIs and explored the game-changing technology of ChatGPT3. 
