---
layout: post
title: "dont get mad | you have been hacked"
category: snews
description: 
keywords: 
---

#{{ page.title }}

<blockquote>dont get mad | you have been hacked | your security=0 y3v.h4x</blockquote> was the message I found today after deleting a pornographic banner from the header of my site (sorry for that) and another fishy php file I found on my server.

How can I not get mad? When I see a pornographic banner on top of my site. I AM mad. I am VERY mad but I'm going to focus my energy into getting even a more secure system, learning about and promoting security to others.<br />
But here is the thing, I've already been quite security aware and my home system is quite secure, if I may say so - definitely more secure than most of them out there. But it seems it wasn't my system that was breached into - it was a <a href="http://www.solucija.com/forum/viewtopic.php?id=2976" onclick="javascript:urchinTracker('/outgoing/solucija_com_forum');">vulnerability in the CMS</a> I use, sNews.

I'm thankful to Luka and Mika, main developers of sNews CMS for supplying us all with a patch in less than 24 hours and everybody else who helped solving this. Bravo!

<!--div style="float:right; margin-left:17px; margin-down:30px; margin-up:5px;"><script type="text/javascript"><!--
 google_ad_client = "pub-963479277638815"9;
google_ad_width = 336;

google_ad_height = 280;

google_ad_format = "336x280_as";

google_ad_type = "image";

//2007-01-30: HackMiddlerightLRectangleImg

google_ad_channel = "7005429262";
//--></script-->
 <!--script type="text/javascript"
 src="../../../../pagead2.googlesyndication.com/pagead/show_ads.js"> 
 </script></div-->

I was actually among the fortunate ones as my site didn't go down like it did to a friend of mine <a href="http://p-ahlqvist.com/" onclick="javascript:urchinTracker('/outgoing/p-ahlqvist_com');">Patric</a> <!-- this page no longer exists - contact Patric <a href="http://p-ahlqvist.com/home/defacement-on-pahlqvistcom/">Patric</a> --> for whom I feel very sorry. And everybody else who got somebody crack into their site - that's right, my site wasn't hacked into - as hacking is not all about breaking into other people's sites and posting inadequate content or doing any other harm. These are crackers who just know how to click "OK" and execute some exploit somebody else made. Ha! Hackers - you wish!

The first thing you should do now, after applying the patch from <a href="http://www.solucija.com/forum/viewtopic.php?id=2976" onclick="javascript:urchinTracker('/outgoing/solucija_com_forum');">sNews forum</a>, and which I recommend to everybody using the sNews CMS is to remove that little notion that says your site was barbecued by this CMS. It's the most obvious one and it won't solve your problem but that's probably the easiest way these crackers can find most of the sNews sites. Everything indicates that these crackers have used that to find sNews sites in this particular case: my logs say that the person who did this came from Google searching for this phrase and the exploit to which <a href="http://www.solucija.com/forum/viewtopic.php?pid=21036#p21036" onclick="javascript:urchinTracker('/outgoing/solucija_com_forum');">Luka at sNews Forum indicates</a> looks like it's made to search for just that. I'll soon put a little picture there instead.

As far as I know for now, the cracker left one suspicious php file that my hosting says could be some kind of a shell script used to manipulate with my files but nothing like that happened because my server has phpsuexec option in PHP turned on, whatever that means.

Now I've got some questions that are bothering me:
<ul><li>How did the cracker exactly gain control over my site?</li>
<li>What exactly did the cracker gain control over? If it was just over my CMS, how did the cracker change my index.php file then?</li></ul>

<!--div id="comments">
    <div class="comment"><p class="date"><p><a href="http://www.frdk.com/" title="http://www.frdk.com" rel="nofollow">Fred K</a>  on <a id="Comment1" name="Comment1" title="Comment 1"></a>January 15, 2007:</p><p>Dom,<br />
    I had the same problem and I agree with your point of view. These crackheads are fishing for attention, like any 5-year old and unfortunately they&#39;re getting what they want from us... But how can we <em>not</em> get mad? If they really wanted to alert us of a potential security flaw in sNews, gosh, all they had to do was post a comment on our sites to that effect or, even better, send us an email. Did they? Nah, they egged us instead. And then <em>ask us not to get pissed off</em>. Which is typical 5-year old behaviour.<br />
    <br />
    Sorry you got cracked, man.<br />
    /agentS</p></div>

    <div class="comment"><p class="date"><p>albert on <a id="Comment2" name="Comment2" title="Comment 2"></a>January 15, 2007:</p><p>Hi Dom<br />
    <br />
    Sorry to hear that your site had been cracked.<br />
    Gald the luka a Mika are on the ball with getting the fix done asap.<br />
    <br />
    if you want to find out more you can go here:<br />
    http://www.securityfocus.com/bid/22025/info</p></div>

    <div class="comment"><p class="date"><p><a href="http://p-ahlqvist.com/" title="http://p-ahlqvist.com" rel="nofollow">Patric</a>  on <a id="Comment3" name="Comment3" title="Comment 3"></a>January 31, 2007:</p><p>Hey, mate...<br />
    <br />
    ;) .. Well, no need to comment really. They&#39;re asses, period.<br />
    Was just curious as to weather you did upload a favicon... Hehe... You mentioned that on my site a few days back...<br />
    <br />
    Btw, I&#39;m gonna steal this font for my new layout/design. It rocks.<br />
    <br />
    Have a good one, Dom.</p></div>

    <div class="comment"><p class="date"><p><a href="http://domdelimar.com/" title="http://domdelimar.com/" rel="nofollow">Dom</a>  on <a id="Comment4" name="Comment4" title="Comment 4"></a>February 02, 2007:</p><p><p>Hi Patric!<br />
    <br />
    Ditto! (about these crackers)</p>

    <p>Regarding the favicon - didn&#39;t have time to do it this week - I&#39;m really inexperienced with graphics and these complex digital graphic applications so we&#39;ll see what I will make out of my first try... hopefully I&#39;ll get to do it next week. <br />
    You watch and see - I&#39;ve been thinking and I&#39;ve got an idea how it&#39;s supposed to look...</p>

    <p>And yes, please use this font - I already saw a font like this one (or maybe the same one) emerging on some headings on your new layout design ("New Articles", "New Comments" etc.) the other day and was about to comment how I&#39;m definitely gonna like your new template if you use this font... ;) <br />
    I&#39;m really bored seeing most of the websites having the same Verdana (or Verdana like) font...</p></p></div>

    <div class="comment"><p class="date"><p>Mani on <a id="Comment5" name="Comment5" title="Comment 5"></a>March 12, 2007:</p><p>they just search 777 premison file and i think it was config.php and they put code into it thats it</p></div>

    <div class="comment"><p class="date"><p><a href="http://www.cssanarchy.com/" title="http://www.cssanarchy.com" rel="nofollow">sasha</a>  on <a id="Comment6" name="Comment6" title="Comment 6"></a>April 01, 2007:</p><p>great site man....odlican :)</p></div>

    <div class="comment"><p class="date"><p><a href="http://domdelimar.com/" title="http://domdelimar.com/" rel="nofollow">Dom</a>  on <a id="Comment7" name="Comment7" title="Comment 7"></a>April 02, 2007:</p><p>Thanks sasha!<br />
    <br />
    Now that wasn&#39;t April Fools&#39; Day joke, was it?</p></div>

    <div class="comment"><p class="date"><p>sasha on <a id="Comment8" name="Comment8" title="Comment 8"></a>April 02, 2007:</p><p>nop...site looks good..fast load ,good chosing colors and nice news story.i liked your site ..this is not joke.... </p></div>

    <div class="comment"><p class="date"><p>y3v.h4x on <a id="Comment9" name="Comment9" title="Comment 9"></a>June 11, 2007:</p><p>sowwy dude<br />
    that porno banner.. wasnt added there by me<br />
    i dont deface index i just added that shell<br />
    you have to turn your safe mode on<br />
    or was it that i did i bypass.. whatever<br />
    no harm done.. i just used your bandwidth for a bit<br />
    no hard feelings eh? :x</p></div>

    <div class="comment"><p class="date"><p><a href="http://domdelimar.com/" title="http://domdelimar.com/" rel="nofollow">Dom</a>  on <a id="Comment10" name="Comment10" title="Comment 10"></a>June 16, 2007:</p><p>We obviously have different views on the world an that&#39;s OK, although what you did is nowhere near OK in my world...<br />
    <br />
    > no hard feelings eh? :x<br />
    Well, just as I have said - I won&#39;t waste my energy on hatred but rather on constructive things. But I won&#39;t forget.</p></div>
</div-->