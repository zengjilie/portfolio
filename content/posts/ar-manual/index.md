---
weight : 3
title: "AR User Manual - UI/UX - AR"
description: "How I build a AR user manual in 7 days"
date: 2020-08-08T11:18:50-06:00
draft: false
author: "Alex"

tags: [Vuforia, Unity, UI/UX]
categories: [AR, UI/UX]
draft: false 

images : [/posts/ar-manual/index.png]
featuredImage: "/posts/ar-manual/index.png"
featuredImagePreview: "/posts/ar-manual/index.png"

lightgallery : true
---

<!--more-->
**Duration** 7 days

**My Role** Everything

**Team** Myself
### [Demon Video](https://www.youtube.com/watch?v=OSb187lFrDY&ab_channel=JilieZeng )

## Problem 

In this project, I chose the user manual as my design subject. First, I did a simple field study to find common problems people encounter when using user manuals. Based on these qualitative data, I listed some hypothetical design goals to help me build a general direction for my later user research.

{{< image src="/posts/ar-manual/1-problem.png" width=800 caption="`Problem`" >}}

## User Research

To get a comprehensive understanding of manual users, I designed a survey and published it on a survey site. A total of 102 replies were collected, of which 100 were valid. Here are some key findings.

{{< image src="/posts/ar-manual/2-stats.png" width=700 caption="`User Research`" >}}

## Ideation

In this phase, I used the Insights, Quesitons, Ideas (IQI) method to help me generate design concepts 

{{< image src="/posts/ar-manual/3-iqi.png" width=700 caption="`Insights, Questions, Ideas`" >}}

## Storyboard
A visual representation of this product
{{< image src="/posts/ar-manual/4-storyboard.png" width=700 caption="`Storyborad`" >}}

## Development

**Development Tool** Unity3D, Vuforia  

**Modeling Tool** Rhino3D

{{< image src="/posts/ar-manual/5-dev.png" width=700 caption="`Development`" >}}


## Usability Test

{{< image src="/posts/ar-manual/6-test.png" width=700 caption="`Usability Test`" >}}

## Takeaways

* The geometric complexity of the product will affect Vuforia’s tracking performance. So for electronic products with minimal design style, it’s pretty hard for Vuforia to track them accurately

* Users' external constraints like room lighting, space, and camera quality may cause a poor user experience. So, there are some technical issues to be solved
  
* Vuforia's 2D tracking performance is so much better than 3D?

* During the usability test, users had a strong inclination to interact with virtual buttons, so enriching the virtual experience is very important for user experience

* Force users to download an AR app to experience it may not be the best solution, gonna try Web AR next time and learn Three.js