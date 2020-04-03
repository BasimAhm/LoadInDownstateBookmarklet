# Load In Downstate Proxy Bookmarklet

[Download Panopto]("javascript:(function(){if(prompt('Hit Ctrl/Cmd-C to copy name to clipboard', document.title.replace(/[:\\/]/g, '-')+'.mp4')!=null){location.href=$('meta[name="twitter:player:stream"]').attr('content');}})();")


<html lang="en">
<head>
<meta charset="UTF-8">
</head>

<body id="find">

<hr>

<h2>Proxy Server Bookmarklet</h2>

<p>Shoutout to UB for using the same proxy service and giving me the idea to do this, and the below explaination of how to use it: </p>

<p>The proxy bookmarklet lets you reload a web page through the Libraries EZproxy server. If the page you are visiting is one that the library has a subscription to, and you're presently off-campus, you will get immediate access to the resource once you've logged in with your NetID and password.</p>

<p>Tested and works with: UpToDate, Bates Visual Guide, BMJ Best Practice (if an article is already opened)</p>

<p><b>Issues with Net Anatomy:</b> Will load in the proxy but you’ll still be on the no subscription page. Probably easier to just bookmark the Downstate link to Net Anatomy, but you can theoretically use this and then just delete the “/nosubscription/notvalidip.htm” off the URL to access the main page.</p>

<h3>How Do You Add It?</h3>

<p>There's a different method for each of the three main browsers:</p>

<ul>
<li>In <strong>Safari</strong> and <strong>Google Chrome</strong><br> Drag this link to your bookmarks toolbar:<br> <a href="javascript:void(location.href=%22http://newproxy.downstate.edu/login?url=%22+location.href)">Reload in Downstate Library Proxy Server</a></li>

<li>In <strong>Firefox</strong><br> Right-click on the following link, then select the "Bookmark This Link" option:<br> <a href="javascript:void(location.href=%22http://newproxy.downstate.edu/login?url=%22+location.href)">Reload in Downstate Library Proxy Server</a></li>

<li>In <strong>Internet Explorer</strong><br> Right-click on this link<br> <a href="javascript:void(location.href=%22http://newproxy.downstate.edu/login?url=%22+location.href)">Reload in Downstate Library Proxy Server</a><br> then select the "Add to Favorites..." option. You may be warned that you are adding a link which may be unsafe. While some links like this may be unsafe, we believe this one is safe. You can click whichever option is required to continue.</li>

</ul>


<hr>


<h3>How Do You Use It?</h3>

<p>Once you've added this bookmark to your web browser, selecting it will attempt to reload your current page through the Libraries Proxy Server. If the page is one that you should be able to access through the Downstate library, you should get access to it.</p>

<hr>

<h3>Unrelated but... Panopto Downloading</h3>

<p> Here's another fun bookmarklet from John from COM 2020 that lets you download Panopto Lectures. Install the bookmarklet as detailed above. Here's the bookmarklet:
<br>
<a href="javascript:(function(){if(prompt('Hit Ctrl/Cmd-C to copy name to clipboard', document.title.replace(/[:\\/]/g, '-')+'.mp4')!=null){location.href=$('meta[name="twitter:player:stream"]').attr('content');}})();">Download Panopto</a>
<br>
Then just click the bookmark when you're on the video you want and it'll open the video in another tab. The alert box just gives you a chance to copy the name of the video. You can now download the video by right clicking and choosing "save as".
</p>




</body>
</html>
