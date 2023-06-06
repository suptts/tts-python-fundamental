[![Python application test with Github Actions](https://github.com/suptts/tts-python-fundamental/actions/workflows/testing_ci.yml/badge.svg)](https://github.com/suptts/tts-python-fundamental/actions/workflows/testing_ci.yml)

# tts-python-fundamental
This is learning python project for tts devops2023


Create a virtualenv: `virtualenv ~/.venv`
edit `vim ~/.bashrc` 
add this code: `source ~/.venv/bin/activate`
clone project then run `make all`

หรือเขียนเป็น venv.sh
#!/usr/bin/env bash

python3 -m venv ~/.venv
echo "source ~/.venv/bin/activate" >> .bashrc

source ~/.venv/bin/activate

save แล้วสั่งรัน
source venv.sh
