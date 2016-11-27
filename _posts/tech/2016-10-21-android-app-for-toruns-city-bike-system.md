---
layout: post
title: Android app for Torun's city bike system
categories: ["tech"]
description: Explore Torun and locate nearby city bike stations with my free Android app
date: 2016-11-21T22:17:40+02:00
---

I'm a big fan of Toruń, and I've spent a lot of time exploring the city over the last year. I'm also a big fan of cycling, so when Toruń's city bike system relaunched in March after its winter hiatus, I took to cycling around the city. As an outsider, it wasn't always easy locating the nearest bike station. Sometimes, I'd walk to a known station, only to find that there were no bikes. I couldn't find an app to help me out with the city bike system, so I [made one](https://play.google.com/store/apps/details?id=com.vinay.trm) myself that uses the data available on the website.

The app uses the Google Maps Android API to show all the bike stations in the city as well as your current location. Using the Locate icon floating action button, you can locate the bike station that's nearest to you from any location in the city.

[![TRM Torun Android app home screen](/public/images/trm-torun-app/home.png){:class="img-centered img-mobile"}](/public/images/trm-torun-app/home.png)

Once you've identified a bike station, you can check the number of available bikes, and use the Navigate icon floating action button to get walking directions to the station from Google Maps. The app is capable of working offline, using a cache of bike stations, but, needless to say, realtime bike availability information needs a working internet connection.

[![TRM Torun Android app bike station information](/public/images/trm-torun-app/bike-info.png){:class="img-centered img-mobile"}](/public/images/trm-torun-app/bike-info.png)

**Technical details**

The app supports Android 4.0.3 (API Level 15 - Ice cream sandwich) and above, covering 98.6%+ of all Android devices <sup>[[1]](https://developer.android.com/about/dashboards/index.html)</sup>. The context-aware floating action button, sliding bottom sheet and the themed action bar are based on [material design](https://developer.android.com/design/material/index.html) guidelines. The app is compatible with the "new" permission system applicable to Android 6 and above: Devices running Android 6 (Marshmallow) and above use runtime permission requests, while all permissions must be granted at installation time on devices running older versions of Android.

Check out the TRM Torun on [Google Play](https://play.google.com/store/apps/details?id=com.vinay.trm)

