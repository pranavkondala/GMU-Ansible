If you have an existing Linux environment that you're comfortable managing, the main steps are:
```
wget -O tutorial.tgz https://github.com/bronwynlewis/ansible-network-automation-tutorial/archive/master.tar.gz
tar xzf tutorial.tgz
cd ansible-network-automation-tutorial-master
sudo apt-get install python-pip python-dev
sudo pip install -r requirements.txt
```
### failure to build cryptography

If, in the ```pip install -r requirements.txt``` step, the cryptography build and subsequently the package installation fails, then you should check if all the dependencies are met. Check out this Stack Overflow post on the subject: [Failed to install Python Cryptography package with PIP and setup.py](https://stackoverflow.com/questions/22073516/failed-to-install-python-cryptography-package-with-pip-and-setup-py)
