# Run Jupyter Notebook on DeX (w/ Termux)

## Setup
Get Termux from F-Droid store\
Inside Termux run
```
pkg upgrade -y
```
After upgrade run 
```
apt install clang python fftw libzmq freetype libpng pkg-config libcrypt &&
LDFLAGS="-lm -lcompiler_rt" pip install jupyter &&
```
*Press `y` and Enter when promoted*\

If you get message that `pip` needs upgrade run this 
```
/data/data/com.termux/files/usr/bin/python3 -m pip install --upgrade pip
```

*(Optional)*
Usefull packages that works well with Jupyter
```
LDFLAGS="-lm -lcompiler_rt" pip install numpy matplotlib
```
To start Jupyter Notebook run
```
jupyter notebook
```
You will be presented with the link that you need copy/paste into your browser to access Jupyter Notebook
