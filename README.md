## Programmer Assessment Q4

# Instructions:
1. Open terminal
2. Enter commands:
sudo apt update
sudo apt install -y python3 python3-venv python3-pip git
3. Verify python installtion using:
python3 --version

git clone https://github.com/bxdda/Assessment-debugging.git
cd Assessment-debugging

4. Setup virtual environmnet for the app:
python3 -m venv .venv
source .venv/bin/activate

5. Install the app using the pyproject.toml:
pip install .

6. Run the app
python3 main.py

7. To access without port forwarding, use another machine on the same network, and go to the local ip address:port :
ip addr show to get the ip

Go to http://LOCAL-IP:10030/

This repository contains a broken web app built with Dash. Please follow the tasks below.

Tasks:
1. Clone this repo to your machine.
2. Fix missing dependencies and fill authors section in `pyproject.toml`.
3. Fix bugs prevent the app `main.py` from running.
4. Change port the app ruuning on to `10030`.
5. Commit you changes.
6. Update `README.md` with a instruction
   1. Assuming the user has a fresh minimum Linux installation with no python.
   2. Setup python and virtual environment for this app, remember to use the fixed `pyproject.toml`.
   3. How to run this app and how to access it without portforwarding.
7. Push all the changes to your own repository on Github, and provide a link to your own repo in your submission in the last.
