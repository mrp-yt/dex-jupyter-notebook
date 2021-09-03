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

*Optional*
Usefull packages that works well with Jupyter
```
LDFLAGS="-lm -lcompiler_rt" pip install numpy matplotlib
```

