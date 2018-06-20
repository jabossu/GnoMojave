# GnoMojave
Using Gnome Vanilla to do a Mojave-like time shifting wallpaper

## What is this ?
I wanted to have a time shifting wallpaper emulating what we saw of the next MacOS version, Mojave. I love the idea of a wallpaper that slowly changes with the time of day, and this one is gorgeous.
So, rather than installing a 3rd party app, I bodged gnome. And it work wonderfoully. You can find more about this story in my post on Reddit : https://www.reddit.com/r/gnome/comments/8sh7oa/a_nice_trick_to_create_a_mojavelike_time_shifting/

## How to use it ?
* download the mojave.xml file
* download the Mojave images from this github project : https://github.com/xtai/mojave-dynamic-heic
* rename the images so they will be in the right order, and starting from mojave-02.jpg to mojave-17.jpg
* copy all the images and mojave-timed.xml to /usr/share/backgrounds/gnome/
* backup adwaita-timed.xml (in case you want to use it later...)
* copy and rename mojave-timed.xml to adwaita-timed.xml
Then, go to gnome stettings and change your brackground to your new time-shifting desert ! Tada !

## How to improve it
If you like that idea and you find other images that would make good time shifting wallpaper, just edit the adwaita XML file. It's syntax is fairly easy to understand, and well documented, i'm sure you'll figure it out.
