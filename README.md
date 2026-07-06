1.  Confirm that the Lenovo Power Manager device is installed in Device Manager -> System Devices.  This driver is installed automatically by Windows Update.  (See note below if you are deployment engineer and want to deploy the driver as part of MDT or SCCM.)

2.  Download ChargeThreshold.exe

3.  To set the charge threshold as 80%, run this command from a command prompt:  ChargeThreshold.exe on 80

4.  To disable the charge threshold:  ChargeThreshold.exe off

5.  To see more options:  ChargeThreshold.exe
