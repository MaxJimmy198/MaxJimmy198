https://qyapi.weixin.qq.com/cgi-bin/webhook/send?key=420a58a9-65a1-40c2-8782-c0bb7791c37c

pip3 install weworkbot
pip install weworkbot

from weworkbot import Bot as wBot

wbot(url).set_text("hello world").send()
wBot(url).set_text('<font color="info">Hello world</font>', type='markdown').send()
wBot(url).set_image_path('test.jpeg').send()
