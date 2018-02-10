# EFI
 Lenovo rescuer 15-ISK hackintosh@10.12 EFI

1. CPU: Intel Core i7 6700hq
2. mem: 8GB ddr4 2133 MHz
3. Graphics: Intel HD 530
4. AC: bcm 94532z(maybe I forget it)
.....
 
update at 2017-10-20

1. fix the appleALC device.
2. fix the ELAN touchPad device. but It looks don't work very well.
	1. deleted the VoodooPS2Controller.kext 
	2. add the ApplePS2SmartTouchPad.kext
3. the bluetouch can't connect other device after I use the bsm 94353z.  
