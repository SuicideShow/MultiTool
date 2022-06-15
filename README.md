# MultiTool
Batch process Media-Files with ffmpeg/mkvmerge/MediaInfo
![Screenshot](https://user-images.githubusercontent.com/107532220/173764160-fa9403d7-292a-4117-bf1c-615aac9b5434.png)


### First Beta Release

MultiTool has the following features in v0.7.10

O  Extract Media Information to .txt. Such as:
- [ ]    Track ID
- [ ]    Track Name
- [ ]    Number of Tracks
- [ ]    Language
- [ ]    Codecs
- [ ]    Bitrate
- [ ]    Frequency
- [ ]     etc

O  Convert Videos to .mkv using ffmpeg
- [ ]    Choose compression rate (CRF) from 18-24
- [ ]    Copy Audio Stream without changes
- [ ]    libx265 codec
- [ ]    10bit
- [ ]    AQ Mode 3 specialized to Dark Scenes
- [ ]    Tune Option for Animation or Grain

O  Play Media Files using ffplay
O  Rename Track ID 0-2 to English or Japanese
O  Change Default Track Flags for ID 0-2 to English or Japanese    
O  Change Aspect Ratio to 16:9 or 4:3
O  Extract Chapter and Attachments
_________________________________________________________________

### Different Versions:
**Setup** version can be extracted and used anywhere and is the same as the .rar version.
The **Portable** Version deletes the Bin folder after use to keep the working folder clean (start is slow)
_________________________________________________________________

### Currently these containers are supported:
 **-MediaInfo:**
(.3gp .avi .m2ts .mkv .mp4 .mov .mpeg .ogv .vob .webm .wmv)
(.aac .ac3 .acm .flac .m4a .mka .mp2 .mp3 .oga .ogg .opus .vorbis .wav .wma)
 **-ffplay:**
(.3gp .avi .m2ts .mkv .mp4 .mov .mpeg .ogv .vob .webm .wmv)
(.aac .ac3 .acm .flac .m4a .mka .mp2 .mp3 .oga .ogg .opus .vorbis .wav .wma)
 **-ffmpeg:**
(.avi .m2ts .mkv .mp4 .vob) 
 **-mkvextract:**
(.m2ts .mkv .mp4  .vob)
 **-mkvpropedit:**
(.avi .m2ts .mkv .mp4 .mpeg .ogv .vob) 
 **-mkvmerge:**
(.avi .m2ts .mkv .mp4 .mov .mpeg .ogv .vob .webm .wmv)  
