GeekML
======

Geek Markup Language 0.1


The purpose of Geek Markup Language (GeekML, or GML) is to be a Geek Code[1] for the Web 2.0 era. By way of background, Geek Code was invented in the pre-web Internet era as a way for geeks (or nerds, or what have you) to briefly 
describe themselves in a block of barely comprehensible gobeltygook that resembed a PGP public key or public signature. This started as a lark, but became an early Internet phenomenon. Geeks would attach Geek Code Blocks to their emails, append them to .plan files, and so on. 

Unfortunately Geek Code suffers from some flaws. Geeky cultulral phenomena are hard-coded into Geek Code, which makes Geek Code blocks stale as old phenomena end and new phenomena emerge. This is particularly unfortunate since Geek Code, as of this writing (April 2014), hasn't been updated since 1996[2]. 

Geek Markup Language is intended as an update of the Geek Code concept that avoids Geek Code's major shortcoming. GeekML is extensible. Initially it exists as a JSON schema[3], with an XML schema to follow. Instead of hard-coding phenomena, GeekML describes broad categories of phenomena and allows the geek to describe themselves according to their participation and level of participation in each phenomenon. Eventually I hope this will follow in Geek Code's proud tradition.

**Features of GeekML**

Geeks are described in several terms:

*Name* -- This is intended to be flexible enough that the geek can use any naming convention. This is really the only mandatory field.

*Summary* -- This is where the geek describes themself.

*ContactData* -- This describes how someone can reach the geek, whether by email, phone, telegraph, IM, or whatever means should arise in the future.

*Media* -- Basically, this is how one can hear or read what the geek has to say, such as through blogs, print media, Twitter, FaceBook, and so on.

*Skills* -- This is where the geek describes their skills, and their proficiency (or, in the spirit of Geek Code, lack thereof.) 

*Organizations* -- This is where the geek describes what organizations they belong to, and their level of involvement (or, in the spirit of Geek Code, their level of aversion).

*Games* -- Geeks love games! This is where the geek decribes the games they particularly like (or loathe) and their level of love or skill (or lack thereof).

*Fandoms* -- Geeks love entertainment! This is where the geek describes the shows, comics, podcasts, etc. they particularly like (or loathe) and their level of love (or hate).

**Why include hate and antipathy?**

The original Geek Code allowed the geek to describe their antipathy towards certain geeky phenomena with minuses. A typical example would be **L--** for someone who really hates Linux (or **L---** for "I am Bill Gates"). I decided that it's important to retain this feature in GeekML. It isn't fashionable these days to express antipathy so openly, but it's also my opinion that geekdom shouldn't be about what's fashionable.

**References:**
[1] http://www.geekcode.com/
[2] http://www.geekcode.com/geek.html
[3] http://json-schema.org/documentation.html

Copyright
=========
Copyright (c) 2014 Michael C Smith <maxomai@gmail.com>. Released under MIT license. See LICENSE for details.

History
=======
2014-04-06 0.1 draft of the JSON schema
