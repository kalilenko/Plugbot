# Plug.bot #

A collection of tools and extended features for Plug.dj, a free live DJing service.  Inspired by TechGuard's Autowoot.  All code is written in Javascript, mostly based off of the Plug.dj API which can be seen here:  http://blog.plug.dj/p/api-documentation.html


### Features List ###

+ Auto-woot  :  Whenever the DJ is advanced, the Woot button is clicked.  Allows for AFK point farming.
+ Auto-queue [optional]  :  Whenever the user is finished playing their song, one more song is skipped, then they are re-added to the DJ Queue, or Wait List.
+ Bookmarklet  :  Easy portability.  Makes it so developers can update remotely, then users just have to click the bookmark again to update.
+ jQuery-powered GUI [in development]  :  A slide-down jQuery GUI menu which allows users to enable/disable features easily.
+ Open-source code  :  All code written for the Plug.bot script is available here on Github.  I may or may not end up extending it to multiple files.  We'll see where the development goes ;)


### Installation ###

Literally so easy.

1.  Create a new bookmark in your web browser.  In Firefox and Chrome, just click the star icon in the top right.  If you really need help with this, Google is your friend.  Or Yahoo.  Or Bing (god forbid.)
2.  Title the bookmark whatever you desire;  this is irrelevent to Plug.bot.  I named it Plugbot.
3.  In the field titled, "Location" "URL" "Website" "Link" "Place" or WHATEVER it may be, add the following:
<code>
javascript: (function () {<br />var jsCode = document.createElement('script'); <br />jsCode.setAttribute('src', 'https://raw.github.com/connergdavis/Plugbot/master/plugbot.js'); <br />document.body.appendChild(jsCode); <br />}());
</code>
4.  Save and run the bookmark while you have your Plug.dj tab open.  If it was successful, the GUI will slide down from the top and you'll be able to set it all up.


### Problems? Bugs? Questions? ###

connergdavis@gmail.com

Try to keep the subject relevant, or else I won't see it and think it's related to Plug.bot.  