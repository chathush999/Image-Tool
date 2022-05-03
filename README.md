
# 🎨 Logo Maker 🎨

import requests

API = 'https://host.single-developers.software/logo?name='

req = requests.post(API+input('Name : ').replace(' ','%20'))

print(req.history[1].url)

import requests

API = 'https://host.single-developers.software/logohq?name='

req = requests.post(API+input('Name : ').replace(' ','%20'))

## deploy to heroku ##
<a href="https://heroku.com/deploy?template=https://github.com/chathush999/Image-Tool">
            <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">

