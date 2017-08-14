# raman_labview

FROG_average default allows you to take a FROG using the stage currently used for Reference by default. If you would like to
use a different Thorlabs stage, all you have to do is change the serial number in the first step of the code.

If you want to use a Newport stage (like the one currently used for AS 1), use the frog_newport_final code. This does the same
thing as FROG_average but with the Newport stage.

Finally, ionization_average records spectrograms using the time of flight spectrum from the Windows 2000 oscilloscope through
LAN. In order to use it, you will have to FIRST push the "Start VX11 server" button on the scope. This can be found in the tray on the
main screen (i.e. minimize the default Tekscope program, hover with your mouse over the tray, click the red icon, and select
"Start VX11 server"). Then you can start the Labview program.
