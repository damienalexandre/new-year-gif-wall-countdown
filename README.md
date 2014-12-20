# Quick & Dirty New Year's Eve gif wall

> A good party is a party where you can stare at a cat playing drums

"Fork" of http://tv.giphy.com/ with:

- new year countdown
- tag whitelist ramdomized
- tag whitelist for the actual NEW YEAR
- much better handling of image loading (preload the gif BEFORE displaying it) - no lag!

**[Demo!](http://damienalexandre.github.io/new-year-gif-wall-countdown)**

## Usage

To edit the tag lists, open the developer console and run thoses (yes, this is the hacker mode :metal:):

    tagWhitelist = ['pony', 'yolo', 'grumpycat'];
    
    // and for after new year:
    newYearTagList = ['rambo'];
    
## Thanks

- https://api.giphy.com/
- http://hilios.github.io/jQuery.countdown/

## License

            DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE 
                        Version 2, December 2004 
    
     Copyright (C) 2004 Sam Hocevar <sam@hocevar.net> 
    
     Everyone is permitted to copy and distribute verbatim or modified 
     copies of this license document, and changing it is allowed as long 
     as the name is changed. 
    
                DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE 
       TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION 
    
      0. You just DO WHAT THE FUCK YOU WANT TO.