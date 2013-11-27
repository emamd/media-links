media-links
====================

An inline link script for multimedia storytelling. Customized to work inside the LA Times hella hacky CMS. But will probably work for you, with some customization. 

For ease of including in the CMS, everything is included in one file. 

inline links for:
	- videos 
		- brightcove
		- youtube
		- vimeo
		- NDN
	- static images
	- document snippets from Document Cloud

So how does this work? 
----------------------
Just wrap your work with a tag in the following format:
*For document cloud and image embeds:
	<pre>\<span class="media-link" data-type="XXX" data-url="XXX" data-width="XXX"\>Wrapped term here\</span\></pre>
** data-type will be "document" or "graphic"
** data-url is the URL of the document or graphic embed

*For video embeds:
	<span class="media-link" data-type="XXX" data-vid="XXX" data-width="XXX">Wrapped term here</span>
** data-type will be video-brightcove, video-youtube, video-vimeo or video-ndn
** data-vid is the ID of the video you are trying to pull in
