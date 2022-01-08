---
title: "Covid Kit"
description: "How I build a weixin mini program in 30 days"
date: 2022-01-07T23:06:21-06:00
draft: true
author: "Alex"

tags: [WeChat Mini Program, UI/UX]
categories: [Mobile App, UI/UX]
draft: false 

images : [/posts/covid-kit/wx.png]
featuredImage: "/posts/covid-kit/wx.png"
featuredImagePreview: "/posts/covid-kit/wx.png"

lightgallery : true
---

<!--more-->


### [Demon Video]( https://www.youtube.com/watch?v=UY41zKFrZkg&ab_channel=JilieZeng)

## Problems / HMWs

In this project, I took COVID-19 as the topic. I started with the HMWs to find problems and design opportunities. Based on the problem's importance, social impact, and creativity. I chose the precautions as my starting point.

{{< image src="/posts/covid-kit/hmw.png" width=700 caption="Lighthouse (`HMWs`)" >}}

I drew an experience map to help me establish a baseline understanding of an ordinary person's experience when searching for COVID-19 precautions

{{< image src="/posts/covid-kit/map.png" width=700 caption="Lighthouse (`Map`)" >}}

## User Research

To better understand the behaviors and pain points of potential users. I designed a survey based on the experience map, then published it on a survey site. I received 210 replies, of which 193 were valid. Here are some key findings.

{{< image src="/posts/covid-kit/stats.png" width=700 caption="Lighthouse (`Findings`)" >}}

## Product Strategy

Based on the survey data I received, 78% of the suvery takers mainly use social media platforms, like WeChat to gain information about COVID-19. So WeChat Mini Program is actually a good place to share these information. Also we can use the uesr's internal social network on WeChat to promote our app.

{{< image src="/posts/covid-kit/strategy.png" width=500 caption="Lighthouse (`Product Strategy`)" >}}

## Information Architecture
Before starting to design the interface, I firstly specified the informaiton architecture because it's going to save more time in the future. I listed all the resources and pages I need to build this app and prioritized them. 
{{< image src="/posts/covid-kit/inforArch.png" width=700 caption="Lighthouse (`Information Architecture`)" >}}

## Hi-Fi Prototype
After completing the information architecture, I started to work on the user interface and visual design

{{< image src="/posts/covid-kit/proto.png" width=700 caption="Lighthouse (`Hi-Fi Prototype`)" >}}

## UI Spec

{{< image src="/posts/covid-kit/spec.png" width=700 caption="Lighthouse (`UI Spec`)" >}}

## Developement

I developed this project using WeChat Min Program SDK. I also used Python crawler to collect COVID-19 data, such as COVID cases, relavent videos, and FAQs from multiple websites. Finally I deployed the beta version of this app on WeChat platform.
[Git Repo](https://github.com/zengjilie/wechat-mini-program) 
{{< image src="/posts/covid-kit/dev.png" width=700 caption="Lighthouse (`Development`)" >}}


## Tech Stack
**Front-End** - JavaScript, WXML, WXSS

**Back-End** - Python

**Development Tool** - WeChat Mini Program SDK, VSCode

**Visualization Tool** - Apache ECharts

## Takeaways

There is a huge difference between development and design. Designers and developers should have the basic understanding of each other's work to collaborate seamlessly.



