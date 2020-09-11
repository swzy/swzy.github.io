---
title: "Warmup - The Duece"
layout: post
date: 2020-09-10 22:31
headerImage: false
category: blog
author: Sam Yi
description: Blog
---

Didn't do as much studying yesterday but I think it's slightly more about just acquiring some consistency. Working in small bites will likely help this out.

## 23:01

Working on the A1 website, I'm running into many questions as to how to test out the database first. I want to upload the data to a Postgres database on AWS or some cloud provider so that I can begin writing the code to fetch that data, but I am a bit worried that 'hidden' costs might start racking up before the site is even somewhat functional. I should definitely write create a local database and do it that way.

## 23:41

I realized that I installed pgAdmin4 before and decided to go ahead and use a sample database [Pagila](https://github.com/devrimgunduz/pagila) based pff of Sakila that was designed for MySQL. This was done by essentially running the SQL script directly through the query editor. I created a child component that uses the basic HTML/CSS layout I created for the product page a while ago.

My goal is to begin querying from my local postgres database using the [node-postgres]() npm package but there seems to be alot of documentation and best practices involved in setting this up, namely a database controller file that will act as a data access layer. I will take a break here and resume - hopefully tomorrow. Accomplishing this will really go a long way in setting up this project nicely as I'll have alot of data to actually work with for the design of the other Vue components.