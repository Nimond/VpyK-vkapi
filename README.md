# VpyK - simple vk.com api library for python 3.x

***-How to start longpolling?***
```python
from VpyK import vkapi
access_token = 'YOUR ACCESS TOKEN'
v = '8.92'
bot = vkapi(access_token, 'last')

while True:
	print(bot.check_longpoll())
```
