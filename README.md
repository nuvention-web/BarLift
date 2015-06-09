[Barlift]
======

Drink Spontaneously.

>BarLift uses your location to send you relevant, high quality deals when you're out at night.

### People

* [Shikhar Mohan] - iOS 
* [Nikhil Pai] - Web
* [Zak Allen] - Android
* [Divir Gupta] - Web
* [Mats Johansen] - Business/Marketing/Design
* [Oskar Melking] - Business/Marketing/Design

### Submodules

* [Barlift-iOS] - Shikhar
* [Barlift-Android] - Zak
* [BarliftWeb] - Nikhil

[Shikhar Mohan]: https://github.com/shikharmohan/
[Nikhil Pai]: https://github.com/nikhilpi/
[Zak Allen]: https://github.com/TheZallen/
[Divir Gupta]: https://github.com/divir94/
[Mats Johansen]: https://github.com/matsglj/
[Oskar Melking]: https://github.com/oskarmelking
[Barlift-iOS]: https://github.com/shikharmohan/BarLift-iOS-v2/
[Barlift-Android]: https://github.com/TheZallen/Barlift-Android/
[BarliftWeb]: https://github.com/nikhilpi/BarliftWeb/

[Barlift]: http://www.barliftapp.com

## Customer Development
`Current status`
`Problems`

### Bars
`Current customers`
`Pipeline`
`Aquisition stratgey`
`Link to contact list`

### Users
`Current Users`
`Marketing campaigns`
`Aquisition stratgey`
`User engagement`

## Product Development
`Current status`
`Problems`

### iOS App
##### High level overview

BarLift is an app that sends you exclusive drink deals and freebies from bars & restaurants located around you!

Deals are sent in real time, giving you spontaneous options throughout the night. In-app social features enable you to stay connected with the people around you, allowing you to see who’s interested in going out and where the crowds are headed. Nudge your friends to get them to head out with you!

You can find it on the app store here: 
https://itunes.apple.com/us/app/barlift/id965946420

##### Next features
 - GeoTrack (implementing Geotrigger SDK) 
 - Bug fixes with dates
 - iBeacon SDK implementation -> loyalty points?
 - News feed

##### Link to submodule setup/deploy readme
- To deploy/develop the app, download Xcode and run
- https://github.com/shikharmohan/BarLift-iOS-v2

### Android App
`High level overview`
`Next features`
`Link to submodule setup/deploy readme`

### Web App
##### High level overview

The purpose of this web app is to create deals, buy deal of the day slots and view consumer and competetive analytics. BarLift uses your location to send you relevant, high quality deals when you're out at night.

The dashboard is a Angular.js app served by a node stack. Data is stored using a Parse.com app and reached over the REST API. Theming was done using INSPINIA, a purchased CSS package. The app was hosted on heroku.

The landing page is a different webapp rendered using node and handlebars.js

##### Next features

More deal creation features
- Feeding deals automatically from other sources like SmallTabs
- Recurring deals

Better Analytics
 - A network graph of BarLift users to see get a sense of closely connected the BarLift community is
 - Visualization to geotag Twitter tweets related to bars
 - Detailed location tracking data

New services
 - Deal reminder text message service for bars
 - Bar feedback notifications
 - Weekly emails about deal performace of bars in a community

##### Links
* [Dashboard repo](https://github.com/nikhilpi/BarliftWeb)
* [Landing Page repo](https://github.com/TheZallen/Barlift-Web)





