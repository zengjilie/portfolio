---
weight: 1
title: "Blog/XYZ - Full Stack"
description: "How I built a fullstack website in 5 days"
date: 2022-01-17T23:44:51-06:00
draft: false 
author: "Jilie"

tags: [ReactJS, NodeJS, ExpressJS, MongoDB, Netlify, Heroku, AWS]
categories: [Full Stack]
draft: false 

images : [/posts/blogfullstack/index.png]
featuredImage: "/posts/blogfullstack/index.png"
featuredImagePreview: "/posts/blogfullstack/index.png"

lightgallery : true
---

<!--more-->

**Duration** - 5 days

**My Role** - Developer

### [Demo Site](https://blogfullstack.netlify.app/)
### [Repo](https://github.com/zengjilie/blog-fullstack)

## Tech Stack

**Front End** - ReactJS, CSS, HTML

**Back End** - NodeJS, ExpressJS, MongoDB

**Deploy** - Netlify, Heroku, MongoDB Atlas, AWS S3 

**Dependencies** - axios, multer, bcrypt, cors, dotenv, mongoose

<!-- ## Challenges -->
<!-- * Design APIs, manage different routers and endpoints using Express.
* Design database schemas, building a server that connects to MongoDB Atlas.
* Avoid minor mistakes like typos.
* Add mini-interactions to frontend.
* Upload files inside a form, use multer to store files inside diskstorage.
* Use web local Storage to store user info.
* Fix bugs when connecting mongoDB Atlas with Heroku.
* Learn how to use AWS s3 to store image files, cause Heroku doesn't allow store files. -->

## Features
### User Login / Registration
{{< image src="./auth.gif" caption="`Authentication`">}}

### Password Encyption
{{< image src="./encryption.png" height="700px" width="700px" caption="`Encryption`">}}

### Edit/Delete Posts
{{< image src="./edit-remove.gif" caption="`Edit Post`">}}

### Update UserInfo
{{< image src="./updateInfo.gif" caption="`UpdateInfo`">}}

### Fetch Posts belong to a User / Category
{{< image src="./user-cat.gif" caption="`User/Category`">}}

### Responsive Website
{{< image src="./responsive.gif" caption="`Responsive Website`">}}

### Write Post
{{< image src="./write.gif" caption="`Write Post`">}}

### Store Image
{{< image src="./aws.png" caption="`AWS S3`">}}


<!-- ## Takeaways
* When developing, set MongoDB **Network Access** to your IP address, when deploying, set it to **anywhere** or your server IP address.
* I probably should develop the backend first, then the frontend. Hard coding the frontend wasted a lot of time. 
* Always draw out the structure of products first before starting to develop it. 
* Encrypt sensitive information is very important, I used **bcrypt** this time, next time use JWT.
* While waiting for data fetch, frontend should display a **pending status** to indicate the time.
* More familiar with **HTTP** status code.
* Learned how to deploy projects to **Heroku**.
* Learned how **AWS** S3, IAM works. -->