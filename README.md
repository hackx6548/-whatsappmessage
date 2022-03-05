import pyautogui as pg
import time
time.sleep(1)

txt = open('annoy.txt')
a = 'Hey'

for i in txt:
    pg.write(a+' '+i)
    pg.press('Enter')
