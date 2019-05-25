Hardware/Software Setup (RCE)
=====================================

- To setup the RCE emulator software the process outlined in the YARR software section can be followed. You can also simply flash the board as well. The process to do this is outlined in the steps below. 


- For the system hardware to setup the full system you will need 
- A HSIO2 board
- Two FEB boards 
- An ethernet cable
- A PC with a 10G ethernet card
- An QSFP cable
- An SMA cable
- A DP to DP cable

- To replicate the system setup at the UW for RCE you will need
- An FEB board
- A KC705
- The Ohio Multi Chip FMC
- A mini-DP to DP cable
- An SMA cable
- To setup the system, the Ohio MMC card needs to be connected to the FMC HPC connector on the KC705 and port A needs to be connected to the mini DP cable. The mini DP cable needs to be connected to port X on the FEB board. Finally the SMA cables needs to be connected to USERCLK P on the KC705 and attached to the SMA port on the FEB board. 
- A block diagram of the hardware setup can be seen below.

.. image:: RCE_hardware.png 


