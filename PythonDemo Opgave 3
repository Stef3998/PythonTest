from sense_hat import SenseHat
import time

senseHat = SenseHat()

B = (102, 51, 0)
r = (255,0,0)
g = (0,255,0)
b = (0,0,255)
S = (205,133,63)
W = (255, 255, 255)

senseHat.set_pixel(2, 2, (0, 0, 255))
senseHat.set_pixel(4, 2, (0, 0, 255))
senseHat.set_pixel(3, 4, (255, 255, 0))
senseHat.set_pixel(1, 5, (255, 0, 0))
senseHat.set_pixel(2, 6, (255, 0, 0))
senseHat.set_pixel(3, 6, (255, 0, 0))
senseHat.set_pixel(4, 6, (255, 0, 0))
senseHat.set_pixel(5, 5, (255, 0, 0))
senseHat.set_pixel(0, 4, (255 ,0, 0))
senseHat.set_pixel(6, 4, (255, 0, 0))

time.sleep(1)

creeper_pixels = [
    g, g, g, g, g, g, g, g,
    g, g, g, g, g, g, g, g,
    g, b, b, g, g, b, b, g,
    g, b, b, g, g, b, b, g,
    g, g, g, b, b, g, g, g,
    g, g, b, b, b, b, g, g,
    g, g, b, b, b, b, g, g,
    g, g, b, g, g, b, g, g
]

senseHat.set_pixels(creeper_pixels)

time.sleep(1)

steve_pixels = [
    B, B, B, B, B, B, B, B,
    B, B, B, B, B, B, B, B,
    B, S, S, S, S, S, S, B,
    S, S, S, S, S, S, S, S,
    S, W, b, S, S, b, W, S,
    S, S, S, B, B, S, S, S,
    S, S, B, S, S, B, S, S,
    S, S, B, B, B, B, S, S
]

senseHat.set_pixels(steve_pixels)

time.sleep(1)

senseHat.clear()
