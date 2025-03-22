# friendlyarm_neo
git clone --depth 1 -b scarthgap git://git.yoctoproject.org/poky
git clone --depth 1 -b scarthgap https://github.com/openembedded/meta-openembedded.git
git clone --depth 1 -b scarthgap https://github.com/linux-sunxi/meta-sunxi.git
git clone --depth 1 -b scarthgap git://git.yoctoproject.org/meta-arm
# add these layers:
core                  /home/henry/Tests/nanopi/source/poky/meta                               5
yocto                 /home/henry/Tests/nanopi/source/poky/meta-poky                          5
yoctobsp              /home/henry/Tests/nanopi/source/poky/meta-yocto-bsp                     5
arm-toolchain         /home/henry/Tests/nanopi/source/meta-arm/meta-arm-toolchain             5
meta-arm              /home/henry/Tests/nanopi/source/meta-arm/meta-arm                       5
openembedded-layer    /home/henry/Tests/nanopi/source/meta-openembedded/meta-oe               5
meta-python           /home/henry/Tests/nanopi/source/meta-openembedded/meta-python           5
sunxi                 /home/henry/Tests/nanopi/source/meta-sunxi                              10

# set MACHINE = "nanopi-neo" in local.conf
