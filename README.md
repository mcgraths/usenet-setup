My Usenet Setup
===============

The following is a general overview of how I have my media center nearly fully automated with Usenet. It makes use of the following components:

- **Usenet Servers** - Servers that contain the actual binary files
- **Usenet Search Providers** - Sites that index and moderate available binary files on Usenet servers.
- **SABnzbd** - Application that does the physical downloading
- **Sonarr** - Application for automating TV Show downloads
- **Plex Media Server** - Applicationfor managing and serving all your TV Shows and Movies
- **Pushover** - Web service for sending push notifications to your mobile device (on successful download of TV Show or Movie)

Usenet Servers
--------------

These are the main cost of running a Usenet setup. There are two types of accounts that I use:

1. **Unlimited** - You pay a monthly/yearly fee and you can download as much as you want. 
2. **Block** - You pay a flat fee for a fixed amount of data that carries over from month to month. Once you use all the data, you need to buy another *"block"* of data.

I use a combination of both account types (3 servers in total) for maximum reliability.

My primary server is an unlimited account, and I have two block accounts as backup servers. So if a file isn't found on the primary server, it checks the backups for the missing file. This makes the block accounts last a long time, since they are only used for finding missing files.

1. [Astraweb](http://www.news.astraweb.com/) - My primary account (unlimited)
2. [Tweaknews](https://www.tweaknews.eu/) - Backup account (block)
3. [Blocknews](http://blocknews.net/) - Backup account (block)

Usenet Search Providers
-----------------------

These are the websites you use to search for files to download. Many of them come with APIs that allow searching and downloading to be automated (very important for Sick Beard), which is typically unlocked after paying a small yearly fee to become a VIP member. Most of the good providers are private and invite only.

Here are the search providers I'm currently using:

- [omgwtfnzbs](https://omgwtfnzbs.org/) (VIP)
- [nMatrix](https://www.nmatrix.co.za/) (VIP)
- [nzb.su](https://nzb.su/index.php)
- [NZB Finder](https://www.nzbfinder.ws/)

*A word of caution: I've heard reports of credit card numbers being stolen from one of the above sites, so I only pay for VIP memberships with Paypal or Bitcoin.*

SABnzbd
-------

TODO

Sonarr
------

TODO


Plex Media Server
-----------------

TODO

Pushover
--------

TODO
