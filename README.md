Latest version 1.12.2.1

# Snaz
>Wiki: https://github.com/JimmyAppelt/Snaz/wiki
>Project: http://jimmyappelt.be/preview/snaz  
>Changelog: http://jimmyappelt.be/Downloads/Software/Snaz/releasenotes.txt  

**Download**

>You can download snaz on the next page:  
>http://jimmyappelt.be/preview/snaz/

# Overview

* System time
* System date
* Countdown to specified time *(Live countdown. Ex. Stream live in: 0h 30m 12s)*
* Chrono Down : Countdown from value  
* Chrono Up : Count up from value
* Text line Changer
* Update Game/Status on Twitch *(with smart game and status lists)*
* Amount of current Twitch viewers
* System Info: capture and stream data real time like cpu usage, ram, processes, up- and download speed
* Dynamic Files: create a textfile or imagefile by choice and link it to any online source
* Playing now with song, artist album, album image (Currenlty supported: Spotify, Foobar2000 and winamp)

Check the wiki for more detailed information https://github.com/JimmyAppelt/Snaz/wiki

# Formatting examples
#### Time Output format info:
```php
Example $hh $mm $ss will go live as: 1h 25m 12s  
Example $hh $mm will go live as: 1h 25m  
Example $h:$m:$s will go live as: 1:25:12  
```
#### Time Output format AM/PM info: 
```php
> Same as above but the letters $tt wil output AM/PM  
> Example $h:$m:$s $tt will go live as: 1:25:12 AM  
```
#### Date Output format info:
```php
> dddd dd MMMM yyyy > Tuesday 25 june 2013  
> dd MMMM yyyy > 25 june 2013  
> dd-MM-yyyy > 25-06-2013  
```
#### Chrono Down Ouput format info: 
```php
> Example Stream live in: $h:$m will go live as: Stream live in: 1:25
> $h:$m:$s > 05:22:23  
```

> Customize formats to your needs :), these are just examples.  
> The textfiles will be stored in the subfolder TextFiles in the apps folder.  
