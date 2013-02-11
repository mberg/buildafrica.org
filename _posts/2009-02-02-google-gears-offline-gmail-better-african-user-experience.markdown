---
comments: true
date: 2009-02-02 22:37:49
layout: post
slug: google-gears-offline-gmail-better-african-user-experience
title: Google Gears = Offline Gmail = Killer African Web App
wordpress_id: 123
categories:
- Technology
- Web
---

Earlier this week with little fanfare, Google enabled browser based, [offline access](http://gmailblog.blogspot.com/2009/01/new-in-labs-offline-gmail.html) to Gmail.  While this is exciting for all of us who who have long yearned to ditch our desktop email clients, the ability to now access webservices like Gmail, even when we are offline, has enormous implications towards improving the way people living in Africa will now be able to access the Internet.

While things are rapidly improving, connecting to the Internet in Africa can still be a painfully slow experience in most places - the result of over-shared bandwidth, poorly managed backbones and the high latency of satellite jumps.  All this contributes to a very unstable connection, one that handles things like Ajax requests poorly resulting in a lot of time outs that plague many Web2.0 applications.  It's clear that many modern web apps weren't designed with African Internet conditions in mind.

Offline Gmail is made possible by [Google Gears](http://gears.google.com/) which stores a local cache of messages behind the scenes when connected.  This enables users to access a Google Gears enabled website like Gmail (Google Docs now works offline too) through a web browser and experience a similar web experience to if they were online.

While having offline access to one's webmail is a huge benefit on its own,  the emergence of Gears enabled sites is exciting for Africa for a number of different reasons:



	
  * **Dealing with poor connections with [flaky connection mode](http://groups.google.com/group/gmail-labs-help-offline/web/flaky-connection-mode)** - a Gears enabled Gmail now includes a "flaky" mode which enables you to always run off the local store with emails syncing in the background ensuring a continous user experience regardless of your connection status.  I can now finally retire my email IMAP client.

	
  * **Better bandwidth use **- The advantage of POP and IMAP is that the internet connections in Africa are typically better at streaming/straight data transfers.  Google Gears greatly cuts down on the requests of a webapp by downloading queued messages in the background similar to POP or IMAP.  While it still may be slow, at least with POP you know you'll only have to download a message once.  You also now have the option leaving your Gmail open to download messages.  Finally, while tests to verify this are required, it can be assumed that the bandwidth consumption when using Gears will be lower which is important when dealing with a pay-per-byte connectivity model which one encounters when connecting via an Edge/3G cellphone connection.  In aggregate this gain in efficiency is important when you consider that [70% of Internet within Africa is routed outside of the continent](http://news.bbc.co.uk/2/hi/technology/7063682.stm).

	
  * **I****n Africa web apps / portability is king** - client based email only works when you have dedicated access to your own computer.  Since this is rarely the case in Africa, the vast majority of people have jumped straight to webmail.  Google Gears is probably not optimal for a certain environments where there is a high user turnover (you would downloading everyone's messages).  There will undoubtedly be some clever solutions for this in short time. I could see USB keys with a [Google geared portable Firefox](http://bohemiantribe.blogspot.com/2008/08/google-gears-with-portable-firefox.html) quickly becoming the email solution of choice for African university students.  Another option would be to simply run Firefox in a lab setting from a network drive.







To access Gmail when you are offline, you will need to enable offline in your Gmail Lab settings and have the newest version of [Google Gears](http://gears.google.com/) installed.  Once enabled, Google Gears will begin an initial sync syncing approximely the last two weeks of your email.  Depending on how popular you are and the speed of your connection, this could take from 5-15 minutes.
