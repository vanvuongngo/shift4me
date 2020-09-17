# Shift4Me
Automatic Gear Shifting


Shift4me is designed to be very simple to use. But “under the hood” there’s a lot going on. Apart from the normal handling, this manual will tell you how to adjust some parameters to suit your preferences such as cadence, gear changing speed and much more.
In this manual we’ll use “DG” as short for Derailleur Gears, so with x-amount of sprockets, and “HG” for Hub Gears, with internal gears in the rear wheel.
Don’t forget to post any comments you may have - positive or negative - or feature requests on the forum of the website.

www.shift4me.com

[heise.de news](https://www.heise.de/news/Shift4Me-Automatische-Fahrradschaltung-mit-Arduino-4873946.html) [2020/08/25]

[chip.de news](https://www.chip.de/news/Fahrrad-Hack-So-bekommt-Ihr-Rad-eine-automatische-Gangschaltung_182934165.html) [2020/08/29]

[Arduino.cc blog](https://blog.arduino.cc/2020/09/09/shift4me-is-an-automatic-bicycle-shifter/) [2020/09/09]

[Shift4Me - workbench demo video](https://www.youtube.com/watch?v=9t_GTWhJj9I) [2020/09/15]

[Eindhoven Maker Faire](https://eindhoven.makerfaire.com/maker/entry/216/) [2020/09/26-27]


## Contributors


Jan Oelbrandt <info@shift4me.com>

Van Vuong Ngo [vanvuongngo@github](https://github.com/vanvuongngo)

[![Shift4Me - Automatic Gear Shifting](https://img.youtube.com/vi/caMIED0Iqpo/maxresdefault.jpg)](http://www.youtube.com/watch?v=caMIED0Iqpo "Video: Shift4Me - introduction")

[![Shift4Me - workbench demo video](https://img.youtube.com/vi/9t_GTWhJj9I/hqdefault.jpg)](https://www.youtube.com/watch?v=9t_GTWhJj9I "Video: Shift4Me - workbench demo")

### What?
Shift4Me is a system that you can add to a bicycle. It is an electronic device that shifts your gears, based upon cadence (the rotation of your pedals). Its goal is to keep you in a comfortable gear setting, so your bike ride is comfortable and efficient. You can add a Shift4me to any bicycle that has a single cable (spring return) gearing system - that includes standard “cassette” derailleurs, hubgears (internal gears in the rear wheel axle), that means 95% of the market.

### Why?

The system is in another ballpark than the (getting ever more popular) electric pedal-assist bicycle. It doesn’t add power to gain speed. However, because the system keeps you in the most appropriate gear, it makes you cycle more efficiently. Shift4Me can be added to a non-pedal-assist bicycle, in that aspect it is unique in the world (as far as I know). But if you add it to a pedal-assist bicycle(*) you not only get the most efficient ride and best battery performance, it will also help to reduce wear and maintenance.

### Who?
Shift4Me is intended for cyclists that want to have the most comfortable ride possible without having to worry about shifting to be in the right gear. It is designed to be a “no-brainer”: only a single button is present, and that even doesn’t have to be used if you don’t want to. (the button is actually a dual function button that does “bypass” and “reset”). Just turn the power on and enjoy the ride, that’s the main goal.

### How?
Shift4Me is a do-it-yourself project: it is not available as a finished, ready-to-use system. You have to build it yourself - there’s a comprehensive build manual. Only (reasonably) commonly available components are needed. It is an open-source platform which “techies” can change, improve and experiment upon.
(*) The past years, some companies have been introducing automatic gear shifting to their pedal-assist systems and bicycles.

see [Documents](/documents)

see [Basic Components - Parts list](https://github.com/vanvuongngo/Shift4Me/blob/master/installation/Shift4Me-basic-components.pdf)


# Installation Instructions

Assuming you have the [Arduino IDE](https://www.arduino.cc/) or [Visual Studio Code](https://code.visualstudio.com/) with [PlatformIO](https://www.platformio.org/) installed on your computer.

see [Installation](/installation)

# Maintenance

The whole Shift4Me system is reasonably water-proof. But it is not advisable to leave your bike outdoors all year long.... not only for the Shift4Me...
If the system is installed by capable hands, everything should be virtually maintenance-free. Just don’t leave the power on for too long if you’re not cycling, that will possibly kill the battery. When I go shopping, I leave it on because I don’t like shopping. I’m always in and out of the store in like 10 minutes, so I don’t bother to turn the system off for such a short period of time. After some time of cycling with the system: if you feel that Shift4Me is no longer shifting in the right sprocket of your DG, or it’s shifting in between gears of your HG, then first try to adjust the cable adjusters. In the same way as you would on a non-Shift4Me equipped bicycle. If that doesn’t help, redo the calibrate procedure as described in the Build Manual.
