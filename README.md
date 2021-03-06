# Spotify Water Cooler - Killing Productivity...one beat at a time!


## Winner of API Hackday NYC 2012 ##

![ApiHackday logo](http://209.114.47.122/wp-content/images/apihackday_logo.png)

Do you love Spotify? Do you have Spotify running on a computer in your office or shared space that blasts awesome music all the time? Are you tired of having to physically or remotely go to the computer to manage the playlists on Spotify? Well fear not... Spotify Water Cooler is here!

Search songs on Spotify and add them to your playlists being played! But this is not just to get your groove on, its a water cooler, chat with your friends, colleagues, frienemies, associates, & fellow sociopaths while you groove and choose to to groove to. Chat either with the built in chat or use voice chat in your browser powered by the awesome Twilio Voice Chat api all in your browser.

Hmmm...joined the chat a bit late and wanna know what people were talking about? TOO BAD! Real life water coolers don't have chat logs and neither do we. Don't worry, no one is talking about you behind your back *wink wink*.

## Installation and usage ##

These instructions have been written for OS X.

### Pre-requisites ###
  * [Spotify API Key](http://developer.spotify.com/en/libspotify/overview/) Download libspotify and your app key
  * [TWILIO Client API Key](http://www.twilio.com/api/client) Sign up, its SUPER easy!  
  * [Ruby](http://www.ruby-lang.org/) 1.9. Use [RVM](http://rvm.beginrescueend.com/) to manage your Ruby installations. It's good.
  * [Rubygems](http://rubygems.org/)
  * [Git](http://git-scm.com/)
  * The [Bundler](http://rubygems.org/gems/bundler) gem. Install with 'gem install bundler'.
    
### Install dependencies ###

Use Bundler to install project dependencies for you:

    $ bundle install

This will install gems and various other dependencies if not already on your system. It will also create a Gemfile.lock file which will ensure that dependencies do not change unless you explicitly rerun `bundle install` again.


### Configure ###

Copy the example config file:

    $ cp config.yml.example config.yml

Enter your Spotify and Twilio credentials in config.yml. Make sure to place your Spotify key (e.g. spotify_appkey.key) in the root folder of the project.

### Run locally ###

To run the application:

    $ thin start
    
The app will be viewable at `http://localhost:3000`

## Screenshots ##

![Screenshot 1](https://github.com/hamin/Spotify-Water-Cooler/raw/master/screenshot1.png)

![Screenshot 2](https://github.com/hamin/Spotify-Water-Cooler/raw/master/screenshot2.png)

## Powered By ##
![Spotify logo](http://blogs.channel4.com/benjamin-cohen-on-technology/files/2010/10/spotify-logo-1.png)

![Twilio logo](http://www.twilio.com/packages/company/img/logos_downloadable_round.png)

### License ###

(The MIT License)

Copyright (c) 2012 Haris Amin

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the 'Software'), to deal in
the Software without restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the
Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.