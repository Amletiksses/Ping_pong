from pygame import*
from time import time as timer

win_width = 900
win_height = 700
window = display.set_mode((win_width,win_height))
display.set_caption("Ping pong")

background = image.load('phone.jpg')
background = transform.scale(background, (win_width, win_height))

clock = time.Clock()
FPS = 60

