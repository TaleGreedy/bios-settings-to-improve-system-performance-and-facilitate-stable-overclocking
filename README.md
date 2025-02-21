# bios-settings-to-improve-system-performance-and-facilitate-stable-overclocking
these settings have been duly tested and approved, they will improve the way your computer uses energy, removing any kind of limitation or energy saving. And they will improve overall performance, with lower inputlag, higher fps and stability.	

# HARDWARE TEST SETTINGS
Computer Type: Desktop
GPU: EVGA NVIDIA RTX 3060 Ti 8GB
CPU: Ryzen 7 5800X 
Motherboard: TUF GAMING B450-PLUS
BIOS Version: 4622
RAM: 2x16 Asgard Loki W3 4000Mhz CL14 B-die
PSU: EVGA 650W 80 Plus Gold
Case: Montech Air 903 Max
Operating System & Version: WINDOWS 11 PRO 24h2
GPU Drivers: GEFORCE GAME READY DRIVER - WHQL Driver Version: 457.51
Background Applications: Msi

Bios Settings
FIRST STEP: (IMPORTANT BACKUP YOUR SYSTEM FILES BEFORE)
							DISABLE CSM, THEN GO TO SECURE BOOT TYPE AND
							SELECT THE WINDOWS UEFI MODE OPTION, THEN GO TO KEY MANAGEMENT AND SELECT THE CLEAR SECURE BOOT KEYS OPTION, 
			 				THEN SELECT LOAD DEFAULT SECURE VARIABLES, THEN SAVE AND EXIT THE BIOS, AND LOG IN AGAIN. AFTER THIS PROCESS 
							WE CAN MOVE ON TO THE NEXT STEP. 
			 				**IT IS IMPORTANT TO DO THIS PROCESS FIRST**
				
PSS Support - Disable
NX Mode - Disable
SVM Mode - Disable
SMT Mode - Enable
Above 4g Decoding - Enable
Resize BAR Support - Auto
SR-IOV Support - Disable
SMEE - Disable
TSME - Disable
DF Cstates - Disable
APBDIS - set to 1
CPPC - Disable
CPPC Prefered Cores - Disable
Chipset power saving features - Disable
SoC/Uncore OC Mode - Enabled
PCI-X Latency Timer - set to “32 PCI Bus Clocks “0x20””
Power down enabled - Disable
ECO Mode - Disable
LN2 Mode - Auto
Core performance boost - Disable
Global cstate control - Disable
IOMMU - Auto
Fixed SOC Pstate - P0
Q-FAN Tuning - Coloque tudo no turbo e faça uma curva de fan de preferencia.
DIGI +VRM CPU LOADLINE CALIBRATION – REGULAR
DIGI +VRM SOC LOADLINE CALIBRATION – REGULAR

Note: disabling the SMT Mode setting, especially on AMD processors! I haven't tested it on intel processors! so i dont know! 
If you deactivate it, you will have a very considerable gain in games, depending on the game! However,
I recommend that you test it. What it does is deactivate the virtual cores and leave only the real cores
running, maintaining a more stable clock, a much lower temperature with lower voltage, requiring less
and being able to improve performance, but as I said, it depends on the game. And for multitasking,
you'll lose performance, so test it out! These settings are basic and will make any overclocking you want to do more stable and
safe, other than that, they alone will improve your performance, but I strongly recommend that you
overclock your cpu.

Another good system settings

NVIDIA Twerk - Only Nvidia GPU (Highly recommended) 
DOWNLOAD THIS: https://drive.google.com/file/d/1jesBD5BDvEOrtSM6KdiABbY_Y8TUKaGh/view?usp=sharing
                            Run the file as administrator. Ready.

MSI Utility Aplication
Your GPU - Check the MSI box and set interrupt priority to high
Intel Ethernet server adapter - Check the MSI box and set interrupt priority to high

DEBLOATED WINDOWS 11 (Recommended) 
https://github.com/memstechtips/Winhance

CMD (Administrator)
run the commands 1 at a time
bcdedit /set useplatformtick yes
bcdedit /set disabledynamictick yes
bcdedit /setuseplatformclock false
powercfg.exe /hibernate off
sfc /scannow

REGEDIT 
Local machine -> system -> currentcontrolset -> control -> class -> 4d36e968 ->
0000 -> Dword32bts = DisableDynamicPState = 1

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\DriverSearching]
"SearchOrderConfig"=dword:00000000

[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Power]
HiberBootEnabled"=dword:00000000

[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power]
"HibernateEnabled"=dword:00000000

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Serialize]
"StartupDelayInMSec"=dword:00000000

[HKEY_CURRENT_USER\Control Panel\Mouse] "MouseHoverTime"="10"

[HKEY_CURRENT_USER\Control Panel\Desktop] "MenuShowDelay"="0"

Disable Telemetry
https://drive.google.com/file/d/1CiHhfULMB1j5V7IpoEOqwaPB8b7O__l7/view?usp=sharing
Open WPD
- in privacy -- disable telemetry and block telemetry ips
- in blocker – Blocking method – Windows defer firewall = (ON)
- rule sets -> ativar telemetry e extra
Open OOSU10
- go to actions, and activate the option “apply only recommended
settings” and then check the boxes to see if there's anything you use.

do the basic windows optimizations, such as power plan, remove apps you don't use, disable as much of the system startup as possible, disable xbox game bar, disable game overlay and hardware acceleration in discord and steam. 

disable services you dont need. 
		i recommended this video guide: https://www.youtube.com/watch?v=uRsBpDR2CNg
	
#### by. Tale Greedy ####
 #Thanks!




