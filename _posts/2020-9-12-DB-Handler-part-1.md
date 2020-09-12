---
title: "Warmup"
layout: post
date: 2020-09-13 00:07
headerImage: false
category: blog
author: Sam Yi
description: Database
---

A bit of a late start today but I am going to try to make some progress on creating working database handler code for connecting to a postgres database.

## 04:35

So tonight turned out to be quite a bit longer than I originally intended. Problems initially arose when trying to directly import the node-postgres library into the Vue application as several cryptic dependency issues kept popping up no matter where I tried to import and create a client object. This led me down a rabbit hole of messy or misleading workarounds until I realized that the issue was probably a personal misunderstanding in the overall requirements of what I was trying to accomplish. Several google searches later and I am fairly confident that I need to create a separate backend that will serve as a data access layer to my application that will communicate with the frontend through REST calls.

As an aside, after not coding for some time I had actually forgotten about [Model-View-Controller](https://blog.codinghorror.com/understanding-model-view-controller/#:~:text=Controllers,of%20giving%20commands%20and%20data.). I think this architecture is a good overall design for the application.

For additional detail, I will accomplish this separation of concerns by using Express in the backend to create routes (Controller) that will be able to handle CRUD operations (Model), passed down from my Vue components (View), and directly interact with our Postgres database to pass back to our 'Vue.'