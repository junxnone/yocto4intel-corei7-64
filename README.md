
### yocto build Linux OS for intel-corei7-64
> If you want to know more about yocto, please refer the [wiki](https://github.com/junxnone/yocto4intel-corei7-64/wiki)

# Clone this project
```
git clone https://github.com/junxnone/yocto4intel-corei7-64.git 
cd yocto4intel-corei7-64
git submodule update --init --recursive
```

# Build this project

```
source poky/oe-init-build-env intel-corei7-64/
bitbake core-image-sato
```

# Flash the xxx.hddimg to the usb flash drive /dev/sdx
```
dd if=./xxx.hddimg of=/dev/sdx bs=4M status=progress
```

