# python

//code to make subclip from a clip
from moviepy.editor import *
clip = VideoFileClip(r"C:\Users\NITESH KOLI\Desktop\my folder\bad_guy.mp4")
clip = clip.subclip(0,60)

clip.ipython_display(width = 480,maxduration = 206)
