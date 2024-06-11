# ISC_NIRScan_Tiva_FW

Please refer to the document - "APN - First Time to Update TIVA Firmware.pdf" if you are not familiar with the Tiva FW update.

# v2.6.3 (MD5:D97B1DC407B81B8479CFEC8EFCE93DF1)

1. Add internal EEPROM backup/restore factory calibration parameters functionality.
2. Add splashing LED at boot-up.
3. Check lamp existence at boot-up.
4. Minor bugs fixed.

# v2.4.10 (MD5:5bc66e18ebd0961001b1702df42e45ee)

1. Improved M/B and D/B version detecting accuracy.  

2. Add system parameters self-check at boot-up.

3. Minor bugs fixed.

# v2.4.7 (MD5:63174705FC2A065DB0D5B14033B9E1F6)

1. Remove default button lock on BLE connection.

# v2.4.6 (MD5:7799C23EE505545364B7176F333B9C00)

1. Fix BLE setting active configuration by wrong index mapping.

2. Minor bugs fixed.

# v2.4.4 (MD5:d838e5b0bf870ccc4f0d6c399abd0493)

1. Add API for getting BD Address.

2. Scan stability and quality fine tune.

3. Minor bugs fixed.

# v2.4.1 (MD5:fdc1c4bdb12e45e29ff38946d6ecec6f)

1. Fixed BLE can not read battery capacity in battery power mode.

# v2.4.0 (MD5:7aec6b3bac477ca421747d9f6d448483)

1. Support hardware version upto version "F".

2. Added new error code for system errors. (Scan unstable detected for lamp/ADC only for version "F" and beyond)

3. Added lock/unlock physical scan button control APIs.

4. Added APIs for users to customize the Bluetooth LE advertising name.

5. Disable the physical device scan button while Bluetooth data is in the transaction.

6. Support legacy reference data for upgrade/downgrade Tiva FW (Auto converting device reference data).

7. Minor bugs fixed.   

# v2.3.2

1. Based on v2.1.0.67, create specific glitch filter switch API and limited the glitch filter function with only Column type, exposure time at 0.635ms for user selectable.

2. Send out error indication if UUID read failed.

3. Add boot-modes selection right after power-up the device. Change the behavior for selecting boot-modes - slow blinking LEDs after user confirms action.

4. Modify APIs for capable changing the version string of calib, scan cfg and refcalib data.

5. Modify to support 8 digits serial number writing.

6. Create battery regulation voltage setting API.

7. Minor bugs fixed.

# v2.1.2

1. Fixed BLE returned active config with a truncated index

# v2.1.0.73b

1. Fixed UART communication problem.

# v2.1.0.72

1. Add watchdog to recover from system hanged.

2. Set a valid string for BLE when the model name or serial number is NULL.

3. Minor bugs fixed.

# v2.1.0.67

1. Improve scan glitch issue.

2. Remove TI's UART unfinished solution that causing UART no response.

3. Add BLE services for lamp usage, lamp mode control, lamp delay time, scan PGA and number of repeats.

4. Add BLE configuration set/write services.

5. Fix BLE broadcasting with a blank model name issue.

6. Add charger status to BLE devices.

7. Minor bugs fixed.

# v2.0.22

1. Add Red LED status: On - Charging in progress, Blinking - Battery Low

2. Computation of Scan Time changed to support variable exposure times across sections.

3. Slew Scan capability added. Capability to support different exposure times for different sections.

4. Minor bugs fixed.

# License - InnoSpectra Corp.

Copyright (c) 2017, InnoSpectra Corporation, All rights reserved.

# License - Texas Instruments

Refer to "DLP_Spectrum_Library_SLA.rtf"

# License - TPL

The BSD License

Copyright © 2005-2013, Troy D. Hanson http://troydhanson.github.com/tpl/ All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
