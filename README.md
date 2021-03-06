# README

# Project 2 - PikQ

## Description

Developing websites involves working in groups where its members have different ideas, tasks delegated, and versions of have to be controlled and reconciled when using the GitHub. The purpose of the project is to make and develop a website in a group. Our group is comprised of:

1. [Weijia Li](https://github.com/unicar9)
2. [Lingxiao Wang](https://github.com/douMax)
3. [Ryan Ruan](https://github.com/Ryan-ruan)
4. [Jonathan See](https://github.com/jonathansee2013)

## Features

PikQ is a website developed to allow users to take pictures from their webcams. These pictures can be edited and posted to their profiles which in turn appear in the gallery. Users can also comment on and "Like" posts from other users.

The group utilized the following applications to achieve a functional yet visually appealing website:

Ruby
* Ruby on Rails - wireframe upon which the website is built
* [acts_as_votable](https://github.com/ryanto/acts_as_votable) - Ruby Gem used for the upvotes ("Like") of the posts

AJAX - enables the user to see the updated number of votes ("Likes") without reloading the page

JS Libraries
* [fabric js](http://fabricjs.com/) - allows users to edit images by changing and adding stickers, drawings and texts to it
* [webcam js](https://github.com/jhuckaby/webcamjs) - enables PikQ to obtain data from the users' webcams and take pictures
* [tracking js](https://trackingjs.com/) - detects users' faces as they move which in turn can be superimposed by another image (e.g. other people's faces)

Plugin
* [AddThis](http://www.addthis.com/) - allows users to share their edited images to social media sites such as Facebook, Pinterest, Weibo and Yummly.

API
* [imgurAPI](https://apidocs.imgur.com/) - allows users to upload their edited images unto imgur anonymously

CSS Framework
* [Semantic-UI](https://semantic-ui.com/) - responsible for creating a clean and presentable website
* [Colorzilla](http://www.colorzilla.com/gradient-editor/) - responsible for the purple gradient background appearing throughout the website

Cloud Platforms
* [Cloudinary](http://cloudinary.com/) - responsible for storing all the images saved in PikQ
* [Heroku](https://www.heroku.com/) - where PikQ is deployed


## Result
Here is [our live site](https://pikq.herokuapp.com)

Welcome Page
![pikQ](app/assets/images/screenshot1.png)
![pikQ](app/assets/images/screenshot2.png)
![pikQ](app/assets/images/screenshot3.png)


## Lessons Learned

* The most useful important learned in working in groups is that conflicts will inevitably arise so resolving these quickly saves time which can be devoted to completing tasks.

* Planning from the beginning by listing and delegating tasks helps keep the team on track. In our group, we used [teambition](https://www.teambition.com/) to keep track of the tasks progress and share resources useful to accomplish the tasks.

* Never be afraid to explore other applications to give the website the best user experience.


## Wish List

The website would have provided better user experience if the following features were incorporated which would have allowed users to:

* Crop and resize the uploaded image
* Upload stickers they wish to add and choose fonts for the text editor
* Comment on other user's comments using the nested commenting system
* Add tags
* Use search function


## Acknowledgments

We would like to thank Luke Hammer for leading us to the right direction by introducing us to webcamjs, trackingjs and AddThis and helping us fix the bugs in our face detection feature. We also would like to thank Matthew Edge-Williams for answering our queries and assisting us with the Github-related problems.

Lastly proper acknowledgments goes to the following:
* [freepik](http://www.freepik.com/) - source of the sticker used in the editor function of PikQ
* [I Hate Tomatoes](https://ihatetomatoes.net/how-to-create-css-glitch-effect/) - tutorial on how to create a CSS glitch effect on PikQ when hovered on the welcome page
* [Adorable Avatars](http://avatars.adorable.io/) - collection of avatars for users who choose not to upload their face photos in their user profile
