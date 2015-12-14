title = "Joining in on the Conversation: IRC"
datetime = "2012-02-22 00:00"
author = "meskarune"
summary = "One of the quickest and easiest ways to get help and/or feedback on an open source project is through Internet Relay Chat."
tags = ["tutorial", "irc"]
----------

One of the quickest and easiest ways to get help and/or feedback on an
open source project is through Internet Relay Chat. When you join a chat
in IRC you can talk directly to project developers and get a problem
fixed very fast. On the negative side, because IRC is real time, there
is a greater chance of running into trolls and harassment, so finding
a good channel with active moderators becomes important.

To quickly try out IRC, you can use [this web client][web]. Be warned
that people might be busy and take a while to respond. Make sure to stay
and 'lurk'.

### Official hours

We have set a weekly time frame, during which community members are
guaranteed to be available:

    Saturday, 12 noon - 2 p.m. [Central Time][time]

However, feel free to join at any other time.

### Getting started with IRC

Getting connected to IRC is just a matter of installing a client,
picking a name, connecting to a server, and joining a channel. It's
a good idea to register your nick name so you can always use the same
one.

1. In Arch Linux you can install an IRC client like [xchat][] via
   pacman: 
   ```bash
   sudo pacman -S xchat
   ```
2. After you open your client choose a nickname. Some IRC clients also
   offer to let you set alternative names in case the one you pick is
   already taken.
3. After you have a name, connect to the Freenode IRC chat server.
   Freenode is mainly used by FOSS projects for software support and
   organizing. To connect to the Freenode server You can enter
   ```
   /connect irc.freenode.net:6667
   ``` in the text feild of your client, or by using the GUI of your choosen IRC client.
4. After connecting to the server, register your nick 
   ```
   /msg nickserv register <password> <email>
   ```
5. To connect to a channel such as Arch Women type 
   ```
   /join #archlinux-women
   ```
6. To get a list of current channel operators, do 
   ```
   /msg chanserv access #archlinux-women list
   ```

### Related IRC channels

#### Freenode (irc.freenode.net:6667)

`#archlinux` `#ubuntu`-women `#apachewomen` `#drupalchix` `#glofs`
(glorious ladies of free software)

#### Linux Chix (irc.linuxchix.org:6668)

`#linuxchix` `#owoot` (oceania women of tech)

### Links

- [Freenode: Registering Nicks][registering]
- [Arch Linux IRC rules][rules]
- We recommend reading the Arch Wiki page for your chosen IRC client.
  Here is a list of available pages.
- You can find configurations and color themes for command-line IRC
  clients on the Arch Linux Forums.

  [web]: http://webchat.freenode.net/?channels=archlinux-women
  [time]: http://www.timeanddate.com/worldclock/city.html?n=104
  [xchat]: https://wiki.archlinux.org/index.php/Xchat
  [registering]: http://freenode.net/faq.shtml#registering
  [rules]: https://wiki.archlinux.org/index.php/IRC_Channel#.23archlinux_rules
