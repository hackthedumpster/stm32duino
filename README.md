stm32duino from st with xpack requirement replaced with gcc-arm-none (so arm64
will work) and usb support for nucleo 144 F767ZI added, also usb composite
cdc/msc added, serial pins correctly setup for st-link cdc, i2c pins on pb8 and pb9

requires arduino m0 support to be installed from board manager and currently
choosing non composie usb support "only" cdc will fail. This is ruff but working.
currently upload method mass storage tested and working.
