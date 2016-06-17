# stream-iplayer
A script to make watching BBC iPlayer live streams in VLC less of a chore.

get-iplayer is a very powerful tool for downloading and watching programmes on 
the BBC iPlayer via the command line. However for simply watching a live stream 
of one of the TV channels I find its syntax very verbose. This means either
remembering a whole bunch of flags or scrolling back through you bash history.

This script is intended to make things easier. It requires the VLC media player.

Example usage:

stream-iplayer -c "bbc one"

stream-iplayer -r -c "radio 1"
