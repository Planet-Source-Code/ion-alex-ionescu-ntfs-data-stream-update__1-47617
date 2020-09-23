<div align="center">

## NTFS Data Stream Update


</div>

### Description

Hi everyone,

Included in the ZIP file is a new version of the NTFS Alternate Data Stream code. It fixes all the bugs listed below, and add new features. All of these have been kindly given as suggestions from everyone on the site, and I wish to thank you!

If you'd like to read the original article and vote on it (if you haven't seen it already), it's located at: http://www.planetsourcecode.com/vb/default.asp?lngCId=47299&lngWId=1
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |2003-08-11 13:49:02
**By**             |[Ion Alex Ionescu](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/ion-alex-ionescu.md)
**Level**          |Advanced
**User Rating**    |5.0 (30 globes from 6 users)
**Compatibility**  |VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0, VB Script
**Category**       |[Files/ File Controls/ Input/ Output](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/files-file-controls-input-output__1-3.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[NTFS\_Data\_1627938112003\.zip](https://github.com/Planet-Source-Code/ion-alex-ionescu-ntfs-data-stream-update__1-47617/archive/master.zip)





### Source Code

<b>The following bugs have been fixed in this revision:
</b>
<p>- Clicking cancel on the dialog box no longer switches to open mode.
<br>
- Choosing a menu option when no stream is selected no longer crashes the app
<br>
- The Path to Wordpad isn't hard coded anymore
<br>
- The app won't crash on a FAT-32 system anymore
<br>
- The GUI won't freeze after a long amount of files beeing scanned
</p>
<p><b>The following new features have been added:
</b></p>
<p>- You can now double-click on a file in seek mode to open it for stream editing.
<br>
- Two new functions, <i>GetWordPadPath</i> and <i>CheckStreamCapability</i> to support localized and non-NTFS systems
<br>
- You can now close the application during a search<br>
- Streams are displayed as they are found, not only at the end of a search.</p>
<p>The 0-byte bug seems to be a Windows API bug, I will report it to Microsoft.
</p>
<p>Finally, if you liked the update or have any comments about it, please post it as a comment either here or on the original article.
Also, if you've never read the article before, please read it at the link above and vote for it if you liked it.</p>

