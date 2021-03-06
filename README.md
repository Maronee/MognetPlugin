Mognet Plugin
=============
A simple plugin for ACT [(Advanced Combat Tracker)](http://advancedcombattracker.com/home.php), which allows your parses from Final Fantasy XIV to be sent to a Discord Guild chat, through the [Mognet Bot](https://discordapp.com/oauth2/authorize?client_id=322436422646628352&scope=bot&permissions=0).

With a fairly simple setup, the purpose is to help the raiding scene of Final Fantasy XIV to have a tool, where one can post parses and share numbers between FC members. Also, help PS4 players to track their performances without having to ask party members to post their numbers manually everytime.

You can also use this plugin as a base to send your parses to your own private server by creating a fork and changing the host to your own server.

Requisites
----------
In order to make this plugin to work properly, you will need to have both below installed and configured:

* [Advanced Combat Tracker](http://advancedcombattracker.com/includes/page-download.php?id=56);
* [Ravahn's FFXIV_ACT_Plugin](http://advancedcombattracker.com/includes/page-download.php?id=66);

Also, be sure to download the latest version of the plugin on the [releases](https://github.com/castanhob/MognetPlugin/releases) page!

Setup
-----
Check the [wiki](https://github.com/castanhob/MognetPlugin/wiki/Mognet-Setup-Guide).

Commands
--------
* !create-token : It sends you a private message with the token to allow ACT Mognet Plugin to post message on the requested channel. Only works if the bot has write permission on the channel.
* !recreate-token : It recreates a token on the requested channel.
* !remove-token: It disables a previously generated token, making the bot unable to post logs through ACT Mognet Plugin on the requested channel.
* !mognet-help: It shows the list of available commands.

Contributing
------------

1. [Fork it](https://github.com/castanhob/MognetPlugin/fork)
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create a new Pull Request

You can also contribute pointing a bug into the [issues](https://github.com/castanhob/MognetPlugin/issues) section.
The server side code is private right now, but I'll make it public soon!

Donation
--------

[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=YUN5D9RUMXE4Y)

Is the plugin being useful? Do you want to suport me and show your appreciation? You can donate via PayPal!
Every donation will be greatly appreaciated and I'll work to make it even better!

May your parses be good and enjoy the Omega raid folks! :)