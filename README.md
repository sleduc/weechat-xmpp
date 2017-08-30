weechat-xmpp
============

A fork of the jabber plugin for weechat

Quick start:

    add server: /jabber add <server_name> <username>@<server_FQDN> <password> [<server_FQDN>[:<port>]]
    connect: /jabber connect <server_name>
    chat: /jchat <nickname>
    join room: /jroom <roomname>@conference.<server_FQDN> [<optional_user_nickname>]

Commands provided by script:

    /jabber
    /jchat
    /jmsg

The configuration is stored in ~/.weechat/jabber.conf
