# ISC_NIRScan_Tiva_FW

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
