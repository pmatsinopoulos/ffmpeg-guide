# Convert VOB (DVD) to MP4

```
ffmpeg -i VTS_01_1.VOB -b:v 1500k -r 30 -vcodec h264 -strict -2 -acodec aac -ar 44100 -f mp4 convert.mp4
```

# Add srt to mp4

```
ffmpeg -i iron-man-3.mp4 -i iron-man-3-gr-subtitles-as-downloaded.srt -scodec mov_text iron-man-3-gr.mp4
```

# Convert mp4 to mp3

```
ffmpeg -i foo.mp4 foo.mp3
```
