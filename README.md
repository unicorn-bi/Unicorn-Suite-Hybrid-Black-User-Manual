# Unicorn Suite Hybrid Black User Manual


[Glossary](#glossary)<br/>
[Safety Notice](#safety-notice)<br/>

[Introduction](#introduction)<br/>
&nbsp;&nbsp;&nbsp;[Highlights](#highlights)<br/>
&nbsp;&nbsp;&nbsp;[Intended use](#intended-use)<br/>
&nbsp;&nbsp;&nbsp;[Conditions of use](#conditions-of-use)<br/>

[Software System Requirements](/Installation/softwareRequirements.md)<br/>
[Installation](/Installation/installation.md)<br/>
[Software Prerequisites](/Installation/softPrerequisites.md)<br/>

### Amplifier

[Technical Specifications](TechnicalSpecifications.md)<br/>
[Electromagnetic compatibility EMC](#electromagnetic-compatibility-emc)<br/>
[Declaration of conformity](#declaration-of-conformity)<br/>
[General notes](TechnicalSpecifications.md)<br/>

[Unicorn Hybrid Black](UnicornHybridBlack.md)<br/>
[Unicorn Naked BCI](UnicornNaked.md)<br/>

### Programming Interfaces

[Unicorn APIs](https://github.com/unicorn-bi/Unicorn-Hybrid-Black-Windows-APIs)<br/>
&nbsp;&nbsp;&nbsp;[Unicorn C API](https://github.com/unicorn-bi/Unicorn-Hybrid-Black-Windows-APIs/blob/main/c-api/unicorn-c-api.md)<br/>
&nbsp;&nbsp;&nbsp;[Unicorn .NET API](https://github.com/unicorn-bi/Unicorn-Hybrid-Black-Windows-APIs/blob/main/dotnet-api/unicorn-dotnet-api.md)<br/>
&nbsp;&nbsp;&nbsp;[Unicorn Python API](https://github.com/unicorn-bi/Unicorn-Hybrid-Black-Windows-APIs/blob/main/python-api/unicorn-python-api.md)<br/>
&nbsp;&nbsp;&nbsp;[Unicorn Simulink Interface](https://github.com/unicorn-bi/Unicorn-Hybrid-Black-Windows-APIs/blob/main/simulink-interface/unicorn-simulink-interface.md)<br/>

[Unicorn Network Interfaces](https://github.com/unicorn-bi/Unicorn-Network-Interfaces-Hybrid-Black/tree/main)<br/>
&nbsp;&nbsp;&nbsp;[Unicorn LSL](https://github.com/unicorn-bi/Unicorn-Network-Interfaces-Hybrid-Black/tree/main/LSL)<br/>
&nbsp;&nbsp;&nbsp;[Unicorn UDP](https://github.com/unicorn-bi/Unicorn-Network-Interfaces-Hybrid-Black/tree/main/UDP)<br/>

### Applications
Unicorn Recorder<br>
[Unicorn Bandpower](https://github.com/unicorn-bi/Unicorn-Bandpower-Hybrid-Black)<br/>
[Unicorn Blondy Check](https://github.com/unicorn-bi/Unicorn-Blondy-Check-Hybrid-Black)<br/>
[Unicorn Speller](https://github.com/unicorn-bi/Unicorn-Speller-Hybrid-Black)<br/>
Unicorn Painting<br/>
Brainbuddy<br/>
Platformer<br/>

## Glossary

<table>
    <tr>
        <th><span style="font-size: larger;">Wording</span></th>
        <th><span style="font-size: larger;">Explanation</span></th>
    </tr>
    <tr>
        <td>Unicorn Brain Interface</td>
        <td>The amplifier (device) including battery and electrode connectors.</td>
    </tr>
    <tr>
        <td>Unicorn Hybrid EEG Electrodes</td>
        <td>Disposable electrodes for R and L clip connectors.</td>
    </tr>
    <tr>
        <td>Unicorn Sticky Electrodes</td>
        <td>Disposable electrodes for R and L clip connectors.</td>
    </tr>
    <tr>
        <td>Unicorn Bluetooth Dongle</td>
        <td>The Bluetooth dongle delivered with the Unicorn Brain Interface.</td>
    </tr>
    <tr>
        <td>Unicorn USB Charging Cable</td>
        <td>The USB cable delivered with the Unicorn Brain Interface.</td>
    </tr>
    <tr>
        <td>Unicorn Cap</td>
        <td>The EEG cap delivered with the Unicorn Brain Interface.</td>
    </tr>
    <tr>
        <td>Unicorn Suite Hybrid Black</td>
        <td>The Unicorn software environment.</td>
    </tr>
    <tr>
        <td>Unicorn Hybrid Black</td>
        <td>The Unicorn Brain Interface bundle referring to the version Hybrid Black. This bundle includes Unicorn Brain Interface Hybrid Black, 8 Unicorn Hybrid EEG Electrodes, 50 pieces Unicorn Sticky Electrodes, Unicorn Cap Size M, Unicorn USB Charging Cable, Unicorn Bluetooth dongle and the Unicorn Suite Hybrid Black.</td>
    </tr>
    <tr>
        <td>R</td>
        <td>The electrode clip for the Unicorn Sticky Electrode on the right mastoid. </td>
    </tr>
    <tr>
        <td>L</td>
        <td>The electrode clip for the Unicorn Sticky Electrode on the left mastoid.</td>
    </tr>
    <tr>
        <td>Unicorn Gel</td>
        <td>The conductive electrode gel for Unicorn Hybrid EEG Electrodes.</td>
    </tr>
    <tr>
        <td>Unicorn .NET API</td>
        <td>The Unicorn C# library. </td>
    </tr>
    <tr>
        <td>Unicorn Python API</td>
        <td>The Unicorn Python library.</td>
    </tr>
    <tr>
        <td>Unicorn Simulink Interface</td>
        <td>The Unicorn Simulink Interface application.</td>
    </tr>
    <tr>
        <td>Unicorn block</td>
        <td>The MATLAB Simulink block for the Unicorn.</td>
    </tr>
    <tr>
        <td>Unicorn C API</td>
        <td>The Unicorn C library.</td>
    </tr>
    <tr>
        <td>Unicorn Speller</td>
        <td>The P300 Spelling application.</td>
    </tr>
    <tr>
        <td>Unicorn Sphero</td>
        <td>The P300 based Sphero control application.</td>
    </tr>
    <tr>
        <td>Unicorn Painting</td>
        <td>The P300 based painting application.</td>
    </tr>
    <tr>
        <td>Unicorn Recorder</td>
        <td>The recording application for Unicorn Brain Interface.</td>
    </tr>
    <tr>
        <td>Unicorn Hybrid Black User Manual</td>
        <td>The user manual for the Unicorn Brain Interface version Hybrid Black.</td>
    </tr>
</table>

## Safety Notice
In order to use this product safely and fully understand all its functions, read this manual before using the product. Follow the instructions for use for the used PC and the connected devices for allowed environmental conditions. The used PC must not go to sleep, hibernate, turn off, or turn on the screensaver during a measurement.

**Warning:**<br>
Conductible parts of all Unicorn Hybrid EEG Electrodes must not have contact with the earth or other conductible parts.

**Warning:**<br>
Avoid electrostatic discharge impulses when handling the device or touching the Unicorn Hybrid EEG Electrodes.

**Warning:**<br>
Pay attention to the precautions regarding electromagnetic compatibility.

**Warning:**<br>
The operation of the device can be compromised within shielded rooms. In case of problems, relocate the receiving device or consult technical support.

**Warning:**<br>
The operator must be familiar with the operation of the device and must operate the device according to the instructions for use.

**Warning:**<br>
The device and its accessories must not be exposed to increased mechanical stress.

**Warning:**<br>
Each time you use the device, you must first check the device and its accessories for possible damage to connectors, sockets and cables. Check the Unicorn Hybrid EEG electrode cable connections with special care and ensure that the electrode cables have no breaks or cracks. Any cables, connectors, accessories, or other parts of the equipment must be replaced immediately if damaged or not working correctly.
The Unicorn Brain Interface is not protected against electrical defibrillation - before defibrillation, the Unicorn Hybrid EEG Electrodes must be removed from the subject!

**Warning:**<br>
Only use accessories identified for use with this device.

**Warning:**<br>
The device is powered internally via a lithium-ion polymer accumulator. The accumulator must only be replaced by the manufacturer.

**Note:**<br>
The Unicorn Brain Interface uses special lightweight, thin and highly flexible cables for the Unicorn Hybrid EEG Electrodes to provide high comfort and easy cap mounting, especially for multi-channel recording. These cables are sensitive and need to be treated with special care. Following some basic guidelines will prolong the lifetime of Unicorn Hybrid EEG Electrodes:
    - Never pull on Unicorn Hybrid EEG Electrodes cables.
    - Avoid knots in cables.
    - Do not soak cables and Unicorn Hybrid EEG Electrodes for more than 30 minutes.
    - Avoid exposure to direct sunlight or chemical agents.
    - Make sure that no Unicorn Gel remains on Unicorn Hybrid EEG Electrodes or cables after cleaning.
    - Protect the amplifier unit from contamination with Unicorn Gel, water or disinfectant.
    - Always make sure that Unicorn Hybrid EEG Electrodes, cables and Unicorn caps are completely dry before storing.
    - Don’t cut, kink or pinch electrode cables; light bending is safe.

**Note:**<br>
Unicorn Hybrid EEG Electrode and cable lifetime depends on proper usage, careful treatment and cleaning, and appropriate storage. The manufacturer will provide warranty replacement only if there is no visible physical damage to the parts, such as: damaged, broken or pinched cables; or damaged housings or connectors.
   
**Warning:**<br>
- Do not use any detergent other than detergents mentioned in this manual!
- Do not perform automated reprocessing in Washer Disinfectors (WD) or Endoscope Washer Disinfectors (EWD)!
- Do not machine-wash!
- Do not use a laundry dryer or other hot air devices!
- Do not put into an ultrasonic bath!
- Do not autoclave Unicorn caps or Unicorn Hybrid EEG Electrodes!

**Note:**<br>
The manufacturer is responsible for the safety, performance and reliability of the Unicorn Brain Interface as supplied to the customer at the time of delivery. This responsibility expires if the Unicorn Brain Interface is changed. Please note the following:
    - Changes to the Unicorn Brain Interface must be performed by the manufacturer only, and service and repair must be performed by corresponding qualified personnel only.
    - The Unicorn Brain Interface must be used according to the instructions for use.

**Note:**<br>
The Unicorn Brain Interface and its components have been tested and comply with the electromagnetic compliance limits for the Directive 2014/53/EU (radio equipment directive, RED). See the chapter on Electromagnetic compatibility. The equipment, if not installed and used in accordance with the instructions, may cause interference with other devices in the vicinity. If this equipment does interfere with other devices, which can be determined by turning the equipment off and on, try to correct the interference through one or more of the following measures:
    - Reorient or relocate the receiving device.
    - Increase the separation between the equipment.
    - Consult Unicorn technical support.

**Warning:**<br>
The Unicorn Brain Interface must not be used in dangerous conditions such as wet rooms or explosive environments. The relative humidity must be between 25 % and 80 %. The Unicorn Brain Interface must not be used in combination with any other high-frequency device. Using a high frequency device with the Unicorn Brain Interface can cause burning under the Unicorn Hybrid EEG Electrodes and could damage the Unicorn Brain Interface.

**Warning:**<br>
The Unicorn Brain Interface must not be used in humans with pace-makers or electrical stimulators.

**Note:**<br>
The Unicorn Brain Interface uses the 2.4 GHz band for wireless transmission. Ensure that enough transmission bandwidth is available in your environment, since other devices might also use the same band (e.g. WiFi or other Bluetooth devices).

## Introduction
The Unicorn Brain Interface is a consumer grade biosignal amplifier kit. It allows developers, artists and makers to integrate signals from the human body within their projects – ranging from simple display of the signals to designing and controlling attached devices and interacting with artistic installations, toys, computer programs or apps and more. The Unicorn Brain Interface acquires the EEG from eight Unicorn Hybrid EEG Electrodes. The Unicorn Brain Interface consists of the Unicorn Brain Interface Hybrid Black, Unicorn C Size M, Unicorn Hybrid EEG Electrodes, Unicorn USB Charging Cable and a Unicorn Bluetooth dongle to acquire data on a computer. The Unicorn Suite is the software environment, consisting of standalone applications and APIs to interface the Unicorn Brain Interface, acquire and process data and to perform BCI paradigms.

### Highlights
- EEG recordings without cable connection via radio signal
- Bluetooth 2.1 interface
- Hybrid electrodes for wet and dry measurements
- 8 DC-coupled analog input channels with 24 Bit resolution
- sampling rate of 250 Hz per channel
- oversampling to achieve a high signal-to-noise ratio
- input sensitivity of ± 750 mV
- 3-axis accelerometer
- 3-axis gyroscope

### Intended use
The Unicorn Brain Interface is intended for use in non-medical environment for non-medical applications. The Unicorn Brain Interface is used by developers, artists, makers and gamers in the user’s environment.

### Conditions of use
#### Operation and storage
Temperature: +5 to +40 °C<br>
Relative humidity: 25 to 80 %, non-condensing<br>
Atmospheric pressure: 700 to 1060 hPa


## Unicorn Brain Interface
<p align="center">
<table>
    <tr>
        <th><span style="font-size: larger;">Technical Specifications</span></th>
        <th><span style="font-size: larger;"></span></th>
    </tr>
    <tr>
        <td>Model</td>
        <td>Unicorn Hybrid Black</td>
    </tr>
    <tr>
        <td>Type</td>
        <td>8-channel amplifier</td>
    </tr>
    <tr>
        <td>Battery</td>
        <td>350 mAh, IEC 62133 (ed.2)</td>
    </tr>
    <tr>
        <td>Rated power consumption</td>
        <td>0.3W</td>
    </tr>
    <tr>
        <td>Rated DC voltage</td>
        <td>3.7 V</td>
    </tr>
    <tr>
        <td>Rated current of fuse</td>
        <td>Little fuse 0467001.NR (1.0 A)</td>
    </tr>
    <tr>
        <td>Rated voltage of fuse</td>
        <td>32 V</td>
    </tr>
    <tr>
        <td>Manufacturer</td>
        <td>g.tec neurotechnology GmbH<br/>Sierningstrasse 14<br/> 4521 Schiedlberg, Austria</td>
    </tr>
</table>
</p>

**Warning:**

Do not short circuit the battery. <br/> Do not expose cells or batteries to heat or fire.

## Unicorn Brain Interface settings
<p align="center">
<table>
    <tr>
        <th><span style="font-size: larger;">Technical Specifications</span></th>
        <th><span style="font-size: larger;"></span></th>
    </tr>
    <tr>
        <td>Channels</td>
        <td>1 to 8 and R channel</td>
    </tr>
    <tr>
        <td>Sensitivity</td>
        <td>± 750 mV</td>
    </tr>
    <tr>
        <td>Highpass</td>
        <td>0 Hz</td>
    </tr>
        <tr>
        <td>Lowpass</td>
        <td>10.23 kHz</td>
    </tr>
        <tr>
        <td>Input impedance</td>
        <td>>100 M</td>
    </tr>
</table>
</p>

### Analog-Digital-Converter (ADC)
<p align="center">
<table>
    <tr>
        <th><span style="font-size: larger;">Technical Specifications</span></th>
        <th><span style="font-size: larger;"></span></th>
    </tr>
    <tr>
        <td>Resolution</td>
        <td>24 Bit</td>
    </tr>
    <tr>
        <td>Sampling frequency</td>
        <td>250 Hz</td>
    </tr>
    <tr>
        <td>Number of ADCs</td>
        <td>8</td>
    </tr>
</table>
</p>

## Motion Tracking
<p align="center">
<table>
    <tr>
        <th><span style="font-size: larger;">Technical Specifications</span></th>
        <th><span style="font-size: larger;"></span></th>
    </tr>
    <tr>
        <td>Acceleration range</td>
        <td>± 8 g setting in x, y and z directions</td>
    </tr>
    <tr>
        <td>Acceleration bandwidth</td>
        <td>44.8 Hz</td>
    </tr>
    <tr>
        <td>Gyroscope range</td>
        <td>± 1000 °/s setting in x, y and z directions</td>
    </tr>
    <tr>
        <td>Gyroscope bandwidth</td>
        <td>41 Hz</td>
    </tr>
</table>
</p>

## RF module
<p align="center">
<table>
    <tr>
        <th><span style="font-size: larger;">Technical Specifications</span></th>
        <th><span style="font-size: larger;"></span></th>
    </tr>
    <tr>
        <td>Operating Frequency range</td>
        <td>2400.0 … 2483.5 MHz (ISM Band)</td>
    </tr>
    <tr>
        <td>Transmit power Max</td>
        <td>+3 dBm</td>
    </tr>
    <tr>
        <td>Receiver sensitivity</td>
        <td>-86 dBm</td>
    </tr>
    <tr>
        <td>Compliance</td>
        <td>Bluetooth specification, version 2.1 + EDR</td>
    </tr>
        <tr>
        <td>Marking</td>
        <td>CE, FCC, IC, Japan and South-Korea</td>
    </tr>
        <tr>
        <td>FCC ID</td>
        <td>QOQWT12</td>
    </tr>
        <tr>
        <td>IC</td>
        <td>5123A-BGTWT12A</td>
    </tr>
        <tr>
        <td>Japan</td>
        <td>R 209- J00036</td>
    </tr>
</table>
</p>

This Unicorn Brain Interface complies with Part 15 of the FCC Rules. Operation is subject to the following two conditions: (1) this Unicorn Brain Interface may not cause harmful interference, and (2) this Unicorn Brain Interface must accept any interference received, including interference that may cause undesired operation.

### FCC RF Radiation Exposure statement
This Unicorn Brain Interface complies with Industry Canada license-exempt RSS standard(s). Operation is subject to the following two conditions: (1) this Unicorn Brain Interface may not cause interference, and (2) this Unicorn Brain Interface must accept any interference, including interference that may cause undesired operation of the Unicorn Brain Interface.

Under Industry Canada regulations, this radio transmitter may only operate using an antenna of a type and maximum (or lesser) gain approved for the transmitter by Industry Canada. To reduce potential radio interference to other users, the antenna type and its gain should be chosen so that the equivalent isotropically radiated power (e.i.r.p.) is not more than that necessary for successful communication.

**Note:**

The Unicorn Brain Interface uses the 2.4 GHz band for wireless transmission. Ensure that enough transmission bandwidth is available in your environment, since other devices might also use the same band (e.g. WiFi or other Bluetooth devices). Use wireless screening tools to ensure the availability of the necessary transmission channel.

## Classification
- Protection against mechanical distortion and liquids: IP40
- Operation mode: S1 (Permanent operation)

## Transportation and storage conditions
The Unicorn Brain Interface can be stored at temperatures between –20° to +45° Celsius. The relative humidity must be between 25 % and 80 %. If there is any condensed water, wait until it disappears before use (wait at least 1 h in a heated room).

## Location details
Do not use the Unicorn Brain Interface near a heating system or directly in the sun. During operation, the outside temperature should be between +5 Celsius and +35 Celsius and the air pressure between 700 and 1060 hPa.

## Wast disposal details
Bring the Unicorn Brain Interface to a recycling center or sent it back to the manufacturer.

## Warranty
Warranty in the EU is 6 month and 30 days in other countries for the Unicorn Brain Interface. The Unicorn Hybrid EEG Electrodes, the Unicorn Gel and the disposable Unicorn Sticky Electrodes are consumables. Only use parts from g.tec to operate the Unicorn Brain Interface. Warranty is invalidated if anyone except a g.tec employee opens or disassembles any components of the Unicorn. Warranty only applies for properly used devices. Please note that any damage resulting from improper treatment of the system will not be covered by the warranty. This may include broken, kinked or damaged wires and cables, damaged isolators and enclosures

### Electromagnetic compatibility (EMC)
The EMC declaration is available on request.

### Declaration of Conformity
The declaration of conformity is available on request.

<br/>
Contact email: hello@unicorn-bi.com<br>
For more information, visit: www.gtec.at<br>
Copyright © 2024 g.tec medical engineering GmbH Austria