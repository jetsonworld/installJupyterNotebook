# 젯슨나노에서 주피터노트북과 주피터랩을 설치하기:
***

먼저 Ctrl + Alt + T 단축키를 눌러서 터미널을 엽니다.

```
sudo apt update
wget https://bootstrap.pypa.io/get-pip.py
sudo python2 get-pip.py
sudo python3 get-pip.py

sudo apt install python3-pip
sudo apt install python3-pil
sudo apt install python-pip
sudo apt install python-pil
sudo pip3 install --upgrade numpy
sudo pip2 install --upgrade numpy

sudo apt install nodejs
sudo apt install npm

sudo apt install jupyter
sudo pip3 install jupyterlab
sudo jupyter labextension install @jupyter-widgets/jupyterlab-manager
sudo jupyter labextension install @jupyterlab/statusbar
jupyter lab --generate-config
jupyter notebook password
sudo pip3 install pillow

- How To Excute:
jupyter notebook
jupyter lab

- Check the version:
jupyter --version
jupyter lab --version

python2 --version
python3 --version

pip2 --version
pip3 --version
pip --version

```
