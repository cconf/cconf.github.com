---
layout: index
title: The C Conference
rss: /blog.rss
---

## [Tickets][register]

[Buy early bird tickets][register] through the end of May $225

## [Program][pfc]

What would you like to see? What talks do you want to give? Help define C Conf,
participate in the [reverse CFP][pfc]

## The Essential Details

- **What**: A conference about using the C programming language
- **Where**: San Diego, CA; co-located with [LinuxCon][linuxcon]/[CloudOpen][cloudopen]/[LPC][lpc]
- **When**: August 28th, 2012
- **Why**: Because C is used by everyone to solve interesting problems

[linuxcon]: https://events.linuxfoundation.org/events/linuxcon
[cloudopen]: https://events.linuxfoundation.org/events/cloudopen/
[lpc]: http://linuxplumbersconf.org
[register]: http://www.regonline.com/Register/Checkin.aspx?EventID=1096261
[pfc]: /pfc/

## Blog Posts

{% for item in site.posts limit:5 %}
{% include frontpage_blog.html %}
{% endfor %}
