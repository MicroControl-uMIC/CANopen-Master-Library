# CANopen FD Master Libary

This repository holds the latest version of the CANopen FD Master library for the µMIC.200 controller.


## Installation

After download of the `canopen_v5.06.00_arm.tgz` file to the µMIC.200 controller use the following
steps for installation:

```
tar -xzvf canopen_v5.06.00_arm.tgz
cd canopen_v5.06.00_arm
sudo ./install.sh
```

## Linking to the library

Please make sure to use the following settings in your projekt to use the library:

```
-lCANopenFD -lCANpieFD
```
  