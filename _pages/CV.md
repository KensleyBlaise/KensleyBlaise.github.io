---
title: 
layout: single 
author_profile: true 
permalink: /cv/
---
<div id="adobe-dc-view" style="width: 800px;"></div>
<script src="https://documentservices.adobe.com/view-sdk/viewer.js"></script>
<script type="text/javascript">
	document.addEventListener("adobe_dc_view_sdk.ready", function(){ 
		var adobeDCView = new AdobeDC.View({clientId: "<YOUR_CLIENT_ID>", divId: "adobe-dc-view"});
		adobeDCView.previewFile({
			content:{location: {url: "assets/images/CV_Kensley_Blaise.pdf"}},
			metaData:{fileName: "CV_Kensley_Blaise.pdf"}
		}, {embedMode: "IN_LINE"});
	});
</script>
---

