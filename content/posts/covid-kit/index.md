---
title: "Covid Kit - UI/UX - Full Stack"
description: "How I built a WeChat Mini Program in 30 days"
date: 2020-07-07T23:06:21-06:00
draft: false
author: "Alex"

tags: [WeChat Mini Program, UI/UX]
categories: [UI/UX, Full Stack]
draft: false 

images : [/posts/covid-kit/index.png]
featuredImage: "/posts/covid-kit/index.png"
featuredImagePreview: "/posts/covid-kit/index-preview.png"

lightgallery : true
---

<!--more-->

**Duration** - 1 month

**My Role** UI/UX Designer, Developer

### [Demon Video]( https://www.youtube.com/watch?v=UY41zKFrZkg&ab_channel=JilieZeng)
### [Git Repo](https://github.com/zengjilie/wechat-mini-program) 

## Tech Stack

**Design** - Adobe XD, Adobe Illustrator, Adobe Photoshop

**Front End** - JavaScript, WXML, WXSS

**Back End** - Python

**Development** - WeChat Mini Program SDK, VSCode

**Visualization** - Apache ECharts

## Problem

In this project, I took COVID-19 as the topic. I started with the HMWs to find problems and design opportunities. Based on the problem's importance, social impact, and creativity. I chose precautions as my starting point.

{{< image src="/posts/covid-kit/1-hmw.png" width=700 caption="`HMWs`" >}}

## Experience Mapping
I drew an experience map to help me establish a baseline understanding of an ordinary person’s experience when searching for COVID-19 precaution information.

{{< image src="/posts/covid-kit/2-map.png" width=700 caption="`Experience Mapping`" >}}

## User Research

To better understand the behaviors and pain points of potential users. I designed a survey based on the experience map, then published it on a survey site. I received 210 replies, of which 193 were valid. Here are some key findings.

{{< image src="/posts/covid-kit/3-stats.png" width=700 caption="`Findings`" >}}

## Product Strategy

Based on the survey data I received, 78% of survey takers mainly use social media, like WeChat to gain information about COVID-19. So WeChat Mini Program is a good place to share this information. Also, we can use the user's internal social network on WeChat to promote our app.

{{< image src="/posts/covid-kit/4-strategy.png" width=500 caption="`Product Strategy`" >}}

## Information Architecture
Before starting to design the interface, I firstly specified the information architecture because it’s going to save more time in the future. I listed all the resources and pages I need to build this app and prioritized them.
{{< image src="/posts/covid-kit/5-inforArch.png" width=700 caption="`Information Architecture`" >}}

## Hi-Fi Prototype
After completing the information architecture, I started to work on the user interface and visual design.

{{< image src="/posts/covid-kit/6-proto.png" width=700 caption="`Hi-Fi Prototype`" >}}

## UI Spec

{{< image src="/posts/covid-kit/7-spec.png" width=700 caption="`UI Spec`" >}}

## Developement

I developed this project using WeChat Min Program SDK. I also used a Python crawler to collect COVID-19 data, such as COVID cases, relevant videos, and FAQs from multiple websites. Finally, I deployed the beta version of this app on the WeChat platform.

{{< image src="/posts/covid-kit/8-dev.png" width=700 caption="`Development`" >}}


## Takeaways

* There are some differences between development and design. Designers and developers should have a basic understanding of each other’s work to collaborate seamlessly.

* Optimization is very important when fetching and rendering huge datasets.

