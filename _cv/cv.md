	- - - 
	title: Curriculum Vitae
	categories: 
		- Experience
	tags: 
		- pdf
	- - -
## Here's an in-line of my CV

<div id="adobe-dc-view" style="width: 800px;"></div>
<script src="https://documentservices.adobe.com/view-sdk/viewer.js"></script>
<script type="text/javascript">
	document.addEventListener("adobe_dc_view_sdk.ready", function(){ 
		var adobeDCView = new AdobeDC.View({clientId: "<YOUR_CLIENT_ID>", divId: "adobe-dc-view"});
		adobeDCView.previewFile({
			content:{location: {url: "https://documentservices.adobe.com/view-sdk-demo/PDFs/Bodea Brochure.pdf"}},
			metaData:{fileName: "Bodea Brochure.pdf"}
		}, {embedMode: "IN_LINE"});
	});
</script>


