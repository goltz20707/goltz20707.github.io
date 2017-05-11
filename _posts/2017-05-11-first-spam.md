---
layout: post
title: The real first "spam"
excerpt: The real "first spam message".
date: 2017-05-11 15:12:40 -0400
---

I see a lot of posts lately about the supposed 40th birthday of
"spam", unsolicited commercial email (see [this piece in the San Jose
Mercury News](http://www.mercurynews.com/2017/05/03/happy-birthday-spam-not-so-many-happy-returns/), 
for example).  While it is technically correct that the first
unsolicited commercial email was sent on May 1, 1978, in my mind that
was not the first "spam".

The *real* first "spam", the message that gave "spam" its name, was
sent in April 1994, and it was via Usenet News, not email.

[Usenet](https://en.wikipedia.org/wiki/Usenet) was a loose collection
of discussion groups of various topics, such as "rec.games.pinball"
for pinball enthusiasts, or "soc.culture.bulgaria" (hopefully
self-explanatory).  Messages could be posted to more than one group,
but through some behind-the-scenes magic, only one copy of the message
needed to be stored, and a sufficiently intelligent news-reading
program would only show you a given message once.

If a post was inappropriate, or you wanted to "recall" it, you could
"cancel" the post.  This basically flagged the unique message ID that
every post had so that all news servers everywhere would remove it
from their storage.  If a server hadn't even seen the post in question
yet, it would "remember" the message ID, and simply discard that post
when it finally came in.

Enter [Lawrence Canter and Martha Siegel](https://en.wikipedia.org/wiki/Laurence_Canter_and_Martha_Siegel),
two lawyers based on Phoenix, AZ, US.  Among other services, they
offered to guide clients through the process of obtaining work permits
("green cards") via a national lottery.  (I'm unfamiliar with the
details of this whole process.)  They hired a programmer to write some
code that would post a
message advertising their services on hundreds of Usenet groups,
virtually none of which had anything to do with immigration, lawyers,
or work permits.

Here's where it went from "unsolicited" to true "spam", however.  They
posted in such a way that the news software considered each message in
each group as a separate entity.  You'd encounter the "GREEN CARD
LOTTERY" message in one group and flag it to be ignored, only to
encounter it again in the next group you visited...and the next, and
the next, and the next, and so on.

Worse still for news server administrators, each separate message was
stored as a separate file on the hard drive, instead of one copy
shared across all groups.  And this was in the days when a 20 negabyte
(not gigabyte, megabyte) hard drive was considered more than enough
for home use.

And even worse, the normal methods of "canceling" a news post wouldn't
work, because they relied on there being only one copy of a given
message (with one unique message ID) no matter how many groups it was
in.  The "Green Card spam" was, in essence, hundreds of unique
messages, all saying the exact same thing and each showing up in one
and only one group.  (This led to the creation of the very first
"cancelbot", a program designed to seek out and erase the Green Card
spam messages -- a program designed to fight another program.)

Monty Python fans were everywhere on the Internet back then, and the
way the Green Card spam kept popping up reminded someone of the "Spam"
sketch, where a bunch of Vikings are singing, "Spam, spam, spam, spam,
..." endlessly.  (It makes more sense, and is much funnier, in
context.)

So, yeah.  *That's* why it's called spam, and *that* was the real
first spam.

Click [here](https://goltz20707.mmert.org/) to go back to the home page.

