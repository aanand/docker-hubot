Dockerfile for an IRC-enabled Hubot
===================================

This is also available in the Docker public image index as [aanand/hubot](https://index.docker.io/u/aanand/hubot/).

Building
--------

    $ git clone https://github.com/aanand/docker-hubot.git
    $ docker build -t hubot docker-hubot

Running
-------

    $ docker run -e 'HUBOT_IRC_SERVER=irc.example.com' -e 'HUBOT_IRC_ROOMS=#nameofroom' -e 'HUBOT_IRC_NICK=hubot' hubot
