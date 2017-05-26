# QCodeEditor

This project is just for fun and learning Qt.

To run the application, you have to install the [FakeVim](https://github.com/hluk/FakeVim) and [QCE](http://qcodeedit.org/) library.

## Installing the 3th party libs:

```
# installing FakeVim
git clone https://github.com/hluk/FakeVim.git
cd FakeVim
mkdir build
make
cd fakevim
sudo cp libfakevim* /usr/local/lib

# installing qce
git clone git://git.tuxfamily.org/gitroot/qcodeedit/qce3.git
cd qce3
mkdir build
make
sudo make install

```

## Installing

```
mkdir build
cd build
qmake ..
make
```


