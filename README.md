<div align="center">

## Use Javascript to Disable Windows Print Screen Key


</div>

### Description

It's easy! Just need to change a line in your HTML.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[vivalite](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/vivalite.md)
**Level**          |Beginner
**User Rating**    |3.2 (29 globes from 9 users)
**Compatibility**  |
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__2-57.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/vivalite-use-javascript-to-disable-windows-print-screen-key__2-3337/archive/master.zip)





### Source Code

<body>
<p><span>replace &lt;body> with:</span></p>
<p><span>&lt;body onload=setInterval("window.clipboardData.setData('text','')",20)></span></p>
<p><span>PS:The drawback of this way is it also
clear any clipboard data other than image. So your browser can't do "copy
paste" properly during the page open.</span></p>

