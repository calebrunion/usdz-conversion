# USDZ Conversion

## Build USD on Ubuntu 20.04 
1. Update 
```
apt update && apt upgrade -y
```
2. Install [USD](https://github.com/PixarAnimationStudios/USD)
C++ compiler:
```
apt install python3 python-pip3 curl git build-essential nasm cmake
```
Download USD:
```
git clone https://github.com/PixarAnimationStudios/USD
```

2. PIP
```
pip install pyopengl and pyside6
```
4. 3.[Install Open GL](https://www.includehelp.com/linux/how-to-install-opengl-in-ubuntu-linux.aspx): `apt install freeglut3-dev` and then `apt install binutils-gold g++ mesa-common-dev cmake libglew-dev build-essential libglew1.5-dev libglm-dev`
5. Build with `python3 usd_from_gltf/tools/ufginstall/ufginstall.py /usr/local/UFG /usr/local/USD`
