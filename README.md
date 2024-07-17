# Steps to build with this emulator device tree

- Clone this repository to device/fus0g/emu64x
- Then go to device/fus0g/emu64x do the bringup for specific ROM. If already done ignore this step.

# Source the build
```
. build/envsetup.sh
```

# Lunch the emulator
```
lunch euclid_emu64x-ap2a-user
```

# Start the build
```
make
```
OR
If the `make` does not work then try the below one
```
m
```

# Start the emulator
Once the build is done start the emulator using below command
```
emulator
```
Starting emulator for the first time takes a little time so wait patiently.
