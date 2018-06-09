
### yocto build Linux OS for intel-corei7-64


# Clone this project
```
git clone https://github.com/junxnone/yocto4intel-corei7-64.git 
cd yocto4intel-corei7-64
git submodule update --init --recursive
```

# build this project

```
source poky/oe-init-build-env intel-corei7-64/
bitbake core-image-sato
```
