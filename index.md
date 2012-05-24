---
layout: index
title: The C Conference
rss: /blog.rss
---

## [Tickets][register]

[Buy early bird tickets][register] through the end of May $225. Optionally you
can attend both C Conf and [LinuxCon][linuxcon] or [CloudOpen][cloudopen] for
$520 ($20 more than LinuxCon alone)!

## [Program][pfc]

What would you like to see? What talks do you want to give? Help define C Conf,
participate in the [reverse CFP][pfc]. There will be a single track and talks
will be fast (around 20 minutes), it will be a blast.

## [Travel & Hotel][travel]

Discounted room rates at the [Sheraton Hotel & Marina][travel] in San Diego,
California. And travel details for getting there.

[travel]: /travel.html

## The Essential Details

- **What**: A conference about using the C programming language
- **Where**: [San Diego, CA][travel]; co-located with [LinuxCon][linuxcon]/[CloudOpen][cloudopen]/[LPC][lpc]
- **When**: August 28th, 2012
- **Why**: Because C is used by everyone to solve interesting problems

[linuxcon]: https://events.linuxfoundation.org/events/linuxcon
[cloudopen]: https://events.linuxfoundation.org/events/cloudopen/
[lpc]: http://linuxplumbersconf.org
[register]: http://www.regonline.com/Register/Checkin.aspx?EventID=1096261
[pfc]: /pfc/

## Keep up to date

Get the latest updates. Join the [cconf-announce mailing list][cconf-announce].
Follow [@thecconf][twitter] on Twitter. Watch on [github]. Or add the C
Conference on [Google+][googlep] or [Facebook][facebook].

[cconf-announce]: https://groups.google.com/forum/#!forum/cconf-announce
[github]: https://github.com/cconf/cconf.github.com
[twitter]: https://twitter.com/thecconf
[googlep]: https://plus.google.com/111666632522404882293/posts
[facebook]: http://www.facebook.com/thecconf


## Sponsors

Want to sponsor?  <a href="mailto:contact@cconf.org">Contact me.</a>

## Blog Posts

{% for item in site.posts limit:5 %}
{% include frontpage_blog.html %}
{% endfor %}
