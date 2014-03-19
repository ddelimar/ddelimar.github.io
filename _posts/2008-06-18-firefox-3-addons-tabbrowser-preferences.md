---
layout: post
title: "Firefox 3 addons: Tabbrowser Preferences"
category: web
description: 
keywords: 
---

#{{ page.title }}

<script type="text/javascript"><!--
	google_ad_client = "pub-9634792776388159";
	/* Fx3 Tabbrowser pref art. Link Unit 468x15, 19.06.08 */

	google_ad_slot = "1024121721";

	google_ad_width = 468;

	google_ad_height = 15;
//--></script>
<script type="text/javascript"
src="//pagead2.googlesyndication.com/pagead/show_ads.js"> 
</script>

As with every new version of Firefox you can expect there will be addons that won't be compatible with the new version immediately after the Firefox release.

It's all good until it happens to you, right? ;)

It's all good until this happens with your <em>must-have-or-die</em> Firefox extension, right?

Well, something like that happened to me. More specifically, not only is the addon incompatible with Firefox 3, but the project seems to be d.e.a.d. - and that stinks... :(

So, without further ado, for all the users of <a href="https://addons.mozilla.org/en-US/firefox/addon/158">Tabbrowser Preferences</a>, this isn't Tabbrowser Preferences for Firefox 3, but it's a way to get to almost all of it's features even without it.

All you need to do is open <a href="/goodies/articles/firefox-3-addons-tabbrowser-preferences/user.html">this txt file</a>, modify the values inside to your liking and then save it into your Firefox profile (<a href="http://support.mozilla.com/en-US/kb/Profiles">How to find your profile?</a>) and voila!<br /> All of the settings are now saved in Firefox 3, even without Tabbrowser preferences! (OK, truth is I got a little carried away, since some of the settings were tied to Tabbrowser preferences and you'll see which ones I'm talking about because they are commented in the above txt file)

It's easy to modify the values. Just change the true/false or the integral value where it shows up.

You can help others and share this resource to the world using the self explaining button below.

<br />
<strong>UPDATE, June 20th</strong>:<br />
If you came here without seeing what Lawrence Webb, a.k.a <a href="https://addons.mozilla.org/en-US/firefox/user/1773358">larryvgs</a> on addons.mozilla.org suggested <em>"For those who MUST HAVE their tabs on the bottom"</em>, here's a solution for you:

Put the following in your userChrome.css file (it doesn't exist by default but it should be located in the sub-folder called <em>chrome</em> in your profile folder) or just open <a href="/goodies/articles/firefox-3-addons-tabbrowser-preferences/userChrome.html">this userChrome.css</a> and save it in your chrome folder.

/* Display the Tabbar at the bottom */<br />
#content > tabbox {-moz-box-direction: reverse;}

The orginal instructions are supposedly at <a href="http://support.mozilla.com/tiki-view_forum_thread.php?locale=en-US&amp;comments_parentId=67089&amp;forumId=1">support.mozilla.com</a>.

<br />
<strong>UPDATE, July 2nd</strong>:<br />
There's now a new and still experimental addon <a href="https://addons.mozilla.org/firefox/addon/7955">Tab Focus</a> for all of you who can't live without Tabbrowser Preferences' <em>"Select tabs when the mouse is moved onto them"</em> feature. Thanks <a href="/web/firefox-3-addons-tabbrowser-preferences/#Comment17">TDM</a> for letting us know!



<!--div id="comments">

	<div class="comment"><p class="date"><p><a href="http://quidsit.com/" title="http://quidsit.com" rel="nofollow">Josh Miller</a>  on <a id="Comment1" name="Comment1" title="Comment 1"></a>June 19, 2008:</p><p>Absolutely awesome! I&#39;ve been looking for a (easy) way to do this for a couple of months now. Thanks much!</p></div>

	<div class="comment"><p class="date"><p>Walter Grayson on <a id="Comment2" name="Comment2" title="Comment 2"></a>June 20, 2008:</p><p>You had me going...right up until this:<br />
	Select tabs when the mouse is moved onto them // Tabbrowser pref only<br />
	<br />
	I *need* that Tabbrowser functionality so much! If only it worked in FF3!</p></div>

	<div class="comment"><p class="date"><p><a href="http://www.tvismypacifier.com/" title="http://www.tvismypacifier.com" rel="nofollow">Jenny</a>  on <a id="Comment3" name="Comment3" title="Comment 3"></a>June 21, 2008:</p><p>I upgraded to Firefox 3 yesterday. Previously, I was able to enlarge the text (using ctrl +) on a single tab.  The text size would stay the same on that tab until I manually changed it or closed the tab, even if I went to different pages on that tab. I was using TabBrowser Preferences and I believe that must have been how I was able to do this, as TBP doesn&#39;t work with FF3 and that text thing quit working when I updated.<br />
	<br />
	Since the install, I tried without an extension and now with a select extension I found, and I&#39;m able to either permanently change the starting zoom level or zoom in temporarily but if I go to a new page in that tab, it resets. For example, in my gmail, when I use it on my 2nd monitor, I need the text bigger when I am working. So I make that tab zoomed in a bit. But every time I click on a new email, it goes back to the original 100%, not zoomed in. <br />
	<br />
	Not sure if your workaround would fix my issue or not.  I looked at it but I just got thouroughly confused.  ;)  Any chance you understand what I am talking about and know how to help?  *laugh*<br />
	<br />
	TIA!</p></div>

	<div class="comment"><p class="date"><p><a href="http://domdelimar.com/" title="http://domdelimar.com/" rel="nofollow">Dom</a>  on <a id="Comment4" name="Comment4" title="Comment 4"></a>June 22, 2008:</p><p>Hi Jenny,<br />
	<br />
	The zoom behavior you describe wasn&#39;t due to Tabbrowser Preferences but default Firefox 2 behavior.<br />
	<br />
	And I know that the default behavior of Firefox 3 is to keep the zoom level for a given domain even after you close the tab/Firefox (and I have to say among one of my favorite features!).<br />
	<br />
	You might want to try disabling the extension you installed (or all of them, which can easily be done by starting Firefox in safe mode) to see if one of the extensions is to blame. In safe mode, you should expect the Firefox default zoom behavior.</p></div>

	<div class="comment"><p class="date"><p><a href="http://www.tvismypacifier.com/" title="http://www.tvismypacifier.com" rel="nofollow">Jenny</a>  on <a id="Comment5" name="Comment5" title="Comment 5"></a>June 22, 2008:</p><p>Hmm, darnit.  I don&#39;t want the zoom level saved for a domain.  heh  Just simply for a select tab until the tab is closed or zoom level altered for it.  Ah well!  Thanks!  :)</p></div>

	<div class="comment"><p class="date"><p><a href="http://domdelimar.com/" title="http://domdelimar.com/" rel="nofollow">Dom</a>  on <a id="Comment6" name="Comment6" title="Comment 6"></a>June 22, 2008:</p><p>There&#39;s a cure for that after all... in your user.js file, add the following line:<br />
	<br />
	user_pref("browser.zoom.siteSpecific", false);<br />
	<br />
	And after that, restart Firefox and now the zoom level should be applied on the current tab only, according to <a href="http://kb.mozillazine.org/About:config_entries">MozillaZine Knowledge base</a>.</p></div>

	<div class="comment"><p class="date"><p><a href="http://www.bennink.info/" title="http://www.bennink.info" rel="nofollow">Corien</a>  on <a id="Comment7" name="Comment7" title="Comment 7"></a>June 22, 2008:</p><p>Is there a way to set it so that when you mouse-over a tab, it gets activated?<br />
	That&#39;s the option I miss most at the moment, but it looks to be grayed out in the script file.<br />
	(this page bookmarked, will check for answers :) )</p></div>

	<div class="comment"><p class="date"><p><a href="http://domdelimar.com/" title="http://domdelimar.com/" rel="nofollow">Dom</a>  on <a id="Comment8" name="Comment8" title="Comment 8"></a>June 22, 2008:</p><p>@Corien: And I bet it was a delight to bookmark it so easily with new Firefox :)<br />
	<br />
	Unfortunately, I don&#39;t know how Tabbrowser Preferences accomplished that mouse-over-a-tab feature...<br />
	<br />
	But when I find the answer, I&#39;ll post it here.</p></div>

	<div class="comment"><p class="date"><p>Nik on <a id="Comment9" name="Comment9" title="Comment 9"></a>June 23, 2008:</p><p>I am having difficulty getting your Tabbrowser solution to work.<br />
	<br />
	Ihave copied the text file to my profile folder and made changes i require, but it does&#39;nt have any affect on how firefox 3 handles Tabs.<br />
	<br />
	I really only need the "overwrite open tabs feature" from tabbrowser preferences.<br />
	<br />
	Can I set this up in about:config directly<br />
	<br />
	<br />
	Thanks</p></div>

	<div class="comment"><p class="date"><p><a href="http://domdelimar.com/" title="http://domdelimar.com/" rel="nofollow">Dom</a>  on <a id="Comment10" name="Comment10" title="Comment 10"></a>June 23, 2008:</p><p>Hi Nik,<br />
	<br />
	You should edit that file for features to appear because I have setup the file with only the Firefox default options, nothing will happen if you only copy the file without editing it first.<br />
	<br />
	Sure, you can just change it&#39;s value from about:config window, especially if you only have one feature you want to access.</p></div>

	<div class="comment"><p class="date"><p><a href="http://www.pmoylan.org/" title="http://www.pmoylan.org" rel="nofollow">Peter Moylan</a>  on <a id="Comment11" name="Comment11" title="Comment 11"></a>June 24, 2008:</p><p>This is a good solution, but it&#39;s missing the one "absolute must-have" feature that I needed Tabbrowser Preferences for: open all popups in a new window. (This is broken in version 1.3.1.1 of Tabbrowser Preferences, but it works in version 1.3.0.) Allowing popups to open in a new window is not acceptable for internet banking, because my bank then takes over the whole screen, which I absolutely hate. Allowing them to open in the _existing_ window makes many on-line transactions unworkable, because if you want to print a receipt then you can&#39;t get back to where you were in the transaction. (Pressing the browser&#39;s "back" button can cause your credit card to be charged twice.)<br />
	<br />
	So, is there any way to get this option? I can learn to live without many of the other Tabbrowser Prefs features, but not this one.</p></div>

	<div class="comment"><p class="date"><p>Jack on <a id="Comment12" name="Comment12" title="Comment 12"></a>June 25, 2008:</p><p>The main thing I miss is having URL&#39;s in the Address Bar open in a New Tab. Any way to achieve this without Tabbrowser Preferences?</p></div>

	<div class="comment"><p class="date"><p>Jan on <a id="Comment13" name="Comment13" title="Comment 13"></a>June 27, 2008:</p><p>Tab Mix Plus is an extension that includes the "Tabbrowser Preferences" and the "Tab Clicking Options" in one.<br />
	It is available for Firefox 3.0<br />
	<br />
	http://tmp.garyr.net/forum/viewtopic.php?t=7031</p></div>

	<div class="comment"><p class="date"><p><a href="http://www.tvismypacifier.com/" title="http://www.tvismypacifier.com" rel="nofollow">Jenny</a>  on <a id="Comment14" name="Comment14" title="Comment 14"></a>June 27, 2008:</p><p>I love how people are constantly spamming Tab Mix Plus in everything I read.  lol<br />
	<br />
	Anyway, thanks for the update about the zoom!  I uninstalled the NoSquint add-on and changed that preference and it works great!  YAY!<br />
	<br />
	Thanks so much!  :)</p></div>

	<div class="comment"><p class="date"><p><a href="http://www.chadegeland.com/" title="http://www.chadegeland.com" rel="nofollow">Chad</a>  on <a id="Comment15" name="Comment15" title="Comment 15"></a>June 27, 2008:</p><p>Thanks for the write up. Now all that is needed is an update to the Noia 2 eXtreme theme and my Firefox 3 will be complete.</p></div>

	<div class="comment"><p class="date"><p>Lou on <a id="Comment16" name="Comment16" title="Comment 16"></a>July 01, 2008:</p><p>I have a different issue, which caused me to downgrade to Firefox 2.  For accessibility reasons, I need high contrast white characters on a black background.  I&#39;m operating from OSX 10.5.4, which does not offer this as a built-in feature, as does Windows.  I installed Firefox 3, and as in previous versions, changed the style sheet colors so as to effect my required high contrast style.  However, the basic style sheet nevertheless evidently leaves search boxes white with black characters.  This is hard for me to see, but I can live with it.  What I cannot deal with is that on many web sites (e.g. Amazon), search boxes have a black background with black characters.  This is also true for many on-line banking / ordering sites.  Black on black is unusable.  (I have a similar problem with Firefox 2 on a much smaller number of sites.)  I hunted around for options, and tried all of those I could find that were suggested, but as far as I can tell, nothing overrides the built-in style sheet.  This makes Firefox 3 unusable for me, so I downgraded.  I hope this problem will be fixed eventually, but truthfully, I will have no way of knowing if it is.  Therefore, I am hoping Mozilla will continue to support Firefox 2.  Otherwise, I will have to change browsers.</p></div>

	<div class="comment"><p class="date"><p>TDM on <a id="Comment17" name="Comment17" title="Comment 17"></a>July 02, 2008:</p><p>For those wanting to "Select tabs when the mouse is moved onto them" from Tabbrowser Preferences there&#39;s a new "Tab Focus" extension:- https://addons.mozilla.org/firefox/addon/7955</p></div>

	<div class="comment"><p class="date"><p>Corien on <a id="Comment18" name="Comment18" title="Comment 18"></a>July 04, 2008:</p><p>TabFocus installed, thanks heaps for the info!</p></div>

	<div class="comment"><p class="date"><p>S3NTYN3L on <a id="Comment19" name="Comment19" title="Comment 19"></a>July 05, 2008:</p><p><em>Jan on June 27, 2008:<br />
	<br />
	Tab Mix Plus is an extension that includes the "Tabbrowser Preferences" and the "Tab Clicking Options" in one.<br />
	It is available for Firefox 3.0<br />
	<br />
	http://tmp.garyr.net/forum/viewtopic.php?t=7031<br />
	</em>
	<br />
	<br />
	This IS the answer!<br />
	It&#39;s got everything Tabbrowser Prefs and Tab Clicking Options had and then some!</p></div>

	<div class="comment"><p class="date"><p>zmartha on <a id="Comment20" name="Comment20" title="Comment 20"></a>August 27, 2008:</p><p>I would like to put your save text file in my profile, but need help on a couple of questions.<br />
	<br />
	What do I name the text file when I save it in profiles?<br />
	<br />
	How do I change something in it to my preferences?  For instance you have:<br />
	<br />
	Load Web browser links into a (new window=2, new tab=3, current tab=1)<br />
	user_pref("browser.link.open_newwindow", 3);<br />
	<br />
	If I want it to open in a new window, do I just leave it like it is, but type in a 2 where the last 3 is??<br />
	<br />
	AND another one you have says:      Force all left-clicked links to open in new tabs: // Tabbrowser pref only<br />
	  <br />
	How do I change it to NOT do that?<br />
	Thanks for your help.</p></div>

	<div class="comment"><p class="date"><p><a href="http://domdelimar.com/" title="http://domdelimar.com/" rel="nofollow">Dom</a>  on <a id="Comment21" name="Comment21" title="Comment 21"></a>August 28, 2008:</p><p>Dear zmartha,<br />
	<br />
	You just name it user.js, like I&#39;ve named it. If you already have a user.js file in your profile folder, then feel free to edit it just by adding the contents of the file provided by me.<br />
	<br />
	If you want links to open in new windows, you&#39;re right on track by typing in a "2" where that last "3" is, like this: <br />
	user_pref("browser.link.open_newwindow", 2);<br />
	<br />
	The same logic applies to other settings.<br />
	<br />
	Unfortunately, wherever you see my note "// Tabbrowser pref only" it means this feature is actually missing. It was only available in Tabbrowser Preferences addon although some of them could be available in other Firefox addons. I just left the notes about these features so people would be able to see which one these are.<br />
	<br />
	So in your case, if you don&#39;t want to force all left-clicked links to open in new tab, don&#39;t worry, this feature isn&#39;t there.</p></div>

	<div class="comment"><p class="date"><p>Evlampya on <a id="Comment22" name="Comment22" title="Comment 22"></a>September 17, 2008:</p><p>Home Button<br />
	//  Open the home page in a (current tab=0, new tab=1, new tab, unfocused=2) // Tabbrowser pref only<br />
	<br />
	If I understand it right, I won&#39;t be able to set homepage opened in new tab instead of blank page :(</p></div>

	<div class="comment"><p class="date"><p><a href="http://domdelimar.com/" title="http://domdelimar.com/" rel="nofollow">Dom</a>  on <a id="Comment23" name="Comment23" title="Comment 23"></a>September 17, 2008:</p><p>Evlampya,<br />
	<br />
	You can do that, just not with this user.js file. <br />
	<br />
	There&#39;s an addon called <a href="https://addons.mozilla.org/en-US/firefox/addon/2221">NewTabURL</a> that does exactly what you want. ;)</p></div>

	<div class="comment"><p class="date"><p>Evlampya on <a id="Comment24" name="Comment24" title="Comment 24"></a>May 13, 2009:</p><p>Hey Dom, I found a link to this place occasionally, I want to say I suffered  the whole my life that I was familiar with Mozilla Tabbed Browsing. Because: first I wasn&#39;t able to load a homepage in new tab with Mozilla preferences, as previous comment says, then I downloaded New Tab Homepage Add-on, but it made me suffer a lot, too - coz it&#39;s don&#39;t showed up tab bar when I had only one tab opened. That sux. Today I downldd and istlld Tab Mix Plus and it does both and is great! I really don&#39;t need to dive in that .js and other hard understandable things!<br />
	Cool I must say! Everything works fine now! Are you happy for me? :)</p></div>

	<div class="comment"><p class="date"><p><a href="http://domdelimar.com/" title="http://domdelimar.com" rel="nofollow">Dom</a>  on <a id="Comment25" name="Comment25" title="Comment 25"></a>June 04, 2009:</p><p>Evlampya, I really am glad that you found what works for you at the end.<br />
	<br />
	The problems you describe shouldn&#39;t be that hard to solve still you, from millions of other users of Firefox, suffered from them.<br />
	<br />
	P.S. Sorry it took so long to reply...</p></div>
</div-->

<!--div style="padding:1em;vertical-align:middle;">
<script type="text/javascript"><!--
 google_ad_client = "pub-9634792776388159";
google_alternate_color = "FFFFFF";

google_ad_width = 160;

google_ad_height = 90;

google_ad_format = "160x90_0ads_al_s";

//2007-07-23: ExtraMiddleRightHomepage

google_ad_channel = "0795798680";

google_color_border = "FFFFFF";

google_color_bg = "FFFFFF";

google_color_link = "467AA7";

google_color_text = "000000";

google_color_url = "467AA7";
//--></script>
 <script type="text/javascript"
 src="../../../../pagead2.googlesyndication.com/pagead/show_ads.js"> 
 </script>
</div-->


<script src="../../../../www.google-analytics.com/urchin.js" type="text/javascript">
 </script><noscript></noscript>
 <script type="text/javascript">
 _uacct = "UA-299737-2";
 urchinTracker();
 </script><noscript></noscript>
