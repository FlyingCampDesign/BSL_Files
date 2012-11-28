README FIRST

This is the zip file containing support files for the Texas Instruments 
User Gudie: MSP430 Programming Via the Bootstrap Loader (SLAU319)

Directory Description:

BSL Patch         - Directory containg BSL images for use with older 1xx BSLs 
BSL Scripter      - Directory containing the BSL Scripting Application for use with 5/6xx BSLs
  /Demo Scripts   - Demo Scripts for use with the BSL Scripter Application, seperated by device and purpose
  /source         - The Source code used to compile the Scripter Application
                  - NOTE: This project requires the following files for USB communication
                    - hid.lib, hidclass.lib, hidparse.lib, hidpi.h, hidsdi.h, hidusage.h
                    - the files listed above can be downloaded from: http://www.microsoft.com/whdc/ddk/winddk.mspx
Deprecated        - Directory containing older projects which will not receive future updates
  /BSL Replicator - A multi-BSL programmer
  /BSLDEMO        - The command line demo utility for communication with 1/2/4xx BSLs