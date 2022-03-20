====== Archive.org media posting on Self Hosted Wordpress ======
===== Using Wordpress built in player =====

  - Upload the audio to archive.org
  - Get the link of the audio as shown in the picture
  - {{:archive_org_media.png?500|}}
  - then embed the following code in the wordpress
  - <html>[embed]https://archive.org/download/olacab_geoblr_feb2015/olacab_geoblr_feb2015.mp3[embed]</html>
  - Wordpress will automatically create a player and embed it in the post

===== Using shortcode =====
  - Install [[https://wordpress.org/plugins/archiveorg-wp/|archiveorg-wp]] plugin and activate it
  - Go to archive.org page 
  - Get the embedID from the URL
  - For example: for the url https://archive.org/details/GeoBLRMarch2015FrancescaR
  - embedID is **GeoBLRMarch2015FrancescaR**
  - Place the shortcode [archive-org embed=GeoBLRMarch2015FrancescaR] into any post or page. embedID can be found on the Archive.org website at the tail end of the URL for a video or audio item or playlist. The plugin automatically recognizes playlists.
  - Optional Parameters:
     - width = width in pixels of the embedded player
     - height = height in pixels of the embedded player
     - playlist = true/false - determines whether a dropdown list of all the files is displayed
   - For example if you want to specify width and height 
<HTML>
<code>
[archive-org embed="GeoBLRMarch2015FrancescaR" width="500" height="30"]
</code>
</HTML>