---
title:  "ultimatevocalremovergui"
search: false
categories: 
  - aws
last_modified_at: 2021-08-12T08:06:00-05:00
---


```bash
### aws t4g ubuntu18.04 ultimatevocalremovergui
sudo apt-get update
sudo apt-get install python3-pip python3-dev python-virtualenv
sudo pip3 install -U pip
virtualenv --system-site-packages -p python3 ~/virtualenvs/py3
source ~/virtualenvs/py3/bin/activate
sudo apt-get install -y python3-opencv
sudo apt install llvm-8-dev
sudo ln -s /usr/bin/llvm-config-8 /usr/bin/llvm-config
pip install --no-cache-dir -r requirements.txt
sudo apt-get install libsndfile1-dev

```
