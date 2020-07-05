```
$arduino-cli board list
Port         Type              Board Name  FQBN            Core
/dev/ttyACM0 Serial Port (USB) Arduino Uno arduino:avr:uno arduino:avr
/dev/ttyS0   Serial Port       Unknown
/dev/ttyS1   Serial Port       Unknown
/dev/ttyS2   Serial Port       Unknown
/dev/ttyS3   Serial Port       Unknown

$arduino-cli core install arduino:avr
$arduino-cli compile --fqbn arduino:avr:uno hello-world/
$arduino-cli upload -p /dev/ttyACM0 --fqbn arduino:avr:uno hello-world/
```