
<div><img src="https://github.com/puutaro/sendClipToGmail/assets/55217593/3ef6597f-0007-487f-af81-62b6cdd8d70d" width="300">  </div>
  
<div><img src="https://github.com/puutaro/selectTyper/assets/55217593/555e8f5f-656a-4faf-bb76-f663c01cfe47" width="300"></div> 


# sendClipToGmail


Send clipboard contents to Gmail draft @puutaro

Table of Contents
-------
<!-- vim-markdown-toc GFM --> 
* [Cmd Variables](#cmd-variables)
	* [gmailDraftUrl](#gmaildrafturl)
	* [gmailDraftListURL](#gmaildraftlisturl)
	* [play](#play)
* [Setting variables](#setting-variables)
	* [terminalFontZoom](#terminalfontzoom)
	* [terminalFontColor](#terminalfontcolor)
	* [terminalColor](#terminalColor)

## Cmd Variables
--------
### gmailDraftUrl 
Paste gmail draft url
### gmailDraftListURL 
Paste gmail draft list url
### play 
Depend on state, change execute like bellow table.

| state | execute content | 
| --------- | --------- |
| `gmailDraftUrl` doesn't launch | Launch `gmailDraftUrl` |
| `gmailDraftUrl` launch and gmail bocy blank | Paste clipboard |
| `gmailDraftUrl` launch and gmail body has been written | Save draft gmail |


## Setting variables
---------
### terminalFontZoom
Adjust terminal font size (percentage)
### terminalFontColor
Adjust terminal font color
### terminalColor
Adjust terminal background color
