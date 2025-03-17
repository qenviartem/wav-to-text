# wav-to-text



ffmpeg -i input.mp4 -vcodec libx265 -crf 35 output_compressed.mp4


Convert wav to text

ffmpeg -i input.mp4 -q:a 0 -map a output_audio_0018.wav

