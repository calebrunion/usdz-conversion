# USDZ Conversion

## Build USD on CentOS
1. Dependancies 
```
yum update -y &&
yum install -y git python3 gcc-c++ nasm curl &&
python3 -m pip install --upgrade &&
pip install PySide2 cmake PyOpenGL
```
2. Build [USD](https://github.com/PixarAnimationStudios/USD)
```
git clone https://github.com/PixarAnimationStudios/USD &&
python3 USD/build_scripts/build_usd.py /usr/local/USD
```
3. PIP
```
pip install pyopengl and pyside6
```
4. Download USD:
```
git clone https://github.com/PixarAnimationStudios/USD
```
## Build UFG
1. 3.[Install Open GL](https://www.includehelp.com/linux/how-to-install-opengl-in-ubuntu-linux.aspx): `apt install freeglut3-dev` and then `apt install binutils-gold g++ mesa-common-dev cmake libglew-dev build-essential libglew1.5-dev libglm-dev`
2. Build with `python3 usd_from_gltf/tools/ufginstall/ufginstall.py /usr/local/UFG /usr/local/USD`
