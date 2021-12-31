# CommonStuff


Changing C++ versions to C++14 or basically G++5.5:
```
sudo update-alternatives --remove-all gcc 
sudo update-alternatives --remove-all g++

sudo apt-get install gcc-5 g++-5

sudo update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-5 10
sudo update-alternatives --install /usr/bin/g++ g++ /usr/bin/g++-5 10

sudo update-alternatives --config gcc
sudo update-alternatives --config g++
```

If you have multiple versions and you want to prioritize 2 versions then check this link: https://askubuntu.com/questions/26498/how-to-choose-the-default-gcc-and-g-version
