---
layout: post
title: Exercise 1 - The Beautiful City of Kiffa
date: 2024-10-04 12:00:00 +0100
categories: OSINT
---

As with all of these excercises, created by [Sofia Santos](https://gralhix.com/), we are provided with a Task Briefing:

> Below you can see a screenshot from a tweet containing a photo. It 
> contains all the relevant information necessary to help you find the 
> exact location.
> 
> Please identify the coordinates of where the photo was taken.
> 
> <img title="" src="https://gralhix.com/wp-content/uploads/2023/01/osintexercise001.png" alt="Screenshot of a post on Twitter / X" width="456" data-align="left">

---

### Initial Thoughts

I start by looking at the text within the image provided:

1. *Translated from Arabic* = are we in an arab country?

2. *In the morning* = we can use this to determine direction we are facing by using the shadows.

3. *The beautiful city of Kiffa* = I have not heard of this place before, but Google will help.

4. *Feb 20, 2013* = We can use this for when geolocating

Okay, let's get into Google Earth.

I start by doing a search for **Kiffa** and can see there is a town within Mauratania. From a first glance of the satellite imagery, this looks like a good match, however I confirm this with another search on Google just to confirm there are no other cities/towns that this could be.

![Satellite image of Kiffa](docs/assets/images/kiffa.jpg)

Now that I am happy with this, I can start taking a look a the image provided on the exercise:

1. We are on a tarmac road

2. The sun is in the west

3. There is a large tree on the right of the image

4. There are trees further away in the distance

5. There are telegraph poles

---

### Process

I start by using the Historical Imagery feature within the Google Earth to go back to images from 2013, as we know this is when the image was taken.

Once I have this imagery, I then start to look for tarmac roads which are going North-South. Luckily in this town, there are not a lot. I narrow down my search to 2 roads. One of the west side of the town, and another central of the town.

Next I look at the terrain in the image and as there are a lot of trees in the distance, this soon narrows my search down to the central road, based on the fact that there are now signs of forestation on the west side road.

I can now start to begin my search for the exact location.

As I know we can see some trees in the distance, this area looks to be a good starting point

Next I use objects within the image which I can try and identify. In this image, I think the main help will be the large tree(s) on the right of the image.

I rotate the satellite imagery so that I am facing south and start to search. There are about 3 or 4 trees which catch my attention, but other small details rule these out such as incorrect tree location, surrounding buildings not matching etc.

I then find a location which looks very promising.

![Zoomed in satellite image of a tarmac road in Kiffa](docs/assets/images/correct_location.jpg)

I also checked to see if the telegraph poles which are in the image are visibilty, and a historical image from 2021 clearly shows the shadows cast from these:

![A satellite image of Kiffa showing shadows cast from a lamp post](docs/assets/images/lamppost.jpg)

Based on this, I will put a marker down at: **16°36'34.24"N 11°23'52.20"W**
