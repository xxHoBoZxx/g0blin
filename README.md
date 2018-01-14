# g0blin

a (work-in-progress) iOS 10.3.x jailbreak

*For 64-bit devices prior to the iPhone 7 (A7 - A9)*

Made from off the shelf parts and shared research, long live the jailbreak community!


## ingredients

+ [v0rtex](http://github.com/siguza/v0rtex) kernel exploit by Siguza, vuln by Ian beer, POC by windknown
+ kpp bypass, sandbox, codesigning from [yalu102](http://github.com/kpwn/yalu102) by Luca Todesco
+ additional sandbox work from [h3lix](http://h3lix.tihmstar.net) by tihmstar
+ patchfinder from [extra_recipe](http://github.com/xerub/extra_recipe) by Xerub
+ additional patchfind work from [async_wake_fun](http://github.com/ninjaprawn/async_wake-fun) by ninjaprawn
+ Cydia by Jay Freeman


## notes

Spawns an SSH server listening on port 2222. Remember to change your passwords!

| user   | password |
| ---    | ---      |
| root   | alpine   |
| mobile | alpine   |


## important issues that are being worked on

- Touch ID does not work in App Store apps while in jailbroken mode
- Respring button panics sometimes
- support for 60/62 device/OS combos exploitable by v0rtex
- internal mechanics


## developer notes

- system daemons are not being reloaded en masse after jailbreaking


## instructions

1) Download an offical .ipa file from [g0blin.sticktron.net](http://g0blin.sticktron.net)

2) Install using [Cydia Impactor](http://www.cydiaimpactor.com)


## support

| iOS     | iPod 6G | iPhone 5S | 6   | 6+  | SE  | 6S  | 6S+ | iPad Air | Air 2 | 5G (2017) | Pro 9.7" | Pro 12.9" | Mini 2 | Mini 3 | Mini 4 |
| ---     | ---     | ---       | --- | --- | --- | --- | --- | ---      | ---   | ---       | ---      | ---       | ---    | ---    | ---    |
| 10.3    |         |           | y   |     |     |     |     |          |       | y         |          |           |        |        |        |
| 10.3.1  | y       | y         | y   |     | y   | y   | y   |          |       |           |          |           | y      | y      |        |
| 10.3.2  |         |           | y   | y   |     | y   | y   |          |       |           |          |           |        |        |        |
| 10.3.3  |         |           | y   | y   | y   | y   |     |          |       |           |          |           |        |        |        |


## much love

Siguza, Ian Beer, windknown, Luca Todesco, xerub, tihmstar, saurik, uroboro, Abraham Masri, arx8x, psycho tea, cryptic; tyler, the creator, my muse, Dr. TC, for keeping me alive in 2011; madflav0r coco diaz, bert k, the joe rogan podcast, J.P., for helping me find my way in 2016; mom.

I am extremely grateful for everyone whose open-source/public contributions to iOS research and developement made this software possible :)

peace.love.beauty.


&nbsp;


&nbsp;


<img src="http://data.whicdn.com/images/35103248/original.jpg" width="100%"/>


<p align="center">😈</p>
