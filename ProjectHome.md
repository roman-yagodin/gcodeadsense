<table width='100%'>  <tr>    <td width='90%' align='left' valign='top'>
<h1>gCodeAdSense <a href='http://kontactr.com/user/frankglaser'><img src='http://kontactr.com/pics/small.gif' /></a></h1>
<blockquote>AdSense Gadget for Your Google Code Project.</blockquote>

<wiki:gadget url="https://gcodeadsense.googlecode.com/svn/release/gCodeAdSense/gCodeAdSense.xml" width="468" height="60" border="0" up_ad_client="3727478741117936" up_ad_slot="9350988841" up_ad_width="468" up_ad_height="60" up_ad_project=document.URL /><br>
<br>
<h2>News</h2>
<ul><li>Released Version 1.40<br>
<ul><li>Removed Analytics tracking (<a href='http://www.theeucookielaw.com/'>The EU Cookie Law</a>)<br>
</li></ul></li><li>Released Version 1.30<br>
<ul><li>Load javascript files via https to avoid mixed content<br>
</li></ul></li><li>Released Version 1.20<br>
<ul><li>Added optional project URL parameter<br>
</li></ul></li><li>Released Version 1.10<br>
<ul><li>Additional AdSense width and height parameter are now optional</li></ul></li></ul>

<table border='0'>
<blockquote><tr>
<blockquote><td>
<blockquote>
</blockquote></td>
<td></blockquote></blockquote>

<blockquote></td>
<td>
<blockquote><a href='http://www.facebook.com/sharer.php?u=http://code.google.com/p/gcodeadsense/&t=gCodeAdsense'><img src='http://kpenhancedlistview.googlecode.com/svn/wiki/Facebook.png' /></a>
</blockquote></td>
<td align='center' valign='middle'>
<blockquote><wiki:gadget border="0" url="http://stefansundin.com/stuff/flattr/google-project-hosting.xml" width="110" height="20" up_uid="frankglaser" up_title="gCodeAdSense" up_url="http://code.google.com/p/gcodeadsense/" /><br>
</blockquote></td>
<td align='center' valign='middle'>
<blockquote><a href='https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=CH7PBX4C8WZAE&item_name=gCodeAdSense&cancel_return=https://code.google.com/p/gcodeadsense&return=https://code.google.com/p/gcodeadsense'><img src='https://www.paypal.com/en_US/i/btn/btn_donate_LG.gif' /></a>
</blockquote></td>
<td align='center' valign='middle'>
<blockquote><a href='Hidden comment: 
<wiki:gadget url="http://www.ohloh.net/p/584064/widgets/project_thin_badge.xml" height="36" width="120px" border="0"/>
'></a><br>
</blockquote></td>
</blockquote><blockquote></tr>
</table></blockquote>

<h2>Motivation</h2>
<blockquote>The problem is You can not use AdSense directly from the project start page (<a href='https://code.google.com/p/support/issues/detail?id=135'>Google Code Feature Request</a>)<br>
After I have implemented and copied the widget to several projects, I thought it might be better to host it in a seperate project, where it can be maintained.</blockquote>

<h2>Description</h2>
<blockquote>It is a configurable gadget, which You can use directly. Only with a single line of code can it be added to Your Google Code project start or wiki page.</blockquote>

It is based on following ideas:<br>
<ul><li><a href='http://geoland.org/2007/01/adsense-in-iframe/'>http://geoland.org/2007/01/adsense-in-iframe/</a>
</li><li><a href='http://code.google.com/p/support/issues/detail?id=135'>http://code.google.com/p/support/issues/detail?id=135</a></li></ul>

<h2>What You need</h2>
<ul><li>Create a new <a href='http://www.google.com/adsense/support/bin/answer.py?hl=en&answer=72583'>AdSense unit</a>.<br>
</li><li>You can get all information from Your AdSense Code.<br>
<table><thead><th> <b>What</b> </th><th> <b>Parameter</b> </th><th> <b>Required</b> </th><th> <b>AdSense Code</b> </th></thead><tbody>
<tr><td> Widget Width </td><td> width="123" </td><td> yes </td><td>  </td></tr>
<tr><td> Widget Height </td><td> height="456" </td><td> yes </td><td>  </td></tr>
<tr><td> Border </td><td> border="0" </td><td> no </td><td>  </td></tr>
<tr><td> Publisher-ID </td><td> up_ad_client="CCC" </td><td> yes </td><td> google_ad_client = "ca-pub-CCC" </td></tr>
<tr><td> Content-ID </td><td> up_ad_slot="SSS" </td><td> yes </td><td> google_ad_slot   = "SSS" </td></tr>
<tr><td> Ad width </td><td> up_ad_width="WWW" </td><td> no </td><td> google_ad_width  = WWW </td></tr>
<tr><td> Ad height </td><td> up_ad_height="HHH" </td><td> no </td><td> google_ad_height = HHH </td></tr>
<tr><td> Ad project</td><td> up_ad_project="url" </td><td> no </td><td>  </td></tr>
<tr><td> Ad keywords </td><td> up_ad_keywords="Word1 Word2" </td><td> no </td><td>  </td></tr></li></ul></tbody></table>

For the url parameter You can just use, one of these variables:<br>
<ul><li>document.URL<br>
</li><li>top.location.href<br>
</li><li>window.location.href</li></ul>

<h2>Howto use</h2>
Just place this code on Your Google code project start or wiki page.<br>
<ul><li>Short URL Basic variant:<br>
<pre><code>&lt;wiki:gadget url="https://goo.gl/Uql18" width="123" height="456" up_ad_client="CCC" up_ad_slot="SSS" /&gt;<br>
</code></pre>
</li><li>Basic variant:<br>
<pre><code>&lt;wiki:gadget url="https://gcodeadsense.googlecode.com/svn/release/gCodeAdSense/gCodeAdSense.xml" width="123" height="456" up_ad_client="CCC" up_ad_slot="SSS" /&gt;<br>
</code></pre>
</li><li>Enhanced variant:<br>
<pre><code>&lt;wiki:gadget url="https://gcodeadsense.googlecode.com/svn/release/gCodeAdSense/gCodeAdSense.xml" width="123" height="456" border="0" up_ad_client="CCC" up_ad_slot="SSS" up_ad_width="WWW" up_ad_height="HHH" up_ad_project="url" /&gt;<br>
</code></pre></li></ul>

<h2>Take a look on the <a href='Examples.md'>Examples</a> wiki page for layout ideas (<a href='http://code.google.com/p/gcodeadsense/source/browse/wiki/Examples.wiki'>source code</a>).</h2>

<h2>Disclaimer</h2>
Using this gadget may or may not be completely acceptable with regard to <a href='https://www.google.com/adsense/localized-terms'>Adsense TOS</a>.<br>
I've been using this method for months, have been paid for ads served this way, and I haven't yet received any warning from Google.<br>
<br>
<a href='Hidden comment: 
<wiki:gadget url="http://www.ohloh.net/p/584064/widgets/project_factoids.xml" border="0" width="400" height="200"/>
'></a><br>
<br>
<br>
</td>
<blockquote><td valign='top'>
<blockquote><wiki:gadget url="https://gcodeadsense.googlecode.com/svn/release/gCodeAdSense/gCodeAdSense.xml" width="160" height="600" border="0" up_ad_client="3727478741117936" up_ad_slot="7507193440" up_ad_width="160" up_ad_height="600" up_ad_project=document.URL /><br>
</blockquote></td>
</blockquote><blockquote></tr>
</table>