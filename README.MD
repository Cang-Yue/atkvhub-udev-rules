# udev rules for ATK V HUB

## Usage

``` bash
git clone git@github.com:Cang-Yue/atkvhub-udev-rules.git
cd ./atkvhub-udev-rules/
sudo cp -rf ./99-atkvhub.rules /etc/udev/rules.d/

```

Then reboot your system.

## Warning

Only supported Vendor ID

``` text
0x3554
0x373b
```
