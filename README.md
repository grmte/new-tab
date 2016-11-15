>vk@Vikass-Air ~/g/s/sc-be-new-tab> bower install

>vk@Vikass-Air ~/g/s/sc-be-new-tab> npm install

>sudo gem install sass

>sudo gem install compass

vk@Vikass-Air ~/g/s/s/src> compass compile
directory css
    write css/feeditem.css
    write css/screen.css

vk@Vikass-Air ~/g/s/sc-be-new-tab> gulp
[17:45:59] Using gulpfile ~/gt/sc-repos/sc-be-new-tab/gulpfile.js
[17:45:59] Starting 'html'...
[17:45:59] Starting 'columns'...
[17:45:59] Starting 'compass'...
[17:45:59] Starting 'coffee'...
[17:45:59] Starting 'libs'...
[17:45:59] Starting 'copy'...
[17:45:59] Finished 'html' after 75 ms
[17:45:59] Finished 'copy' after 324 ms
directory /Users/vk/gt/sc-repos/sc-be-new-tab/dist/css
    write /Users/vk/gt/sc-repos/sc-be-new-tab/dist/css/feeditem.css
    write /Users/vk/gt/sc-repos/sc-be-new-tab/dist/css/feeditem.css.map

[17:46:00] Finished 'libs' after 895 ms
[17:46:00] Finished 'coffee' after 1.05 s
[17:46:00] Finished 'columns' after 1.08 s
[17:46:00] Starting 'vulcanize'...
    write /Users/vk/gt/sc-repos/sc-be-new-tab/dist/css/screen.css
    write /Users/vk/gt/sc-repos/sc-be-new-tab/dist/css/screen.css.map

[17:46:00] Finished 'compass' after 1.24 s
[17:46:00] Starting 'default'...
[17:46:00] Finished 'default' after 8.41 μs
[17:46:01] Finished 'vulcanize' after 1.43 s

vk@Vikass-Air ~/g/s/sc-be-new-tab> gulp package

mkdir tabbie

mv tabbie.zip tabbie

cd tabbie/

unzip tabbie.zip 

Load unpackaged extension -> folder tabbie.


#Tabbie <span style='float:right'>[![Join the chat at https://gitter.im/jariz/tabbie](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/jariz/tabbie?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) [![Build Status](https://travis-ci.org/jariz/tabbie.svg?branch=master&style=flat-square)](https://travis-ci.org/jariz/tabbie) [![](https://img.shields.io/badge/Chrome-Extension-yellow.svg?style=flat-square)](https://chrome.google.com/webstore/detail/tabbie/kckhddfnffeofnfjcpdffpeiljicclbd)

![](https://cloud.githubusercontent.com/assets/1415847/7947591/5ebce982-097e-11e5-99b8-2ceb979dfda7.png)
![](https://cloud.githubusercontent.com/assets/1415847/7947610/806ab334-097e-11e5-91d4-9852390391f3.png)
![](https://cloud.githubusercontent.com/assets/1415847/7947613/86c0d312-097e-11e5-9c8d-3ce7cfa5361b.png)

###What is it?  
  
Tabbie keeps you informed, inspired, and up to date through it's beautiful and customizable columns.
Tabbie replaces your 'new tab' page with your favorite websites.
Choose exactly what content you want to see.

###Content

Tabbie has a bunch of build in columns, but **any RSS-complaint site indexed by [Feedly](https://feedly.com) can be added to Tabbie.**

Tabbie by default comes with the following services / sites;
- Dribbble
- Behance
- HackerNews
- Designer News
- GitHub
- Reddit (frontpage/multireddit/frontpage of your account)
- Lobste.rs
- ProductHunt
- Gmail
- PushBullet
- Codepen
- Chrome Apps, Bookmarks, and Top sites.

###Features
- Material design based on Google's design principles.
- Reposition columns
- Customizable grid
- Add/remove columns
- Customize column-specific settings
- Decentralized, gets it data straight from 3rd party API's
- Resize columns
- Rename columns


##Contributing to Tabbie
Want to add your favorite website? Want to add a awesome column that has nothing to do with websites? You can!  
It is extremely simple to contribute to Tabbie! You won't even need to install the extension.

- [Creating your first Tabbie column.](https://github.com/jariz/tabbie/blob/master/CONTRIBUTING.md)
