# AWS_S3_Audio_Encoder_Script
Bash script to properly encode .mp3 audio files for uploading to AWS S3.

This script can be directed at a folder containing subfolders containing the .mp3 files to be encoded.


<h1>Requirements</h1>
<a href="https://www.ffmpeg.org/">FFmpeg</a>

<h1>File Structure</h1>
The current version of the script must be edited to be directed at folder containing sub-folders containing mp3 files.
*-Top-tier-folder
*
*--Subfolder
*    ---.mp3
*    ---.mp3
*
*--Subfolder
*    ---.mp3
*    ---.mp3
*...
