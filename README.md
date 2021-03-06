### MultiTool
**Batch process Media-Files with ffmpeg/mkvmerge/MediaInfo.**


![Screenshot](https://user-images.githubusercontent.com/107532220/174289562-497e83b4-2577-4acc-af0a-2d7dd0910d59.png)


_________________________________________________________________

### Usage

Put MultiTool in the same folder as your Media files

Run .exe

Choose Option

Wait for it to finish
_________________________________________________________________

### Updating

Just replace the old .exe with the new one
_________________________________________________________________

### Beta Release

MultiTool has the following features in v0.8.13

O  Extract Media Information to .txt. Such as:
- [ ]    Track ID
- [ ]    Track Name
- [ ]    Number of Tracks
- [ ]    Language
- [ ]    Codecs
- [ ]    Bitrate
- [ ]    Frequency
- [ ]    ...

O  Convert Videos to .mkv using ffmpeg
- [ ]    Choose compression rate (CRF) from 18-24
- [ ]    Copy Audio Stream without changes
- [ ]    Copy Subtitle without changes
- [ ]    libx265 codec
- [ ]    10bit
- [ ]    AQ Mode 3 specialized to Dark Scenes
- [ ]    Tune Option for Animation or Grain

O  Convert Audio to .mp3 or .ogg using ffmpeg
- [ ]    Choose Frequency between Variable, 41khz or 48khz 
- [ ]    Choose Bitrate from Variable, 128kbit to 320kbit
- [ ]    Stereo (2 Channel)
- [ ]    Vorbis or MPEG Layer 3

O  Play Media Files using ffplay

O  Rename Track ID 0-2 to English or Japanese

O  Change Default Track Flags for ID 0-2 to English or Japanese   

O  Change Aspect Ratio to 16:9 or 4:3

O  Extract Chapter and Attachments
_________________________________________________________________

### Different Versions:
**Setup** version can be extracted and used anywhere and is the same as the .rar version.

The **Portable** Version deletes the Bin folder after use to keep the working folder clean.
(start is slow because of the extraction process)

**Standalone.rar** is the updated MultiTool.exe without the Bin folder. It can be used to quickly update the MultiTool
without the need to download the big Bin folder again. 
_________________________________________________________________

### Containers currently supported:
**MediaInfo:**
 
(.3gp .avi .m2ts .mkv .mp4 .mov .mpeg .ogv .vob .webm .wmv)
(.aac .ac3 .acm .flac .m4a .mka .mp2 .mp3 .oga .ogg .opus .vorbis .wav .wma)


**ffplay:**

(.3gp .avi .m2ts .mkv .mp4 .mov .mpeg .ogv .vob .webm .wmv)
(.aac .ac3 .acm .flac .m4a .mka .mp2 .mp3 .oga .ogg .opus .vorbis .wav .wma)


**ffmpeg video convert:**
(.avi .m2ts .mkv .mp4 .vob)


**ffmpeg audio convert:**
(.aac .ac3 .acm .flac .m4a .mka .mp2 .mp3 .oga .ogg .opus .vorbis .wav .wma)


**mkvextract:**
 
(.m2ts .mkv .mp4  .vob)


**mkvpropedit:**
 
(.avi .m2ts .mkv .mp4 .mpeg .ogv .vob) 


**mkvmerge:**
 
(.avi .m2ts .mkv .mp4 .mov .mpeg .ogv .vob .webm .wmv)  
_________________________________________________________________

### Changelog:


**0.8.13**

-added audio convert option

-minor cosmetic fixes

-new icon


**0.7.12**

-added "-scodec copy" to ffmpeg commands.

-fixed a bug in ffmpeg normal option, which made option 7-9 not selectable.

-changed title name.


**0.7.10**

-First Beta Release.
