---
title: 
layout: single 
author_profile: true 
permalink: /cv/
<div id="adobe-dc-view" style="width: 800px; height: 600px;"></div>
<script src="https://documentcloud.adobe.com/view-sdk/main.js"></script>
<script type="text/javascript">
  document.addEventListener("adobe_dc_view_sdk.ready", function() {
    var adobeDCView = new AdobeDC.View({ clientId: "YOUR_CLIENT_ID", divId: "adobe-dc-view" });
    adobeDCView.previewFile(
      {
        content: { location: { url: "PATH_TO_YOUR_PDF_FILE" } },
        metaData: { fileName: "YOUR_FILE_NAME.pdf" }
      },
      { embedMode: "IN_LINE" }
    );
  });
</script>
---
