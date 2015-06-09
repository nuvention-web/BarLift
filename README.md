[BarLift](http://barliftapp.com/)
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
We have approached 15 bars in Evanston to this date, and we’ve already had 12 bars on trial. After two months, 8 of those bars agreed to pay to use our service. Deal pushes have been effective, generating an average of $315 incremental bar revenue per push, which is reported to us by the bars. For DePaul, we had 30 target bars, and 25 agreed to test our product. We can convert at least 50% of them to subscription sales within one-two months of launching there.

### Problems
* A lot of bars are not tech savvy
* Bar's are not good at marketing
* Bars want a flat fee
* User's don't have a lot of incentive to click I'm interested

### Bars
#### Current customers
#### Pipeline
#### Aquisition stratgey
#### Link to contact list

### Users
#### Current Users
* 

#### Marketing campaigns
* DM Competition (March 2-6) - Launch of version 1. Single page app with ability to support a DM team. The team with the most supporters won $1000. Gained 1400 users with 500 people enabling push notifications.
* NU Bar Week (May 18-22) - Launch of version 2. Multiple deals with better social features. Had line up of exclusive bar deals for a full week. Gained Hit 2150 users, signed up 18 bars with 6 paying a subscription cost.
* DePaul bar week (May 27-June2) - Signed up 28 bars for a trial and got 200 DePaul users.

#### Aquisition stratgey
* Campus Bar week
* Campus Reps
* Student group comeptitions

#### User engagement
* 600 weekly active users
* 700 push enabled
* 80% have sent a nudge
* 39 avg interested on a deal of the day

## Product Development
The product is at completely functional state. Our apps are live in the Apple App Store, Google Platy Store. The dashboard is live at admin.barliftapp.com and can be used to enter deals into the system. Currently we have 2.14k installations of the apps and 250 weekly active users. 

### Features:
__Mobile__
* View deals in advance
* Multiple locations
* Custom User Profiles
* Nudge friends
* Save to calendar
* Interested
* Call uber
* iOS and Android
* Facebook login
* Google maps integration

__Web__
* Dashbaord
 * Schedule of up coming student events
 * Weather information
 * Competitive analytics
 * Past deal perfomarce
* Deal list
 * Calendar view or list view
 * Repeat deals on specific dats
 * Filter by community
* Deal Builder
 * Sub deals
 * Custom images
* Deal Analytics
 * Demographic breakdown
 * User engagement
 * Feedback forms
* Deal promoter
 * Buy deal of the days
 * See estimated reach
 * Dynamic pricing based on day of week and community
* Profile
 * Add multiple locations
 * View invoice

### Problems:
* Increase user engagement
* Simplify deal creation
* Encourage bars to enter deals themselves
* Improve user tracking and deal redemption

### iOS App
##### High level overview

BarLift is an app that sends you exclusive drink deals and freebies from bars & restaurants located around you!

Deals are sent in real time, giving you spontaneous options throughout the night. In-app social features enable you to stay connected with the people around you, allowing you to see who’s interested in going out and where the crowds are headed. Nudge your friends to get them to head out with you!

You can find it on the app store here: 
https://play.google.com/store/apps/details?id=com.barliftapp.barlift&hl=en

##### Next features
 - GeoTrack (implementing Geotrigger SDK) 
 - Bug fixes with dates
 - iBeacon SDK implementation -> loyalty points?
 - News feed
 - Users can subscribe to multiple communities

##### Links
* [App repo](https://github.com/TheZallen/Barlift-Android)
* [App](https://play.google.com/store/apps/details?id=com.barliftapp.barlift&hl=en)

### Android App
##### High level overview

BarLift is an app that sends you exclusive drink deals and freebies from bars & restaurants located around you!

Deals are sent in real time, giving you spontaneous options throughout the night. In-app social features enable you to stay connected with the people around you, allowing you to see who’s interested in going out and where the crowds are headed. Nudge your friends to get them to head out with you!

You can find it on the app store here: 

##### Next features
 - GeoTrack (implementing Geotrigger SDK) 
 - Bug fixes with dates
 - iBeacon SDK implementation -> loyalty points?
 - News feed
 - Users can subscribe to multiple communities

##### Links
* [App repo](https://github.com/TheZallen/Barlift-Android)
* [App](https://play.google.com/store/apps/details?id=com.barliftapp.barlift&hl=en)

### Web App/Landing Page
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
* [Dashboard](http://admin.barliftapp.com/)
* [Landing Page repo](https://github.com/TheZallen/Barlift-Web)
* [Landing Page](http://www.barliftapp.com/)





