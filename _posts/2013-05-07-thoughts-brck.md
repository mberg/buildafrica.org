---
layout: default
published: false
---

# Initial thoughts on the BRCK

Some quick thoughts on the BRCK

Ushahidi just announced the BRCK - dubbed the backup generator for your Internet.  I got to see the latest prototype from Erik and have gotten to know Reg the hardware engineer behind the project.  

Given what I know here are some very initial thoughts given it’s still a work-in-progress, just being kickstarted and I haven’t been able to test a demo unit yet.

**First thoughts**

It’s certainly looks like a useful gadget and I want one.  I’m still smarting a bit from missing the initial $150 kickstarter offer.  It’s also really cool to see that it’s possible for smaller groups like Ushahidi (without huge engineering armies) to do something meaningful in this space.  It’s a good indication of where things are going and how intrinsic software will be to building things moving forward.

In terms of functionality, here the the things I’m excited about/hoping comes true as they represent some new features in this space.

* **Ethernet and GSM bridge** - There are a lot of routers that provide either ethernet or 3G source but few offer both (at least at this price point) while offering seamless switching between sources (I hope) when things get flacky.
* **Battery life** - I use my smartphone for tethering and it works great.  However, if I’m on the road I find I really need to limit my usage given my smartphone’s already crappy battery life.   If the Ushahidi team really equips this with a battery life enough for 8 hours then I’ll be a happy camper. 
* **Automatic GSM Settings** - while most operators now thankfully push settings APN settings to your phone in many countries that’s still not the case and finding working settings, especially in areas where mobile data adoption is low, can be very hard.   Luckily, the BRCK’s cloud service is supposed to help you automatically set this settings for you based no your provider and country.
* **20 Users support** - this is pretty big as most mobile routers or tethered phones cap limit you to 3-4 simultaneous connections.
* **Remote monitoring** - The ability to see the power level of your device and connectivity throughput on your device is pretty cool and starts to make sense when you think about using these in the field for remote monitoring.  I think this is where the Internet of Things approach they mention briefly in the video starts to come in.  I think for that you can probably make 

**Open Questions**

* **Wifi transmission range** - I’m curious to see what size antenna they pack in this thing.  My standard is the glorious 1000mw the Ubiquiti PicoStation provides.  I realize that’s probably not realistic but I hope it packs more punch than a standard home router especially if you expect it to cover any distance outside and serve up to 20 people.  The ability to add an optional omni or directional antenna would be pretty cool too.
* **Bandwidth management** - I’m hoping it supports advanced bandwidth management.  There are some great router firmware projects like [EasyTomato](http://www.easytomato.org/) that provides bandwidth monitoring but doesn’t enforce management.  If you want to use this rural schools where bandwidth might be capped for budgetary issues then support bandwidth caps will be key.  I’d be curious if Ushahidi is leveraging some of the excellent open router firmware projects out there.  It would certainly make more sense then trying to go at it alone.
* **Local caching** - I’m curious to see how the 16GB is used.  I’m hoping the BRCK comes with something preconfigured with [squid as a proxy server](http://www.tuxguides.com/using-squid-with-ddwrt/).  Providing a simple internet cache to speed up a shared connection and reduce bandwidth makes makes a lot of sense if this is to be used in a lab context.
* **If it works in Africa it’ll work anywhere!** - Well maybe not in the US if the FCC has something to say about it! One of the things I’m really hoping to learn by following this project are what the the challenges you face when introducing a new device like this in the field.  Maybe if pre-approved, off the shelf components for radio transmission are used it’s not an issue.  It’ll be interesting to follow.
* **What’s the license?** - It’s not clear from the BRCK website or kickstarter site if it’s being released under an open hardware license?  Given Ushahidi’s opensource ethos I’m a bit curious to find out.

**Some things I’d like to see in V2**

I know v1 isn't even finished yet but some features I’d like to see in v2 are:

The ability to pool bandwidth between BOTH the ethernet port and 3G sim.
Phone charger.  Ability to tap into the internal battery for emergency phone charging.
Multi-sim support.
Advanced Bandwidth management (see above)

It’ll be exciting to get my hands on one of these. For my particular situation, I know i’ll find it useful.  Kudos to Erik and the Ushahidi team for pulling this initial phase off.  My hunch is that it will be the gadget geeks in the US with a plethora of Internet options would drive initial adoption but there is nothing really wrong with that.   We’ll know after ultimately after all if there is a market in Africa for such a device if the Chinese end up cloning it!

Finally, if you want to help make BRCK a reality you and do so by going to Kickstarter and supporting their [project](http://www.kickstarter.com/projects/1776324009/brck-your-backup-generator-for-the-internet).  I think this project is worth giving a shot to see where it can go.
