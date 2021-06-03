# videos

Some videos support 30 seconds project

### command

```
ffmpeg -i result.mp4 -i ../1.mp3 -vf "subtitles=1.srt:force_style='FontName=kaiti TC Bold,MarginV=30'" -shortest -y final.mp4
```
