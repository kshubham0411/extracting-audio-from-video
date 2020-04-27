# extracting-audio-from-video
# helping people listen to audio alone from their favorite video using python

import moviepy.editor
video=moviepy.editor.VideoFileClip("video url.mp4")
audio=video.audio
audio.write_audiofile("audio.mp3")
