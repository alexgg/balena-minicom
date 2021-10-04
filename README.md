```
# Default to /dev/ttyUSB0 @115200
export N=0
balena run --rm -it --device=/dev/ttyUSB$N:/dev/minicom -e BAUDRATE=115200 aggurio/balena-minicom
```
