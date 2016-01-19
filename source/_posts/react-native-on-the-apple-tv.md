title: "React Native on the Apple TV!"
description: "Showing off React Native on the Apple TV and some lessons learned so far"
date: 2015/11/12 00:00:00
categories: development
tags: react-native, react, javascript, apple tv, apple, ios
------------------

![Apple TV](/images/react-native-on-the-apple-tv/appletv.jpg)


So I've had a chance to play around with React Native for a while (I have another app
in the oven) and I have some thoughts on that but more importantly it looks sweet
on the Apple TV!

For those of you not familiar with React Native, React Native is an open source
framework developed by Facebook to control native applications through javascript.
Which is much like phonegap/cordova except there's no web view layer, just a bridge
for javascript to communicate back to ObjC/Swift or in Android's case Java.  So I
can write javascript code for Apple TV for instance, then port it easily to the Nexus TV
on Android or maybe even a web experience through Firefox. In short its an
incredibly awesome technology.

And given my background with mobile apps and TVs specifically (our startup Gui.de
built TV apps).  I feel its my mission in life to get an app on the Apple TV (especially
since it was a no show at the time of our startup). Some things I've noticed
right off the bat are....

1. There's no UIFocusEnvironment which is obvious.  Its a new iOS 9 feature more
specific to Apple TV.

2. For some reason video doesn't want its perspective to transform.  I still want
to experiment with this but for now it just locks up.  That would have looked soooo
rock n' roll.

3. React Native is cooler than I thought.  Not like it wasn't cool as hell to
begin with.

I uploaded a quick video of what I got running so far...

<iframe width="420" height="315" src="https://www.youtube.com/embed/vV1VJkeiqPs" frameborder="0" allowfullscreen></iframe>
