Twitch on Kodi
==================

[![Build Status](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Factions-badge.atrox.dev%2Fanxdpanic%2Fplugin.video.twitch%2Fbadge&style=flat)](https://actions-badge.atrox.dev/anxdpanic/plugin.video.twitch/goto)
![License](https://img.shields.io/badge/license-GPL--3.0--only-success.svg)
![Kodi Version](https://img.shields.io/badge/kodi-isengard%2B-success.svg)
![Contributors](https://img.shields.io/github/contributors/anxdpanic/plugin.video.twitch.svg)

Watch your favorite gaming streams on Kodi.

LOGIN
----------------

1. Go to __Settings - Login - Get OAuth token__ and visit the url you are prompted with  
   _The prompted url is case-sensitive, if your skin's text is all UPPERCASE you will need to switch to Estuary/Confluence to see the proper url_
2. Login/Sign-up and Authorize TTV on Kodi
3. Input your new OAuth token in __Settings - Login__

FAQ
----------------

* I can't find the Twitch.tv add-on in the Kodi add-on manager!

> Make sure you are using at least Kodi 15 (Isengard), Kodi 16 (Jarvis).

* I'm having issues with the playback of streams (buffering, dropping, stuttering).

> This Add-on does not handle any aspect of the playback of Twitch streams (that would be the Kodi Video Player), it simply tells Kodi what to play.
> The Add-on does however provide Quality Options which may help if your internet connection / computer specs are below requirements for HD streams.
> Try making sure that the Kodi Add-on "InputStream Adaptive" is installed, and Adaptive Quality is enabled in Twitch.tv's Add-on settings.

* Which features require an OAuth token?

> Live Notifications, Following (all menus), Follow/Unfollow, Subscriber only content, IRC (Chat)

What's next?
----------------

Things that need to be done next:

* Suggestions welcome.

Credit where credit is due.
-------------

Thanks to all the people who contributed to this project:

StateOfTheArt89 (Founder of this project), ccaspers, CDehning, Giacom, grocal, KlingOne, kokarn, Kr0nZ, Liquex, MrSprigster, stuross, ingwinlu, mCzolko, ha107642, G4RL1N, spiffomatic64, stevensmedia, anxdpanic, xsellier, lucabric, dadobt, torstehu, kravone, beastd BtbN, Preovaleo, Blayr, bamberino.

This addon utilizes python-twitch https://github.com/ingwinlu/python-twitch (a project which derived from an early version of this addon and has grown to deserve recognition of its own). Thanks to ingwinlu for his continued work on the project.
