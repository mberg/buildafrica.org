---
layout: post
title: "mHealth: Time to get Social!"
description: ""
category: 
tags: []
---
I’m back in Mysore, India were where we are focusing on trying to get the initial release of our Drishti app for Auxiliary Nurse Midwives (ANMs) out.  I’ll write more about Project Drishti later but it’s wonderful to be back, knee deep with my amazing team in service/system design, one of the things I like best.

One of the things that struck us, as we reviewed our system design, is we that completely overlooked one of the key needs expressed by the ANMs – to make it easier to communicate - to coordinate and share information between other.  Or in other words, be more social.

Maybe it’s because everyone is focused on the “building blocks” like mobile data collection and reminders but it struck me that one of the things not discussed enough in mHealth, mAg, etc. is why aren’t the tools we’re building more social?

![](/images/posts/chw_broadcast.png)

**Health Team Messaging**

One of the initial core features of ChildCount+ we considered, but for some reason never pursed, was to allow users to pick their own @alias (similar to twitter) and allow users to send each other direct messages or broadcast to the group - at no cost via ChildCount+’s toll-free number.  It’s a feature we developed but didn’t advertise and eventually dropped – I think maybe because we were afraid of SMS costs.

Recently, I was speaking to my good friend Kieran Sharpey-Schafer who helped oversee UNICEF’s RapidSMS Malnutrition Monitoring project in Malawi.  He told me that they implemented an even simpler idea, just allowing CHWs to send a broadcast message to everyone in the network and he was quite taken back by the almost immediate adoption.   It quickly became the way meetings were organized, CHWs reported problems and provided encouragement.  On the rare occasions, when someone would use the list for things like sharing a soccer score, the CHWs were quick to self-police reminding the offender that this was an important channel reserved for work. 

While obviously this particular implementation could be made more efficient it clearly worked and indicates a clear need most current mHealth systems (that I know of at least) are overlooking.

In India where SMS costs are extremely low, especially for aggregators, SMS group chat services have long been popular.  In India and for well-funded or state subsidized projects SMS represents a potentially good option.  The main driver, I predict, that will make mHealth more social, as what made us more social, are smartphones.  Integrating messaging directly into mHealth apps seems like such a basic and obvious win that we’ve decided to attempt this with Drishti.   One could even envision message integration to the point where it could be to refer patients to each other.  

The other important opportunity here is the ability to provide to the health worker an up-to-date (managed) and actionable directory of other health care providers.   The ability to reach out to a specialist for advice offers is just one example of the benefit of facilitating such a network.   When I think of the potential tie in with great initiatives like Switchboard to create a national level health social network I get really excited.

Technically, open protocols like XMPP (which powers Google Talk) are perfectly tailored for this with a plethora of mature servers and clients to support this. 

Health Team Messenger constitutes a proverbial “low-hanging fruit” if there ever was one.    There is also a real risk though of not acting fast.   If health workers aren’t provided the right tools, they will flock to ones like Facebook Messenger (shudder) that already exist.  Don’t laugh. It’s probably has already started to happen.

**Check-Ins**

Another idea, probably much more controversial, but equally intriguing are check-ins, an idea popularized by services like Foursquare.

One of the challenges of managing an tuning a health system, especially ones that are rural and rely on voluntary or low paid extension workers, is knowing where people are.   Voluntary check-ins at clinics or households, which could be incentivized through gamification and much less draconian then GPS tracking, could provide important operational data related to health service provision.  Check-ins could also be linked to notifications or alerts such as a prompt to pick up certain medicines if their stocks are low.

Alternatively, check-ins could be made required to help better ensure doctors are at work and teachers are at school.    Or it simply could be used, to let people know that the doctor is in.

**Worth a deeper look**

Strategies to make mHealth more “social” is is certain to catalyze even more innovation in this fast moving space.  Consider alone the different ways social could provide additional support to patients and increase their collective voice.  The introduction of social won’t be without it’s controversy as we work to develop approaches appropriate for health.  It promises to be a long and interesting process.   Shall we get started?
