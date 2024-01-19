---
layout: page
slide_id: 4
---

<div class="row">

<div class="col-xs-12 col-sm-12 col-md-12 col-lg-10 offset-lg-1 col-xl-10 offset-xl-1">


<div id="adobe-dc-view" style="width: 800px;"></div>
<script src="https://documentservices.adobe.com/view-sdk/viewer.js"></script>
<script type="text/javascript">
	document.addEventListener("adobe_dc_view_sdk.ready", function(){ 
		var adobeDCView = new AdobeDC.View({clientId: "495ed6c10b7249d3910dc4699522bcc8", divId: "adobe-dc-view"});
		adobeDCView.previewFile({
			content:{location: {url: "/assets/timetable.pdf"}},
			metaData:{fileName: "timetable.pdf"}
		}, {embedMode: "IN_LINE"});
	});
</script>

<ul>
<li> <a href="/assets/timetable.pdf">Schedule </a> </li>
</ul>

<!--<li> <a href="/assets/book-of-abstracts.pdf"> Book of Abstracts </a> </li>>
<!--<li> <a href="/shortcourse"> Short course: Modern STL </a> </li>>
<!--<li> <a href="https://www.youtube.com/playlist?list=PL7vEgTL3FalZ7xBUvYrlgacIhc3CqbYAM">Recorded talks</a> </li>>
<!--<li> <a href="https://zenodo.org/communities/wamta23/?page=1&size=20">Collection of slides and posters</a> </li>>

{% include contact-us.html %}
