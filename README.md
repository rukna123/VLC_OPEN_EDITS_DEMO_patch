# VLC_OPEN_EDITS_DEMO
Apply this patch to VLC player and then run VLC as followsit as following

$>./vlc --load_cut \<EMD file created by creator\> \<Main Video file\>

This will play the Main video with skips defined in EMD text file as intervals to skip

NOTE: It is recommended that you run an EMD text file that has linear time splits for this patch to work
      For example:
            30 60
            90 120
      Not Example:
            40 20
            60 10
      Moreover don't seek during the play.

REPORT ISSUE: Although this patch was tested for what it promises; 
              in case of any issue with patch, please revert back
            
